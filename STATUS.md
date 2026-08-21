# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #17 — 2026-08-21 around 06:40 AZT**.
- **Candidate pool: 165 total.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- Historical master ledger: `CANDIDATES.csv` (C001–C143).
- Additive ledgers: `CANDIDATES_RUN15.csv` (C144–C150), `CANDIDATES_RUN16.csv` (C151–C157), and `CANDIDATES_RUN17.csv` (C158–C165). Treat all four together as the current 165-candidate source of truth until consolidation.
- Repository remains the sole persistent source of truth.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue adding high-quality options until the user explicitly stops the process.

## Latest run result
Added **8** new candidates, C158–C165:
1. **IRES — Receivables Accountant — 90 — CORE / Priority A.** Customer-payment monitoring, overdue follow-up, account reconciliations and payment-issue resolution are almost directly transferable from AP/reconciliation work. Current JobSearch snapshot shows deadline 14.09.2026.
2. **Prodata — ERP üzrə mütəxəssis — 88 — ADJACENT / Priority A.** ERP/business-process understanding, issue triage, user support, module testing and process optimization create a strong S4/MDG-to-ERP-support bridge. Current HRIN listing runs through 31.08.2026.
3. **Baku Electronics — ERP üzrə mütəxəssis — 88 — ADJACENT / Priority A.** Current employer careers page lists a fresh ERP role with deadline 18.09.2026. Prior employer detail for the same role family shows user/role administration, module testing, process integration, documentation, SQL and Power BI. Current exact detail page still needs manual browser verification.
4. **Baku Electronics — Planlama və satınalma üzrə mütəxəssis / aparıcı mütəxəssis — 87 — ADJACENT / Priority A.** Supplier research, POs, delivery tracking, invoice checks and purchasing plans fit P2P/vendor strengths strongly. Current employer careers index and current third-party copies show deadline 27.08.2026.
5. **Novas Group — Audit üzrə mütəxəssis — 84 — ADJACENT / Priority B.** Financial/operational controls, ERP, Excel, risk-based review and audit reporting transfer credibly from controls/audit-support experience. Current listing shows deadline 07.09.2026.
6. **Baku Electronics — Daxili audit üzrə kiçik mütəxəssis — 82 — ADJACENT / Priority B.** ERP-versus-physical reconciliation, discrepancy investigation, documentation and recommendation follow-up fit well, but junior-title compensation risk remains. Official employer page shows deadline 06.09.2026.
7. **Bank of Baku — Analitik və təqibə dəstək bölməsinin eksperti — 80 — ADJACENT / Priority B.** Fresh official employer vacancy dated 20.08.2026; data extraction/structuring, operational KPI monitoring and reporting fit well. High SQL is the main gap. Deadline 03.09.2026.
8. **Bank of Baku — Qeyri-kredit məhsulları şöbəsinin aparıcı eksperti — 78 — ADJACENT / Priority B.** Official employer page lists current role through 31.08.2026. Product/customer analysis and recurring reporting transfer, while card-product experience plus Power BI/SQL are substantial gaps.

`VACANCIES.csv` was not changed because no new user-browser confirmation was available. All C158–C165 remain `TOOL_SNAPSHOT` pending manual browser verification.

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
2. Before deduplication, read `CANDIDATES.csv`, `CANDIDATES_RUN15.csv`, `CANDIDATES_RUN16.csv`, and `CANDIDATES_RUN17.csv`; current absolute pool is 165.
3. Prioritize direct AP/Finance Ops; SAP/S4/MDG/master data; finance systems/ERP; controls/reporting; process automation/RPA; data quality/governance; high-value procurement/vendor/P2P and adjacent operations.
4. Expand employer/ATS searches in Baku and explicitly Azerbaijan-eligible remote markets; record exact access constraints and published compensation where available.
5. Formal maintenance when convenient: consolidate additive candidate ledgers into `CANDIDATES.csv` without changing counts.
6. Preserve browser-verification separation; the user will manually test attractive links later.
7. Continue until an explicit user stop instruction is recorded.
