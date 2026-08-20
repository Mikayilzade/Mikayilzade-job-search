# Job Search — Start Here

This repository is the source of truth for the autonomous job-search project.

## User interface
Open **`DASHBOARD.md`** first. It shows the current candidate pool, browser-confirmed live subset, salary/access, clickable links and scores.

`CANDIDATES.csv` — master pool of strong candidate vacancies.  
`VACANCIES.csv` — subset personally confirmed live by the user in a normal browser.  
`REJECTED.csv` — closed, expired, inaccessible, duplicate or seriously conflicted leads.  
`STATUS.md` — exact progress and NEXT ACTION.  
`RUN_LOCK.md` — prevents the manual chat and scheduled-task chat from writing at the same time.

## Goal
Continuously build a high-quality, scored pool of job opportunities for the candidate in Baku or accessible from Azerbaijan, with target compensation of at least **2,500 AZN net/month equivalent**, preferably materially higher. The former 100-candidate target was only a milestone. On 2026-08-20 the user explicitly removed the cap: **continue adding strong new options until the user explicitly stops the process**.

Browser freshness is a separate field because ChatGPT web can expose stale crawl snapshots. The user will manually open whichever candidates look attractive; do not block autonomous progress waiting for browser confirmation.

## Search philosophy
Search by transferable skills, not only by current title. Candidate profile is in `PROFILE.md`; scoring/freshness rules are in `SEARCH_RULES.md`.

## Mandatory run procedure
1. Read `RUN_LOCK.md` first and acquire the lock. If another non-expired run owns it, do not start.
2. Read `START_HERE.md`, `PROFILE.md`, `SEARCH_RULES.md`, `STATUS.md`, `CANDIDATES.csv`, `VACANCIES.csv`, `REJECTED.csv`, and `DASHBOARD.md`.
3. Resume from `STATUS.md` → `NEXT ACTION`.
4. Search broadly across Baku/local, explicit Azerbaijan remote and legally plausible international routes.
5. Evaluate fit, compensation likelihood, Baku access, lifestyle, upside and key gaps.
6. Deduplicate against `CANDIDATES.csv` and `REJECTED.csv`.
7. Add strong candidates to `CANDIDATES.csv` even when freshness evidence is only `TOOL_SNAPSHOT`, but label that honestly. Never call a snapshot definitely live.
8. Known 404/closed/expired roles do not count as candidates; preserve them in `REJECTED.csv`.
9. Update `DASHBOARD.md` and `STATUS.md`; update `VACANCIES.csv` only when browser-confirmed live evidence exists.
10. Release `RUN_LOCK.md` to `FREE` after all writes.

## Categories
- `CORE`: direct or near-direct fit with finance/AP/P2P/SAP/operations experience.
- `ADJACENT`: strong transferable-skill fit into a neighboring function.
- `STRETCH`: non-obvious role with a plausible path in and meaningful compensation/career upside.

## Completion condition
**Only an explicit user instruction to stop ends autonomous search expansion.** Do not stop because the pool reaches 100, 200, or another numeric threshold.
