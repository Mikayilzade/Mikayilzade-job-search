# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #19 — 2026-08-21 around 08:50 AZT**.
- **Candidate pool: 177 total.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- Historical master ledger: `CANDIDATES.csv` (C001–C143).
- Additive ledgers: `CANDIDATES_RUN15.csv` (C144–C150), `CANDIDATES_RUN16.csv` (C151–C157), `CANDIDATES_RUN17.csv` (C159–C165 after correction), `CANDIDATES_RUN18.csv` (C166–C172), and `CANDIDATES_RUN19.csv` (C173–C178). Treat all together as the current 177-candidate source of truth until consolidation.
- Rejected history is in `REJECTED.csv` plus additive `REJECTED_RUN19.csv` for this run's newly confirmed low-compensation items.
- Repository remains the sole persistent source of truth.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue adding high-quality options until the user explicitly stops the process.

## Latest run result
Added **6** new candidates, C173–C178:
1. **Marpro Logistics — AP/AR Controller — 91 — CORE / Priority A.** Direct AP/AR ownership, payment discipline, receivables collection, credit limits and cross-country finance coordination. Current JobSearch deadline: 28.08.2026. Compensation described as competitive/market-based but no amount published.
2. **Tabaterra — Böyük Maliyyə Mütəxəssisi — 89 — ADJACENT / Priority A.** AP/AR, liquidity, budgeting, cost analysis, reporting, internal controls, audit support and ERP workflow automation make this a high-value finance progression. Current deadline: 02.09.2026.
3. **Bank Respublika — Əməliyyatlara Nəzarət / İlkin Nəzarət — 86 — ADJACENT / Priority A.** Transaction compliance, pre/post control, exception/query handling and cross-unit coordination map strongly to reconciliation/control experience. Fresh employer/company vacancy index lists the role on 18.08.2026; exact deadline needs browser confirmation.
4. **Rabitəbank — Corporate Operations Operator — 85 — ADJACENT / Priority A.** Corporate account operations, cash/non-cash transaction entry, SWIFT/AZIPS-related processing, documentation and reporting are strong transferable operational-finance skills. Current deadline: 18.09.2026.
5. **Novex Group — Satınalma üzrə baş mütəxəssis — 82 — ADJACENT / Priority B.** ERP/1C procurement, suppliers, budgets and cost optimization fit P2P/vendor strengths; direct five-year procurement/team-lead ownership remains the main gap. Current deadline: 10.09.2026.
6. **Bank of Baku — Ümumi audit şöbəsinin auditoru — 82 — ADJACENT / Priority B.** Internal controls, audit tests, financial/operational data analysis and risk reporting fit well. Deadline is **21.08.2026**, so manual browser verification is urgent today.

## Rejected this run
`REJECTED_RUN19.csv` preserves six low-compensation/expired leads found during fresh search, including Capital Logistics AP (1,500 AZN), Baku Shipyard Junior Accountant (1,000 AZN), Home Finance (1,200 AZN + bonus), UHY (500–600 AZN net), Groupone (1,000 AZN), and Agro-West Tax Accountant (1,500–1,800 AZN net). These must not be recycled into the active pool without materially improved compensation.

`VACANCIES.csv` was not changed because no new user-browser confirmation was available. All C173–C178 remain `TOOL_SNAPSHOT` pending manual browser verification.

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
1. Continue open-ended search; target roughly 6–10 genuinely useful new candidates per run when the market supports it.
2. Before deduplication, read `CANDIDATES.csv` and all `CANDIDATES_RUN15.csv` through `CANDIDATES_RUN19.csv`; current absolute pool is 177. Also read `REJECTED.csv` and `REJECTED_RUN19.csv`.
3. Prioritize direct AP/Finance Ops; SAP/S4/MDG/master data; finance systems/ERP; controls/reporting; process automation/RPA; data quality/governance; high-value procurement/vendor/P2P and adjacent operations.
4. Expand current employer/ATS searches in Baku and explicitly Azerbaijan-eligible remote markets; record exact access constraints and published compensation where available.
5. Keep auditing old `UNKNOWN` salaries when fresh published figures surface; remove materially under-target candidates rather than protecting the count.
6. Formal maintenance when convenient: consolidate additive candidate/rejected ledgers into master CSVs without changing counts.
7. Preserve browser-verification separation; the user will manually test attractive links later.
8. Continue until an explicit user stop instruction is recorded.
