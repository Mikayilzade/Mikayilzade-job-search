# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #35 — 2026-08-21 around 23:55 AZT**.
- **Candidate pool: 264 unique total.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- Historical master candidates remain in `CANDIDATES.csv`; additive candidate ledgers continue through `CANDIDATES_RUN35.csv`.
- Rejected history is in `REJECTED.csv` plus additive ledgers through `REJECTED_RUN35.csv`.
- Repository remains the sole persistent source of truth.
- Counter reconciliation: candidate IDs reach `C265`, but historical `C158` is absent, so the true unique count is 264.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue autonomous search and add new high-quality options until the user explicitly stops the process.

## Latest run result
Added **2** new candidates, C264–C265. The batch was intentionally small because fresh local searches produced many under-target or overly technical roles:
1. **Agro Food Investments — Operations Planning Specialist — 77 — ADJACENT / Priority B.** Current HRX/BirJob copies show a Baku full-time role through 26.08.2026. KPI reporting, resource planning, Excel/ERP, deviation analysis, cross-functional coordination and process improvement transfer well. Main gap: direct agricultural production/harvest/resource planning experience; compensation unpublished.
2. **Company- — SAP Administrator — 74 — ADJACENT / Priority C.** Current Position.az listing runs through 24.08.2026. SAP/S4 familiarity, process understanding, issue triage, change/release documentation and user support create a plausible systems bridge, but infrastructure/application administration and production technical ownership are substantial gaps. Employer identity and salary are undisclosed.

## Rejected / watch this run
- **FABER Construction — Procurement Specialist:** fresh listing, but 1,500–2,000 AZN and partial sixth workday.
- **FABER Construction — Financial Planning Specialist:** fresh listing, but 1,000–1,500 AZN and direct budgeting/forecasting gap.
- **Vertex — Junior Supply Chain Management Specialist:** 600–700 AZN + bonus; far below target.
- **Azercell — SAP Logistics (MM/SD/PM) Specialist:** requires 4–6 years direct functional configuration/implementation.
- **Azercell — SAP HCM & SuccessFactors Specialist:** requires 4+ years SAP HCM configuration plus SuccessFactors/CPI.
- **Respublika Diaqnostika Mərkəzi — Financial Analyst:** current through late August but published 1,500 AZN.

## Browser-confirmed live subset
1. **Xsolla — Finance Coordinator — 86**.
2. **Unibank — Financial Efficiency Lead/Chief Specialist — 79**.
3. **Xsolla — Delivery Manager, Self-Service — 74** — remote/Baku — USD 30k–80k/year published.
4. **Bolt — Operations Manager — 71**.

## NEXT ACTION
1. Continue open-ended search; target roughly 6–10 genuinely useful new candidates per run when the market supports it, but keep fewer when quality/economics do not justify more.
2. Prioritize direct AP/Finance Ops, SAP/S4/MDG/master data, finance systems/ERP, treasury/payments/settlements, controls/reporting, process automation/RPA and data quality/governance.
3. Search fresh employer/ATS sources beyond saturated generic accounting/procurement boards, including Azerbaijan-eligible international remote roles; verify country eligibility explicitly.
4. Search specifically for business-side SAP/ERP roles rather than technical Basis/ABAP/HCM configuration roles.
5. Continue early compensation filtering and do not inflate scores for unpublished local salaries.
6. Dedupe against `CANDIDATES.csv`, all `CANDIDATES_RUN*.csv`, `REJECTED.csv`, and all `REJECTED_RUN*.csv` before every addition.
7. Preserve browser-verification separation; `VACANCIES.csv` changes only on browser-confirmed evidence.
8. Continue until an explicit user stop instruction is recorded.
