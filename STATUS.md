# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #16 — 2026-08-21 around 05:45 AZT**.
- **Candidate pool: 157 total.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- Historical master ledger: `CANDIDATES.csv` (C001–C143).
- Additive ledgers: `CANDIDATES_RUN15.csv` (C144–C150) and `CANDIDATES_RUN16.csv` (C151–C157). Treat all three together as the current 157-candidate source of truth until consolidation.
- Repository remains the sole persistent source of truth.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue adding high-quality options until the user explicitly stops the process.

## Latest run result
Added **7** new candidates, C151–C157:
1. **OBA Market — Xərclər üzrə mühasib — 89 — CORE / Priority A.** Expense allocation/accounting, document checks, current-account reconciliations, payment routing, contract/bonus matching and expense analysis are unusually close to AP/reconciliation/process-control strengths. OBA's current Glorri company index, crawled two days ago, lists a fresh 04.08.2026 repost. Exact current detail URL and salary remain unresolved, so this is `TOOL_SNAPSHOT`.
2. **OBA Market — Maddi Vəsaitlər üzrə Mühasib — 86 — CORE / Priority A.** Inventory/material-asset accounting, purchase-document controls, debtor/creditor reconciliations, payment planning, logistics-cost reporting and ERP discipline fit finance operations well. Current OBA Glorri index lists the role dated 03.08.2026; exact detail page still needs browser verification.
3. **OBA Market — Əmək haqqı hesablaması üzrə aparıcı mütəxəssis — 84 — ADJACENT / Priority B.** SAP payroll cycle, data validation, final settlements and payment execution transfer from controlled finance operations. Current sources show deadline 11.09.2026. Main gap: direct payroll plus Azerbaijan labor/tax/social-insurance calculations.
4. **ABB-İnvest — Əməliyyat Riskləri üzrə Aparıcı Mütəxəssis — 84 — ADJACENT / Priority B.** Process-risk gaps, incident/root-cause tracking, corrective actions, RCSA/KRI monitoring and third-party process risk map strongly to controls/audit/process-improvement skills. Current JobSearch/SmartJob copies are fresh August listings; JobSearch shows deadline 14.09.2026.
5. **U.S. Embassy Baku — Customer Service Center Representative — 83 — ADJACENT / Priority B.** Service-request tracking, standards/SLA monitoring, record keeping, issue routing and cross-unit coordination fit structured operations. Published salary is **USD 23,573/year** and the vacancy is open to all interested applicants; announcement text gives open period **12–26 Aug 2026**. Main gap is the non-finance/customer-service orientation and the requirement for Good Working Knowledge in English, Azerbaijani and Russian.
6. **Aqrar Tədarük və Təchizat — Satınalma üzrə mütəxəssis / aparıcı / baş mütəxəssis — 83 — ADJACENT / Priority B.** Procurement documentation, supplier/market research, annual purchasing planning, contracts and cross-functional coordination fit P2P/vendor strengths. Fresh August sources confirm the role; direct public-procurement law and 3+ years procurement ownership are the main gaps. Deadline differs across current copies, so browser verification is important.
7. **Falcon Finance — Audit — 78 — ADJACENT / Priority B.** Financial-resource planning review, operational/process controls, evidence checking, risk identification and reporting transfer from finance controls and audit support. Current JobSearch page shows deadline 13.09.2026. Direct BOKT audit ownership is the main gap.

`VACANCIES.csv` was not changed because no new user-browser confirmation was available. All C151–C157 remain `TOOL_SNAPSHOT` pending manual browser verification.

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
2. Before deduplication, read `CANDIDATES.csv`, `CANDIDATES_RUN15.csv`, and `CANDIDATES_RUN16.csv`; current absolute pool is 157.
3. Prioritize direct AP/Finance Ops; SAP/S4/MDG/master data; finance systems/ERP; controls/reporting; process automation/RPA; data quality/governance; high-value procurement/vendor/P2P and adjacent operations.
4. Expand employer/ATS searches in Baku and explicitly Azerbaijan-eligible remote markets; record exact access constraints and published compensation where available.
5. Formal maintenance when convenient: consolidate additive candidate ledgers into `CANDIDATES.csv` and run-15 exclusions into `REJECTED.csv` without changing counts.
6. Preserve browser-verification separation; the user will manually test attractive links later.
7. Continue until an explicit user stop instruction is recorded.
