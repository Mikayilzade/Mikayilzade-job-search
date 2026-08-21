# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #37 — 2026-08-22 around 00:41 AZT**.
- Last manual vacancy review: **2026-08-22 — Tabaterra / Target Logistics**.
- **Candidate pool: 270 unique total.**
- **Browser-confirmed live subset: 7.**
- User-facing interface: `DASHBOARD.md`.
- Historical master candidates remain in `CANDIDATES.csv`; additive candidate ledgers continue through `CANDIDATES_RUN37.csv`.
- Rejected history is in `REJECTED.csv` plus additive ledgers through `REJECTED_RUN37.csv`.
- Repository remains the sole persistent source of truth.
- Counter reconciliation: candidate IDs reach `C271`, but historical `C158` is absent, so the true unique count is 270.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue autonomous search and add new high-quality options until the user explicitly stops the process.

## Latest run result
Added **5** new candidates, C267–C271. The strongest discovery is unusually outside finance but economically attractive and highly transferable:
1. **U.S. Embassy Baku — Customer Service Center Representative — C267 — 85 — ADJACENT / Priority A.** Published salary USD 23,573/year. The embedded official vacancy announcement says the open period is 12–26 Aug 2026, so use **26 Aug** as the effective application deadline even though the aggregator shell shows a later date. Service-request routing, SLA/performance monitoring, accurate recordkeeping, issue follow-up and multilingual stakeholder support fit strongly. Non-finance role; background/security clearance applies.
2. **Xalq Bank — Operational Risk Senior/Chief Specialist — C268 — 75 — ADJACENT / Priority B.** Strong overlap in controls, incident/root-cause analysis, reporting and process improvement, but direct operational-risk/ERM and banking-regulatory practice are real gaps. Deadline 28 Aug 2026.
3. **Xalq Bank — Digital Fraud / Operations Monitoring Specialist — C269 — 73 — ADJACENT / Priority C.** Transaction monitoring, exception investigation and payment-process discipline transfer, but bank/anti-fraud experience and shift work are meaningful gaps. Deadline 18 Sep 2026.
4. **Xalq Bank — Budget Planning & Expense Control Specialist/Lead range — C270 — 72 — ADJACENT / Priority C.** Expense control, variance analysis, Excel and optimization overlap, but mandatory banking experience plus budgeting/forecasting/modelling ownership make this a stretch. Deadline 30 Aug 2026.
5. **Xalq Bank — Financial Analysis & Management Reporting Chief Specialist — C271 — 73 — ADJACENT / Priority C.** Dashboard/report automation and cost optimization transfer, but product costing, profitability/ratio analysis and direct finance/risk/treasury-sector experience are broader than the current AP profile. Deadline 12 Sep 2026.

## Manual user-found review — 22 Aug
- **Tabaterra — Aparıcı mühasib — C259 — USER_BROWSER_LIVE — rescored 79 → 74.** User supplied an exact live HRX link. Current role requires minimum 3 years manufacturing accounting, 1C 8.3, Azerbaijan tax/statutory knowledge, production/cost accounting, inventory/fixed assets and tax-return participation. AP/finance-operations controls and reconciliation skills transfer, but the direct manufacturing/local-accounting gap is substantial. Deadline 18 Sep 2026; salary unpublished.
- **Target Logistics — Senior Accountant — rejected (R123).** Current vacancy publishes **2,000 AZN** and office hours **15:00–01:00 Monday-Friday**. This is below the economic target and creates major lifestyle risk. The role also includes budgeting, logistics financial reporting, inventory valuation and cost analysis, so it is not strong enough functionally to justify those conditions.

## Rejected this run / manual review
- **Xalq Bank — Internal Control Monitoring Specialist:** direct business-credit/borrower monitoring experience required.
- **Xalq Bank — Payment Technologies Support Specialist:** deeply technical Java/SQL/API/messaging/Linux role rather than business-side payments.
- **Xalq Bank — Risk Control & Reporting Senior/Chief Specialist:** direct ERM/control-framework/banking-regulation specialization too strong.
- **Target Logistics — Senior Accountant:** 2,000 AZN and 15:00–01:00 office schedule; rejected on compensation/lifestyle before broader budgeting/logistics-accounting gaps.

## Browser-confirmed live subset
1. **Xsolla — Finance Coordinator — 86**.
2. **Unibank — Financial Efficiency Lead/Chief Specialist — 79**.
3. **OBA — Maliyyə üzrə Analtik (Logistika üzrə) — 79**.
4. **Xsolla — Delivery Manager, Self-Service — 74** — remote/Baku — USD 30k–80k/year published.
5. **Tabaterra — Aparıcı mühasib — 74** — user-found exact HRX link; deadline 18 Sep.
6. **OBA — BI & SQL Reporting Specialist (Lead) — 72 practical re-review**.
7. **Bolt — Operations Manager — 71**.

## NEXT ACTION
1. Continue open-ended search; target roughly 6–10 genuinely useful new candidates per run when the market supports it, but keep fewer when quality/economics do not justify more.
2. Prioritize direct AP/Finance Ops, SAP/S4/MDG/master data, finance systems/ERP, treasury/payments/settlements, controls/reporting, process automation/RPA and data quality/governance.
3. Keep searching Glorri/HRX/employer-specific local sources because user-found vacancies proved generic searches can miss relevant roles.
4. Search Azerbaijan-eligible international remote roles and selective Baku international-organization/embassy roles where published compensation and transferable operations skills justify a title change.
5. Search specifically for business-side SAP/ERP roles rather than technical Basis/ABAP/HCM configuration roles.
6. Continue early compensation filtering and do not inflate scores for unpublished local salaries.
7. Dedupe against `CANDIDATES.csv`, all `CANDIDATES_RUN*.csv`, `REJECTED.csv`, and all `REJECTED_RUN*.csv` before every addition.
8. Preserve browser-verification separation; `VACANCIES.csv` changes only on browser-confirmed evidence.
9. Treat strong SQL/BI/FP&A/budgeting/forecasting/ERM requirements as real gaps unless evidence shows equivalent experience. Treat manufacturing accounting, local tax/statutory ownership, cost accounting and 1C as real gaps too.
10. Continue until an explicit user stop instruction is recorded.
