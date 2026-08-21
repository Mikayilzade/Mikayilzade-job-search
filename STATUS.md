# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #27 — 2026-08-21 around 16:45 AZT**.
- **Candidate pool: 225 total.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- Historical master ledger: `CANDIDATES.csv` (C001–C143).
- Additive ledgers: `CANDIDATES_RUN15.csv` through `CANDIDATES_RUN27.csv`. Treat all together as the current source of truth until consolidation.
- Rejected history is in `REJECTED.csv` plus additive rejected ledgers through `REJECTED_RUN27.csv`.
- Repository remains the sole persistent source of truth.

## Counter note
The highest candidate ID is C226 while the absolute pool is 225 because prior candidate C158 was removed after published compensation proved materially below target. Do not infer pool size from the highest ID alone.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue adding high-quality options until the user explicitly stops the process.

## Latest run result
Added **5** new candidates, C222–C226:
1. **Hydex Logistics — Mühasib — 84 — CORE / Priority A.** Accounting/reporting, bank and cash operations, inventory controls and structured finance work fit strongly. Current Jobsite listing states deadline 21.08.2026, so manual browser verification/application is urgent. Main gaps: direct Azerbaijan tax-return ownership and 1C; salary amount unpublished.
2. **Azerbaijan SuperMarket — Vergilər üzrə mühasib — 83 — ADJACENT / Priority B.** Supplier tax-invoice/payment matching, debtor-creditor reporting, ERP/accounting data extraction, Excel and reconciliations overlap with AP controls. Exact JobSearch listing states deadline 24.08.2026 and employer LinkedIn recently reposted the role. Main gap: direct tax-code/VAT/WHT/statutory reporting ownership.
3. **Heydər Əliyev adına Müasir Təhsil Kompleksi — Mühasib — 83 — CORE / Priority B.** General accounting/reconciliations/reporting and structured finance operations are transferable. Current Jobsite company/category index lists deadline 22.08.2026. Exact current detail link and salary are unresolved; local statutory/1C depth may be required.
4. **PASHA Bank — Mühasibatlıq və Vergi üzrə Baş mütəxəssis — 80 — ADJACENT / Priority B.** Month/year close, ERP, tax-process automation, analytics, Excel and cross-functional finance work make a credible broader-finance transition. Fresh listing published 20.08.2026 with deadline 20.09.2026. High-level Azerbaijan tax law and IAS12/IFRS9 are significant gaps.
5. **Azerbaijan SuperMarket — Senior Financial Reporting Specialist (IFRS) — 78 — ADJACENT / Priority B.** Strong upside through IC reconciliations, ERP, advanced Excel, audit coordination and high-volume reporting. Current role deadline 05.09.2026. Large gap: 5–7+ years direct IFRS reporting/external audit, consolidation and fluent English.

## Rejected this run
`REJECTED_RUN27.csv` adds four clearly under-target roles:
- QEBELE BROYLER — Mühasib — **600–800 AZN**.
- Music House — Mühasib-Operator — **600–1,000 AZN**.
- Master Blend — Mühasib — **from 1,800 AZN**.
- ENEM Consulting Services — Aparıcı mühasib — **800–1,200 AZN**.

`VACANCIES.csv` was not changed because no new user-browser confirmation was available. C222–C226 remain `TOOL_SNAPSHOT` pending manual browser verification.

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
2. Before deduplication, read `CANDIDATES.csv` and all additive candidate ledgers through `CANDIDATES_RUN27.csv`; current absolute pool is 225. Also read all rejected ledgers through `REJECTED_RUN27.csv`.
3. Prioritize direct AP/Finance Ops; SAP/S4/MDG/master data; finance systems/ERP; controls/reporting; process automation/RPA; data quality/governance; high-value procurement/vendor/P2P and adjacent operations.
4. Give extra attention to fresh employer/ATS pages and newly indexed roles in finance systems, reporting, AP/AR, bank operations/control, master data/data governance and automation. Prefer exact employer/careers pages when discoverable.
5. Audit old `UNKNOWN` salaries whenever fresh published figures surface; remove materially under-target candidates rather than protecting the count.
6. Formal maintenance when convenient: consolidate additive candidate/rejected ledgers into master CSVs without changing counts or losing history.
7. Preserve browser-verification separation; the user will manually test attractive links later.
8. Continue until an explicit user stop instruction is recorded.
