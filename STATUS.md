# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #20 — 2026-08-21 around 09:35 AZT**.
- **Candidate pool: 184 total.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- Historical master ledger: `CANDIDATES.csv` (C001–C143).
- Additive ledgers: `CANDIDATES_RUN15.csv` (C144–C150), `CANDIDATES_RUN16.csv` (C151–C157), `CANDIDATES_RUN17.csv` (C159–C165 after correction), `CANDIDATES_RUN18.csv` (C166–C172), `CANDIDATES_RUN19.csv` (C173–C178), and `CANDIDATES_RUN20.csv` (C179–C185). Treat all together as the current 184-candidate source of truth until consolidation.
- Rejected history is in `REJECTED.csv`, `REJECTED_RUN19.csv`, and `REJECTED_RUN20.csv`.
- Repository remains the sole persistent source of truth.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue adding high-quality options until the user explicitly stops the process.

## Latest run result
Added **7** new candidates, C179–C185:
1. **ATB Bank — Biznesin proseslərinin idarə edilməsi şöbəsinin aparıcı mütəxəssisi — 88 — ADJACENT / Priority A.** AS-IS/TO-BE mapping, process gaps, automation/digitalization and procedure design fit ERP/process-improvement strengths unusually well. Deadline: 17.09.2026.
2. **Veysəloğlu Şirkətlər Qrupu — Büdcə və mühasibat uçotu üzrə Aparıcı Mütəxəssis — 86 — ADJACENT / Priority A.** Budget/reporting, accounting data, variance analysis, controls and Excel form a strong progression from finance operations. Deadline: 17.09.2026.
3. **Mars Overseas Baku — Satınalma üzrə baş mütəxəssis — 83 — ADJACENT / Priority B.** Supplier coordination, tenders, contracts, reporting and cost control align with P2P/vendor experience. Deadline: 12.09.2026.
4. **ATB Bank — Layihələrin idarə edilməsi şöbəsinin aparıcı mütəxəssisi — 81 — ADJACENT / Priority B.** Project schedules, budgets, KPI/status reporting, risk escalation and stakeholder coordination transfer well. Deadline: 17.09.2026.
5. **Xalq Bank — Rəqəmsal dələduzluqla mübarizə / qaydaların idarə olunması — 77 — ADJACENT / Priority B.** Rule-based controls, transaction analysis and root-cause work are transferable; SQL/anti-fraud systems are major gaps. Deadline: 12.09.2026.
6. **ATB Bank — Korporativ strategiya və planlaşdırma şöbəsinin baş mütəxəssisi — 76 — STRETCH / Priority C.** High-upside finance/strategy bridge with meaningful modeling/forecasting gaps. Deadline: 17.09.2026.
7. **Unibank — Kredit Riskləri Ehtiyatlanması və Analitikası üzrə Mütəxəssis — 75 — STRETCH / Priority C.** Data/reporting/control transfer is plausible, but IFRS 9 and credit-risk modeling are major gaps. Deadline: 18.09.2026.

## Rejected this run
`REJECTED_RUN20.csv` adds **Ferrum Capital — Problemli kreditlər üzrə mütəxəssis** with published salary **700 AZN**, far below target.

`VACANCIES.csv` was not changed because no new user-browser confirmation was available. All C179–C185 remain `TOOL_SNAPSHOT` pending manual browser verification.

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
2. Before deduplication, read `CANDIDATES.csv` and all additive candidate ledgers through `CANDIDATES_RUN20.csv`; current absolute pool is 184. Also read all rejected ledgers.
3. Prioritize direct AP/Finance Ops; SAP/S4/MDG/master data; finance systems/ERP; controls/reporting; process automation/RPA; data quality/governance; high-value procurement/vendor/P2P and adjacent operations.
4. Expand current employer/ATS searches in Baku and explicitly Azerbaijan-eligible remote markets; record exact access constraints and published compensation where available.
5. Keep auditing old `UNKNOWN` salaries when fresh published figures surface; remove materially under-target candidates rather than protecting the count.
6. Formal maintenance when convenient: consolidate additive candidate/rejected ledgers into master CSVs without changing counts.
7. Preserve browser-verification separation; the user will manually test attractive links later.
8. Continue until an explicit user stop instruction is recorded.
