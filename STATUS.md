# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #29 — 2026-08-21 around 18:45 AZT**.
- **Candidate pool: 239 total.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- Historical master candidates remain in `CANDIDATES.csv`; additive candidate ledgers continue through `CANDIDATES_RUN29.csv`.
- Rejected history is in `REJECTED.csv` plus additive ledgers through `REJECTED_RUN29.csv`.
- Repository remains the sole persistent source of truth.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. The old 100/100 completion rule is retired. Continue autonomous search and add new high-quality options until the user explicitly stops the process.

## Latest run result
Added **7** new candidates, C234–C240:
1. **Sabah Capital Partners — Kreditor mühasib — 91 — CORE / Priority A.** Near-direct AP/P2P role covering supplier and contractor invoices, document validation, bank statements, payment orders, creditor registers, cost-centre allocation and reconciliations. Exact current JobSearch listing states deadline **27.08.2026**. Main gaps: 1C and construction-specific Forma 2/3 documentation; compensation is candidate-dependent but unpublished.
2. **Sabah Capital Partners — Receivable Accountant / Debitor Borclar üzrə Mühasib — 89 — CORE / Priority A.** Strong AP-to-AR bridge through receivables monitoring, invoicing, payment posting, contract payment schedules and reconciliation. Current listing states deadline **26.08.2026**. Construction-sector accounting is the main gap; compensation unpublished.
3. **Qafqaz NET — Aparıcı Mühasib — 86 — CORE / Priority A.** Daily debtor/creditor monitoring, discrepancy resolution, financial/document checks and cross-functional coordination fit finance operations strongly. Current listing states deadline **26.08.2026**. Main gaps are 1C and Azerbaijani e-tax/statutory portal ownership.
4. **PASHA Insurance — Əməkhaqqı və İnsan Resursları əməliyyatları üzrə aparıcı / baş mütəxəssis — 84 — ADJACENT / Priority B.** ERP, Excel, payment accuracy, reporting, bonus/payment controls, budgeting and process automation transfer well. Exact listing states deadline **23.08.2026**. Direct payroll/HR administration, Labor Code/tax law and e-gov/isb.az are substantial gaps.
5. **AZCD Group — Xərclərə nəzarət üzrə mütəxəssis — 82 — ADJACENT / Priority B.** Budget-vs-actual control, cost variance analysis, cash-flow monitoring, reporting and supplier/contract checks fit reporting/control strengths. Current repost states deadline around **23–24.08.2026**. Direct construction cost-control and 1C are gaps.
6. **IRES — Business Controller — 81 — ADJACENT / Priority B.** Management reporting, KPIs, variance analysis, month-end support and cross-functional finance create attractive upside. Current listing states deadline **26.08.2026**. Direct FP&A/controlling, budgeting/forecasting and financial-modeling depth are the main gaps.
7. **Azerbaijan Automobiles — Aparıcı Mühasib — 79 — CORE / Priority B.** AR/AP, reconciliations, transaction controls, Excel and finance-risk review overlap strongly. Current listing states deadline **23.08.2026** and salary is interview-based. Local tax/statutory reporting, 1C and a six-day schedule reduce fit.

## Rejected / corrected this run
- **Buta Agro — Mühasib:** 800–1000 AZN, below target.
- **Fostanpak — Kiçik Mühasib:** 600 AZN and six-day schedule.
- **Target Logistics — Senior Accountant:** 2000 AZN with 15:00–01:00 hours; poor economics/lifestyle for scope.
- **Carlsberg Azerbaijan — Financial Planning, Reporting & Cost Control Specialist:** fresh-looking indexes exist, but exact requisition deadline was **15.08.2026**; retained as expired conflict, not a candidate.

## Browser-confirmed live subset
1. **Xsolla — Finance Coordinator — 86**.
2. **Unibank — Financial Efficiency Lead/Chief Specialist — 79**.
3. **Xsolla — Delivery Manager, Self-Service — 74** — remote/Baku — USD 30k–80k/year published.
4. **Bolt — Operations Manager — 71**.

## Data discipline
- `TOOL_SNAPSHOT` is discovery/current-looking evidence, not a guarantee of current browser availability.
- `USER_BROWSER_LIVE` and `USER_BROWSER_CLOSED` override snapshots.
- Do not move new rows into `VACANCIES.csv` without user-browser confirmation.
- Read `CANDIDATES.csv` plus all additive candidate ledgers and the full rejected history before deduplication.
- Continue to prefer current employer/careers/ATS evidence, exact URLs, explicit deadlines and legal Azerbaijan access.
- Never add obvious low-compensation or poor-fit roles just to increase the count.

## NEXT ACTION
1. Continue open-ended search; target roughly 6–10 genuinely useful new candidates per run when the market supports it.
2. Prioritize direct AP/Finance Ops, SAP/S4/MDG/master data, finance systems/ERP, treasury/payments, controls/reporting, process automation/RPA, data quality/governance and selective procurement/vendor/P2P roles.
3. Broaden fresh employer/ATS searches beyond increasingly saturated generic accounting/procurement boards, including Azerbaijan-eligible international remote roles; verify country eligibility rather than assuming `remote` means Azerbaijan.
4. Audit high-scoring `UNKNOWN` compensation roles when credible pay evidence appears; move clearly sub-target roles to rejected.
5. Dedupe against `CANDIDATES.csv`, `CANDIDATES_RUN15.csv` through `CANDIDATES_RUN29.csv`, `REJECTED.csv`, and all additive rejected ledgers before every addition.
6. Preserve browser-verification separation; `VACANCIES.csv` changes only on browser-confirmed evidence.
7. Continue until an explicit user stop instruction is recorded.
