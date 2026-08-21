# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #15 — 2026-08-21 around 04:55 AZT**.
- **Candidate pool: 150 total.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- Historical master ledger: `CANDIDATES.csv` (C001–C143).
- Latest additive ledger: `CANDIDATES_RUN15.csv` (C144–C150). Treat both files together as the current 150-candidate source of truth until consolidation.
- Repository remains the sole persistent source of truth.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue adding high-quality options until the user explicitly stops the process.

## Latest run result
Added **7** new candidates, C144–C150:
1. **Kontakt Home — Biznes prosesləri üzrə mütəxəssis — 89 — ADJACENT / Priority A.** ERP-process planning, business-process analysis, workflow mapping, automation opportunities, Excel/Visio, procedures, user training and process-performance work align unusually well with the candidate's ERP/process-improvement strengths. Current JobSearch page states deadline 23.08.2026. Main gaps: formal BPM/Lean Six Sigma and implementation-project ownership; salary unpublished.
2. **AzerGold — Daxili nəzarət üzrə aparıcı mütəxəssis — 85 — ADJACENT / Priority A.** Process-control reviews, data collection/analysis, risk identification, recommendations and internal-control assessment map strongly from finance controls, reconciliations and audit support. Exact LinkedIn page remains current-looking; browser confirmation required. Main gap: direct internal-control ownership in mining/operations.
3. **Bir ecosystem — Senior Internal Control Specialist — 84 — ADJACENT / Priority B.** Control testing, evidence review, findings/remediation, data analysis, process governance and payments context fit well; benefits describe competitive compensation plus annual performance bonus. Main gaps: payment/card-processing controls, SQL, formal risk/audit certification and strong English. Exact page is older, so freshness must be browser-checked.
4. **International Company — Payroll Specialist — 82 — CORE / Priority B.** Payroll-related reconciliations, employee-data accuracy, HR/Finance coordination, reporting, audit support, advanced Excel and ERP preference transfer from disciplined finance operations. Current JobSearch page states deadline 27.08.2026 and competitive salary/benefits. Main gap: direct payroll and local payroll-law/tax/social-insurance expertise.
5. **Giltex — Satınalma Meneceri — 79 — ADJACENT / Priority B.** Supplier relationships, procurement strategy, cost optimization, risk reduction and vendor controls are transferable. Current JobSearch index states deadline 29.08.2026. Main gaps: procurement-manager leadership, strategic sourcing and negotiation ownership.
6. **Aral Group Baku — Mühasib — 78 — CORE / Priority B.** Invoices/contracts, debtor tracking, daily cash/accounting operations and monthly reporting fit finance operations, but the 6-day schedule materially reduces lifestyle score; salary is unpublished.
7. **Aceolution — Safety Back Office Executive — 77 — ADJACENT / Priority B.** Documentation, trackers/databases, data verification, discrepancy handling, reports, audit-ready records, SOPs and quality checks transfer from controlled back-office finance work. Main risks: safety domain, contract employment and unpublished pay.

## Exclusions identified in this run
- **Chronos Consulting — Finance Manager:** exact LinkedIn page says no longer accepting applications; do not count.
- **Homebridge Hotel Apartments — Accounting Specialist:** 900 AZN net; materially below target.
- **Baku Shipyard — Junior Accountant:** 1,000 AZN; below target.
- **Baltic Transline Azerbaijan — Debt Collection Manager:** salary starts from 900 AZN net; below target despite transferable AR/collections work.
- **PwC Azerbaijan — Senior Consultant, Deals:** employer application deadline was 17.08.2026; expired.
- **AzerGold — Project Manager:** exact LinkedIn page says no longer accepting applications.
These are recorded here for deduplication; formal REJECTED.csv consolidation remains a maintenance action for a later run.

`VACANCIES.csv` was not changed because no new user-browser confirmation was available. All C144–C150 remain `TOOL_SNAPSHOT` pending manual browser verification.

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
2. **Before deduplication, read both `CANDIDATES.csv` and `CANDIDATES_RUN15.csv`**; current absolute pool is 150.
3. Prioritize direct AP/Finance Ops; SAP/S4/MDG/master data; finance systems/ERP; controls/reporting; process automation/RPA; data quality/governance; high-value procurement/vendor/P2P and adjacent operations.
4. Expand current employer/ATS searches in Baku and explicitly Azerbaijan-eligible remote markets; record exact access constraints.
5. Formal maintenance when convenient: consolidate `CANDIDATES_RUN15.csv` into `CANDIDATES.csv` and move the six run-15 exclusions into `REJECTED.csv`, without changing the absolute counts or rediscovering them.
6. Preserve browser-verification separation; the user will manually test attractive links later.
7. Continue until an explicit user stop instruction is recorded.
