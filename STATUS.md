# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #22 — 2026-08-21 around 11:40 AZT**.
- **Candidate pool: 198 total.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- Historical master ledger: `CANDIDATES.csv` (C001–C143).
- Additive ledgers: `CANDIDATES_RUN15.csv` (C144–C150), `CANDIDATES_RUN16.csv` (C151–C157), `CANDIDATES_RUN17.csv` (C159–C165 after correction), `CANDIDATES_RUN18.csv` (C166–C172), `CANDIDATES_RUN19.csv` (C173–C178), `CANDIDATES_RUN20.csv` (C179–C185), `CANDIDATES_RUN21.csv` (C186–C192), and `CANDIDATES_RUN22.csv` (C193–C199). Treat all together as the current 198-candidate source of truth until consolidation.
- Rejected history is in `REJECTED.csv`, `REJECTED_RUN19.csv`, `REJECTED_RUN20.csv`, `REJECTED_RUN21.csv`, and `REJECTED_RUN22.csv`.
- Repository remains the sole persistent source of truth.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue adding high-quality options until the user explicitly stops the process.

## Latest run result
Added **7** new candidates, C193–C199:
1. **Maliyyə Nazirliyi – Rəqəmsal Maliyyə Mərkəzi — Məlumatların idarə edilməsi (Data Governance) üzrə mütəxəssis — 85 — ADJACENT / Priority A.** A very strong bridge from S4/MDG/vendor-master/data-quality controls into enterprise data governance. Current employer-source aggregation lists the role as newly active. Main gaps: formal governance frameworks, metadata/catalog tooling and enterprise policy ownership.
2. **Avrora — Mühasib — 82 — CORE / Priority B.** Debtor/creditor, inventory and balance-account analysis, budget-vs-actual, ERP and Excel match finance-operations/reconciliation strengths. Current listing deadline 10.09.2026. ACCA FA is explicitly mandatory and salary is unpublished.
3. **Xalq Bank — Maliyyə təhlili və idarəedici hesabatlılıq şöbəsinin baş mütəxəssisi — 82 — ADJACENT / Priority B.** Reporting automation, dashboards, financial trends/ratios, cost/profitability analysis and management reporting provide good upside. Current exact JobSearch requisition deadline 12.09.2026 and Xalq Bank careers still lists the role. Main gap: direct management reporting/product-costing depth.
4. **Blackwell — Procurement Specialist — 81 — ADJACENT / Priority B.** Supplier sourcing/qualification, cost-effective procurement and vendor relationships fit the P2P/vendor transition. Current JobSearch deadline 24.08.2026. Direct oil-and-gas/industrial sourcing and negotiation ownership are broader.
5. **Maliyyə Nazirliyi – Rəqəmsal Maliyyə Mərkəzi — IT Biznes analitik — 80 — ADJACENT / Priority B.** Requirements, process analysis, documentation, testing and finance-domain context map well from ERP/process-improvement work. Formal BA/SDLC/BPMN/API/SQL exposure remains the main gap.
6. **Bank Respublika — Bakı və Regionlar üzrə Portfel keyfiyyətinə nəzarət mütəxəssisi — 78 — ADJACENT / Priority B.** Payment-discipline monitoring, overdue follow-up, Excel and exception handling transfer from aged-items and reconciliation work. Deadline 18.09.2026. Collections/credit-portfolio ownership and regional travel are notable differences.
7. **Maliyyə Nazirliyi – Rəqəmsal Maliyyə Mərkəzi — Baş Data Analitik — 75 — STRETCH / Priority C.** Large-data analysis, KPI dashboards, data quality and management reporting are attractive upside areas, but the role expects strong SQL/BI/data-modeling and roughly five years direct analytics experience.

## Rejected this run
`REJECTED_RUN22.csv` adds:
- **Coca-Cola CCI — Commercial and Channel Finance Executive — CLOSED.** Exact LinkedIn page states no longer accepting applications.

`VACANCIES.csv` was not changed because no new user-browser confirmation was available. All C193–C199 remain `TOOL_SNAPSHOT` pending manual browser verification.

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
2. Before deduplication, read `CANDIDATES.csv` and all additive candidate ledgers through `CANDIDATES_RUN22.csv`; current absolute pool is 198. Also read all rejected ledgers through `REJECTED_RUN22.csv`.
3. Prioritize direct AP/Finance Ops; SAP/S4/MDG/master data; finance systems/ERP; controls/reporting; process automation/RPA; data quality/governance; high-value procurement/vendor/P2P and adjacent operations.
4. Give extra attention to current employer/ATS pages and newly posted Ministry/RMM, bank systems, ERP/data-governance and finance-automation roles; record exact access constraints and published compensation where available.
5. Keep auditing old `UNKNOWN` salaries when fresh published figures surface; remove materially under-target candidates rather than protecting the count.
6. Formal maintenance when convenient: consolidate additive candidate/rejected ledgers into master CSVs without changing counts.
7. Preserve browser-verification separation; the user will manually test attractive links later.
8. Continue until an explicit user stop instruction is recorded.
