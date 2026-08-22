# Job Search Run Lock

state: BUSY
owner: SCHEDULED_TASK
started_at_azt: 2026-08-22 11:53 AZT
expires_at_azt: 2026-08-22 12:38 AZT

## Protocol
This file prevents the manual chat and the scheduled-task chat from modifying the repository at the same time.

Before any search/audit run:
1. Fetch this file and note its current blob SHA.
2. If `state: BUSY` and `expires_at_azt` is still in the future, **do not start the run**. Report that another run is in progress and exit without changing search data.
3. If `state: FREE`, atomically update this same file using the fetched SHA to `state: BUSY`, set `owner` (`MANUAL_CHAT` or `SCHEDULED_TASK`), set current Baku start time, and set an expiry no more than 45 minutes later.
4. If the update fails because the SHA changed, another run acquired the lock first: re-fetch and obey the current lock.
5. Only after successfully acquiring the lock may the run read/modify `STATUS.md`, `VACANCIES.csv`, `REJECTED.csv`, or `DASHBOARD.md`.
6. At the end of the run, re-fetch this file and set it back to `FREE` if the current owner matches the run.
7. A stale `BUSY` lock whose expiry is in the past may be reclaimed using the same SHA-safe update procedure.

The lock is coordination only; GitHub remains the persistent source of truth.