# Job Search — Start Here

This repository is the source of truth for the autonomous job-search project.

## User interface
Open **`DASHBOARD.md`** first. It is the human-readable view of the search: live count, salary, links, freshness, fit breakdown, interview chance, gaps and priority.

`VACANCIES.csv` is the machine-readable ledger of vacancies that currently pass the strict live-route rule.  
`REJECTED.csv` stores closed, expired, conflicting, inaccessible and watch leads so they are not repeatedly rediscovered.  
`STATUS.md` stores exact progress and NEXT ACTION.

## Goal
Find up to 100 **verified, realistically attainable** job opportunities for Mikayil in Baku or accessible from Azerbaijan, with target compensation of at least **2,500 AZN net/month equivalent**, preferably materially higher.

## Search philosophy
Search by transferable skills, not only by current title.

Candidate profile is defined in `PROFILE.md`.  
Search, freshness and scoring rules are defined in `SEARCH_RULES.md`.

## Mandatory run procedure
1. Read `START_HERE.md`, `PROFILE.md`, `SEARCH_RULES.md`, `STATUS.md`, `VACANCIES.csv`, `REJECTED.csv`, and `DASHBOARD.md`.
2. Resume from `STATUS.md` → `NEXT ACTION`.
3. Search current public job sources and resolve the most exact live employer/ATS application route possible.
4. Verify current availability, location/work model, Baku hiring access, compensation evidence, skill fit, gaps, workload/risk and apply route.
5. Deduplicate against accepted and rejected/watch ledgers.
6. Count a role only if it passes the strict freshness rule. Discovery snippets do not count.
7. Store all six scoring components so `fit_score` is transparent arithmetic.
8. Update `VACANCIES.csv`, `REJECTED.csv`, `DASHBOARD.md`, and `STATUS.md` before ending the run.

## Categories
- `CORE`: direct or near-direct fit with current finance/AP/P2P/SAP/operations experience.
- `ADJACENT`: strong transferable-skill fit into a neighboring function.
- `STRETCH`: non-obvious role with a plausible path in and meaningful compensation/career upside.

## Completion condition
Search phase completes at 100 accepted, currently verified opportunities. Then move to ranking, CV variants, vacancy-specific tailoring, and application sequencing.
