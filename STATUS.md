# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #28 — 2026-08-21 around 17:50 AZT**.
- **Candidate pool: 232 total.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- Historical master ledger: `CANDIDATES.csv` (C001–C143).
- Additive candidate ledgers: `CANDIDATES_RUN15.csv` through `CANDIDATES_RUN28.csv`. Treat all together as the current source of truth until consolidation.
- Rejected history is in `REJECTED.csv` plus additive rejected ledgers through `REJECTED_RUN28.csv`.
- Repository remains the sole persistent source of truth.

## Counter note
The highest candidate ID is C233 while the absolute pool is 232 because prior candidate C158 was removed after published compensation proved materially below target. Do not infer pool size from the highest ID alone.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue adding high-quality options until the user explicitly stops the process.

## Latest run result
Added **7** new candidates, C227–C233:
1. **Avant Group — Daxili nəzarət üzrə mütəxəssis — 89 — ADJACENT / Priority A.** PO/contract/budget compliance, tender controls, procurement-price analysis, payroll-to-bank/accounting reconciliation, 1C counterparty checks, Excel and discrepancy investigation are unusually close to finance-control/P2P strengths. Current jobU page states deadline 31.08.2026. Main gap: direct internal-control title experience and stronger 1C depth.
2. **SOCAR Tech — Data Governance Specialist — 88 — ADJACENT / Priority A.** Data quality, governance standards, workflows, stewardship, process design/improvement and cross-functional implementation map very strongly to S/4HANA MDG/vendor-master/data-quality experience. Current exact JobSearch/HRX evidence states deadline 28.08.2026. Main gaps: formal data-governance tooling, metadata/lineage and professional English.
3. **Facility Management Group — Satınalma üzrə mütəxəssis — 85 — ADJACENT / Priority A.** Supplier evaluation, PO monitoring, RFQ/tender participation, price analysis, contracts and reporting create a strong P2P/vendor bridge. Fresh company/job pages show a new August requisition with deadline around 09–10.09.2026. Direct sourcing/negotiation ownership is the main gap.
4. **Azerbaijan International Mining Company — Procurement Specialist (Baku) — 85 — ADJACENT / Priority A.** Purchase requests, sourcing, POs, quotation/commercial-term comparison, forecasting and coordination with warehouse/logistics/production fit P2P/vendor/ERP strengths. Current SmartJob/HRX company pages list the Baku role active. Direct procurement and mining-material context are the main gaps.
5. **Fregat LLC — Procurement Specialist — 84 — ADJACENT / Priority B.** RFQ/bid comparison, payment terms, POs, delivery discrepancies, supplier records/audits, cost/KPI reporting and finance/warehouse coordination fit strongly. Current listing is active and salary is interview-based.
6. **Veysəloğlu-Rossmann — Tədarükçü sifarişləri üzrə aparıcı mütəxəssis — 83 — ADJACENT / Priority B.** Supplier-order management, PO processing, delivery follow-up, ERP/documentation, reporting and supply-chain optimization are transferable. Current JobSearch page states deadline 23.08.2026. Main gaps: direct supply-chain tenure and fluent English.
7. **Sabah Capital Partners — Leading / Senior FP&A Specialist — 82 — ADJACENT / Priority B.** Budget control, variance analysis, cash-flow monitoring, management reporting, data validation and Excel offer useful finance-upside. Current August listing is active-looking; direct FP&A/modeling, 1C and English are the main gaps.

## Rejected this run
`REJECTED_RUN28.csv` records:
- Leads Group Supply — Tender üzrə aparıcı mütəxəssis — **1,200–1,600 AZN**.
- Textile Horizon — procurement/logistics lead — employer page deadline **07.08.2026** overrides later aggregator dates.
- Homebridge Hotel Apartments — Accounting Specialist — **900 AZN net**.
- P&O Maritime Logistics — Treasury Accountant — exact detailed page deadline **31.05.2026**, despite fresh roundup resurfacing.

`VACANCIES.csv` was not changed because no new user-browser confirmation was available. C227–C233 remain `TOOL_SNAPSHOT` pending manual browser verification.

## Browser-confirmed live subset
1. **Xsolla — Finance Coordinator — 86**.
2. **Unibank — Financial Efficiency Lead/Chief Specialist — 79**.
3. **Xsolla — Delivery Manager, Self-Service — 74** — remote/Baku — USD 30k–80k/year published.
4. **Bolt — Operations Manager — 71**.

## Data discipline
- `TOOL_SNAPSHOT` is discovery/current-looking evidence, not a guarantee of current browser availability.
- `USER_BROWSER_LIVE` and `USER_BROWSER_CLOSED` override snapshots.
- Do not move new rows into `VACANCIES.csv` without user-browser confirmation.
- Prefer employer/careers/ATS evidence and resolve deadline conflicts in favor of employer-controlled sources.
- Never add obvious low-compensation or poor-fit roles just to increase the count.

## NEXT ACTION
1. Continue open-ended search; target roughly 6–10 genuinely useful new candidates per run when the market supports it, but do not pad.
2. Before deduplication, read `CANDIDATES.csv` plus additive candidate ledgers through `CANDIDATES_RUN28.csv`; current absolute pool is 232. Read rejected history through `REJECTED_RUN28.csv`.
3. Prioritize direct AP/Finance Ops; SAP/S4/MDG/master data; finance systems/ERP; controls/reporting; process automation/RPA; data quality/governance; high-value procurement/vendor/P2P and adjacent operations.
4. Expand fresh employer/ATS searches and explicitly Azerbaijan-eligible remote/global roles; record exact access constraints.
5. Audit old `UNKNOWN` salaries whenever fresh published figures surface; remove materially under-target candidates rather than protecting the count.
6. Formal maintenance when convenient: consolidate additive ledgers into master CSVs without changing counts or losing history.
7. Preserve browser-verification separation; the user will manually test attractive links later.
8. Continue until an explicit user stop instruction is recorded.
