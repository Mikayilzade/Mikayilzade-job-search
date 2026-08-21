# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #26 — 2026-08-21 around 15:40 AZT**.
- **Candidate pool: 220 total.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- Historical master ledger: `CANDIDATES.csv` (C001–C143).
- Additive ledgers: `CANDIDATES_RUN15.csv` through `CANDIDATES_RUN26.csv`. Treat all together as the current source of truth until consolidation.
- Rejected history is in `REJECTED.csv` plus additive rejected ledgers through `REJECTED_RUN26.csv`.
- Repository remains the sole persistent source of truth.

## Counter note
The highest candidate ID is C221 while the absolute pool is 220 because prior candidate C158 was removed after published compensation proved materially below target. Do not infer pool size from the highest ID alone.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue adding high-quality options until the user explicitly stops the process.

## Latest run result
Added **6** new candidates, C216–C221:
1. **ABB-İnvest — Aparıcı mühasib — 86 — CORE / Priority A.** Daily accounting, 1C control and Excel fit well; exact current listing gives deadline 17.09.2026 and agreement-based pay. Main blocker is mandatory ACCA F7 plus deeper local tax/statutory accounting.
2. **Europark — Aparıcı Mühasib — 84 — CORE / Priority A.** Month/year close, reporting, expense control and audit support form a strong senior finance-operations bridge. Exact current listing gives deadline 17.09.2026; compensation unpublished.
3. **Landau Education Group — Xərclərə nəzarət üzrə mütəxəssis — 83 — ADJACENT / Priority B.** Expense monitoring, control, inventory accuracy and variance analysis transfer strongly from reconciliations and month-end controls. Deadline 17.09.2026.
4. **OBA — Əmək haqqı hesablaması üzrə aparıcı mütəxəssis — 82 — ADJACENT / Priority B.** SAP, reconciliation, advanced Excel/Power Query/Pivot, error investigation and testing fit well; direct payroll and SAP HCM experience are meaningful gaps. Deadline 17.09.2026.
5. **Company — Mühasib — 81 — CORE / Priority B.** Bank/invoice accounting, debtor-creditor work, reporting and Excel are relevant; local tax/payroll ownership and undisclosed employer/compensation reduce priority. Deadline 14.09.2026.
6. **OBA — Vergi uçotu üzrə mühasib — 80 — CORE / Priority B.** ERP postings, supplier reconciliations, creditor/debtor analysis and payment/document controls fit; tax-declaration ownership is the main gap. Deadline 17.09.2026.

## Rejected this run
`REJECTED_RUN26.csv` adds:
- **Supertoys — Əmək haqqı üzrə mühasib — REJECTED_COMP.** Published salary 1,200 AZN.
- **Retinalab — Satınalma üzrə kiçik mütəxəssis — REJECTED_COMP.** Published fixed salary 600–800 AZN + KPI bonus.

`VACANCIES.csv` was not changed because no new user-browser confirmation was available. C216–C221 remain `TOOL_SNAPSHOT` pending manual browser verification.

## Browser-confirmed live subset
1. **Xsolla — Finance Coordinator — 86**.
2. **Unibank — Financial Efficiency Lead/Chief Specialist — 79**.
3. **Xsolla — Delivery Manager, Self-Service — 74** — remote/Baku — USD 30k–80k/year published.
4. **Bolt — Operations Manager — 71**.

## Data discipline
- `TOOL_SNAPSHOT` is discovery/current-looking evidence, not a guarantee of current browser availability.
- `USER_BROWSER_LIVE` and `USER_BROWSER_CLOSED` override snapshots.
- Do not move new rows into `VACANCIES.csv` without user-browser confirmation.
- Continue to prefer current employer/careers/ATS evidence, exact URLs, explicit deadlines and legal Azerbaijan access.
- Never add obvious low-compensation or poor-fit roles just to increase the count.

## NEXT ACTION
1. Continue open-ended search; target roughly 6–10 genuinely useful new candidates per run when the market supports it, but do not pad.
2. Before deduplication, read `CANDIDATES.csv` and all additive candidate ledgers through `CANDIDATES_RUN26.csv`; current absolute pool is 220. Also read all rejected ledgers through `REJECTED_RUN26.csv`.
3. Prioritize direct AP/Finance Ops; SAP/S4/MDG/master data; finance systems/ERP; controls/reporting; process automation/RPA; data quality/governance; high-value procurement/vendor/P2P and adjacent operations.
4. Give extra attention to fresh employer/ATS pages and newly indexed roles in finance systems, reporting, AP/AR, bank operations/control, master data/data governance and automation. Prefer exact employer/careers pages when discoverable.
5. Audit old `UNKNOWN` salaries whenever fresh published figures surface; remove materially under-target candidates rather than protecting the count.
6. Formal maintenance when convenient: consolidate additive candidate/rejected ledgers into master CSVs without changing counts or losing history.
7. Preserve browser-verification separation; the user will manually test attractive links later.
8. Continue until an explicit user stop instruction is recorded.
