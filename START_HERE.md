# Job Search — Start Here

This repository is the source of truth for the autonomous job-search project.

## User interface
Open **`DASHBOARD.md`** first. It is the human-readable view of the search: live count, salary, clickable apply links, freshness, fit breakdown, interview chance, gaps and priority.

`VACANCIES.csv` is the machine-readable ledger of vacancies that currently pass the strict live-route rule.  
`REJECTED.csv` stores closed, expired, conflicting, inaccessible and watch leads so they are not repeatedly rediscovered.  
`STATUS.md` stores exact progress and NEXT ACTION.  
`RUN_LOCK.md` prevents the manual chat and scheduled-task chat from writing at the same time.

## Goal
Find up to 100 **verified, realistically attainable** job opportunities for Mikayil in Baku or accessible from Azerbaijan, with target compensation of at least **2,500 AZN net/month equivalent**, preferably materially higher.

## Search philosophy
Search by transferable skills, not only by current title.

Candidate profile is defined in `PROFILE.md`.  
Search, freshness and scoring rules are defined in `SEARCH_RULES.md`.

## Mandatory run procedure
1. Read `RUN_LOCK.md` first and acquire the lock exactly as its protocol requires. If another non-expired run owns it, do not start.
2. After acquiring the lock, read `START_HERE.md`, `PROFILE.md`, `SEARCH_RULES.md`, `STATUS.md`, `VACANCIES.csv`, `REJECTED.csv`, and `DASHBOARD.md`.
3. Resume from `STATUS.md` → `NEXT ACTION`.
4. Search current public job sources and resolve the most exact live employer/ATS application route possible.
5. Verify current availability, location/work model, Baku hiring access, compensation evidence, skill fit, gaps, workload/risk and apply route.
6. Deduplicate against accepted and rejected/watch ledgers.
7. Count a role only if it passes the strict freshness rule. Discovery snippets do not count.
8. Store all six scoring components so `fit_score` is transparent arithmetic.
9. Update `VACANCIES.csv`, `REJECTED.csv`, `DASHBOARD.md`, and `STATUS.md` before ending the run.
10. Release `RUN_LOCK.md` back to `FREE` after all run writes are complete.

## Categories
- `CORE`: direct or near-direct fit with current finance/AP/P2P/SAP/operations experience.
- `ADJACENT`: strong transferable-skill fit into a neighboring function.
- `STRETCH`: non-obvious role with a plausible path in and meaningful compensation/career upside.

## Completion condition
Search phase completes at 100 accepted, currently verified opportunities. Then move to ranking, CV variants, vacancy-specific tailoring, and application sequencing.
