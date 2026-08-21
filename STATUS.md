# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #34 — 2026-08-21 around 23:32 AZT**.
- **Candidate pool: 262 unique total.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- Historical master candidates remain in `CANDIDATES.csv`; additive candidate ledgers continue through `CANDIDATES_RUN34.csv`.
- Rejected history is in `REJECTED.csv` plus additive ledgers through `REJECTED_RUN34.csv`.
- Repository remains the sole persistent source of truth.
- Counter reconciliation: candidate IDs reach `C263`, but historical `C158` is absent, so the true unique count is 262.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue autonomous search and add new high-quality options until the user explicitly stops the process.

## Latest run result
Added **3** new candidates, C261–C263. The search deliberately kept the batch small rather than padding with weak or low-pay roles:
1. **AZCON Holding — Data idarəetməsi üzrə baş mütəxəssis — 87 — ADJACENT / Priority A.** Current AZCON/CareerA/BirJob indexes still list the Baku role. Data quality, metadata, master-data governance, controls, standards and cross-functional implementation map strongly to S4/MDG and process-standardization strengths. Main gaps: formal enterprise data-governance frameworks/catalog tooling and direct title experience. Compensation is agreement-based/unpublished.
2. **TuranBank — Əməliyyat riskləri üzrə aparıcı mütəxəssis / baş mütəxəssis — 82 — ADJACENT / Priority B.** Current Position.az listing runs through 23.08.2026. Process mapping, control-gap analysis, corrective-action tracking, root-cause analysis and reporting transfer well from finance controls/reconciliations/audit support. Main gap: banking operational-risk/RCSA/KRI methodology. Compensation unpublished.
3. **AZCON Holding — Chief Specialist, Organizational Development and Planning — 80 — ADJACENT / Priority B.** Fresh August SmartJob exact page and current AZCON/CareerA company indexes. Process diagnostics, maturity assessments, methodology/procedure improvement, standards, reporting and coordination transfer well, but organizational-development methodology is a meaningful domain shift.

## Rejected / watch this run
- **AZCON Holding — Strateji təşəbbüslər üzrə böyük analitik:** exact official AZCON page states the application period has ended. Aggregator/company indexes can still surface it, so employer-source closure is preserved in `REJECTED_RUN34.csv`.
- Several generic local accounting listings were not added because published market evidence remained clearly below the 2,500 AZN target or the role was dominated by statutory/tax ownership.

## Browser-confirmed live subset
1. **Xsolla — Finance Coordinator — 86**.
2. **Unibank — Financial Efficiency Lead/Chief Specialist — 79**.
3. **Xsolla — Delivery Manager, Self-Service — 74** — remote/Baku — USD 30k–80k/year published.
4. **Bolt — Operations Manager — 71**.

## NEXT ACTION
1. Continue open-ended search; target roughly 6–10 genuinely useful new candidates per run when the market supports it, but keep fewer when quality/economics do not justify more.
2. Prioritize direct AP/Finance Ops, SAP/S4/MDG/master data, finance systems/ERP, treasury/payments/settlements, controls/reporting, process automation/RPA and data quality/governance.
3. Search fresh employer/ATS sources beyond saturated generic accounting/procurement boards, including Azerbaijan-eligible international remote roles; verify country eligibility explicitly.
4. Continue early compensation filtering and do not inflate scores for unpublished local salaries.
5. Dedupe against `CANDIDATES.csv`, all `CANDIDATES_RUN*.csv`, `REJECTED.csv`, and all `REJECTED_RUN*.csv` before every addition.
6. Preserve browser-verification separation; `VACANCIES.csv` changes only on browser-confirmed evidence.
7. Continue until an explicit user stop instruction is recorded.
