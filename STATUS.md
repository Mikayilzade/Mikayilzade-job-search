# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Manual user-found vacancy review — 2026-08-22 around 00:22 AZT**.
- **Candidate pool: 265 unique total.**
- **Browser-confirmed live subset: 6.**
- User-facing interface: `DASHBOARD.md`.
- Historical master candidates remain in `CANDIDATES.csv`; additive candidate ledgers continue through `CANDIDATES_RUN36.csv`.
- Rejected history is in `REJECTED.csv` plus additive ledgers through `REJECTED_RUN35.csv`.
- Repository remains the sole persistent source of truth.
- Counter reconciliation: candidate IDs reach `C266`, but historical `C158` is absent, so the true unique count is 265.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue autonomous search and add new high-quality options until the user explicitly stops the process.

## Manual user-found review — 2026-08-22
The user supplied two exact OBA Glorri vacancy links and stated he found them himself; both are therefore recorded as `USER_BROWSER_LIVE`.

1. **OBA — Maliyyə üzrə Analtik (Logistika üzrə) — C266 — 79 — ADJACENT / Priority B.** This is a genuinely new candidate. Current public copies show logistics-expense analysis, supplier purchase/stock analysis, logistics KPI reporting, annual logistics budget preparation and forecast work. The strongest transferable pieces are Excel, supplier/P2P context, reporting, data discipline and variance analysis. Main gaps: minimum one year direct financial-analyst experience plus actual budgeting/forecasting ownership. Power BI and ACCA FA are preferences, not mandatory. Compensation remains unpublished. Public deadline evidence: around 11 Sep 2026.

2. **OBA — BI & SQL Reporting Specialist (Lead) — existing C124.** Not a new pool addition; it was already present from a JobSearch snapshot. The user supplied the current direct Glorri link, so verification is upgraded to `USER_BROWSER_LIVE`. Manual practical-fit re-review is **72/100** rather than the historical 78 because high SQL/complex-query skills, Power BI/Tableau experience and 2–3 years direct business/data analytics are explicit requirements. Data quality/governance, business requirements, reporting and advanced Excel remain strong transferable components. Public deadline evidence: around 12 Sep 2026.

## Browser-confirmed live subset
1. **Xsolla — Finance Coordinator — 86**.
2. **Unibank — Financial Efficiency Lead/Chief Specialist — 79**.
3. **OBA — Maliyyə üzrə Analtik (Logistika üzrə) — 79**.
4. **Xsolla — Delivery Manager, Self-Service — 74** — remote/Baku — USD 30k–80k/year published.
5. **OBA — BI & SQL Reporting Specialist (Lead) — 72 practical re-review**.
6. **Bolt — Operations Manager — 71**.

## NEXT ACTION
1. Continue open-ended search; target roughly 6–10 genuinely useful new candidates per run when the market supports it, but keep fewer when quality/economics do not justify more.
2. Prioritize direct AP/Finance Ops, SAP/S4/MDG/master data, finance systems/ERP, treasury/payments/settlements, controls/reporting, process automation/RPA and data quality/governance.
3. Search fresh employer/ATS sources beyond saturated generic accounting/procurement boards, including Azerbaijan-eligible international remote roles; verify country eligibility explicitly.
4. Search specifically for business-side SAP/ERP roles rather than technical Basis/ABAP/HCM configuration roles.
5. Continue early compensation filtering and do not inflate scores for unpublished local salaries.
6. Dedupe against `CANDIDATES.csv`, all `CANDIDATES_RUN*.csv`, `REJECTED.csv`, and all `REJECTED_RUN*.csv` before every addition.
7. Preserve browser-verification separation; `VACANCIES.csv` changes only on browser-confirmed evidence.
8. Treat strong SQL/BI/FP&A/budgeting/forecasting requirements as real gaps unless the user's manual review provides evidence of equivalent experience.
9. Continue until an explicit user stop instruction is recorded.
