# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #18 — 2026-08-21 around 07:40 AZT**.
- **Candidate pool: 171 total.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- Historical master ledger: `CANDIDATES.csv` (C001–C143).
- Additive ledgers: `CANDIDATES_RUN15.csv` (C144–C150), `CANDIDATES_RUN16.csv` (C151–C157), `CANDIDATES_RUN17.csv` (C159–C165 after correction), and `CANDIDATES_RUN18.csv` (C166–C172). Treat all together as the current 171-candidate source of truth until consolidation.
- Repository remains the sole persistent source of truth.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue adding high-quality options until the user explicitly stops the process.

## Data correction this run
- Removed **C158 IRES — Receivables Accountant** from the active candidate pool because fresh exact-source evidence confirms **1,500–1,800 AZN net**, materially below the 2,500 AZN net target. The role remains preserved as `R045` in `REJECTED.csv`. This corrects the prior run's salary-unknown classification.

## Latest run result
Added **7** new candidates, C166–C172. Net pool change is **+6** because of the C158 correction.
1. **Landau Education Group — Aparıcı Mühasib — 88 — CORE / Priority A.** Customer-payment postings, bank-payment monitoring, debtor tracking/analysis, Excel and cross-functional finance work fit strongly. Current JobSearch deadline: 10.09.2026.
2. **Xalq Bank — Bank Fəaliyyətinə Dəstək / Bank sistemlərinin fəaliyyətinə dəstək — 86 — ADJACENT / Priority A.** Requirements, As-Is/To-Be mapping, testing, automated-process monitoring, issue investigation, user support and vendor coordination create a strong ERP/process-support bridge. Current careers page still lists the role; current banking index gives deadline 10.09.2026.
3. **Xalq Bank — Daxili Nəzarət / Əməliyyatların icrasına nəzarət — 85 — ADJACENT / Priority A.** Operational checks, periodic reporting, registers, Excel and control discipline align closely with reconciliations/audit-support experience. Current employer careers page lists the role; exact current deadline needs browser confirmation.
4. **Baku Electronics — Marketinq layihələrinin idarə edilməsi üzrə mütəxəssis — 82 — ADJACENT / Priority B.** Official employer page lists the role through 15.09.2026. Scope/budget/schedule, vendor coordination, risks, issues and management reporting transfer well from process ownership.
5. **Push30 — Lead Financial Analyst — 81 — ADJACENT / Priority B.** Strong bridge into FP&A/reporting, but mandatory ACCA FA/FR/FM or CFA Level 1 is a serious gap. Current deadline 07.09.2026.
6. **Trilogy — Finance Operations Manager — 75 — STRETCH / Priority C.** Worldwide fully remote and published **USD 100,000/year**; invoices/payments/reconciliations/process quality are highly relevant, but professional certification, Big4 audits, people-management and US-hours requirements make interview probability low.
7. **Klaxon Ltd — Marketinq və əməliyyatlar üzrə koordinator — 75 — ADJACENT / Priority B.** Supplier/customer/internal coordination and task tracking transfer well, but marketing scope and a six-day schedule reduce attractiveness. Current deadline 11.09.2026.

`VACANCIES.csv` was not changed because no new user-browser confirmation was available. All C166–C172 remain `TOOL_SNAPSHOT` pending manual browser verification.

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
2. Before deduplication, read `CANDIDATES.csv`, `CANDIDATES_RUN15.csv`, `CANDIDATES_RUN16.csv`, `CANDIDATES_RUN17.csv`, and `CANDIDATES_RUN18.csv`; current absolute pool is 171.
3. Prioritize direct AP/Finance Ops; SAP/S4/MDG/master data; finance systems/ERP; controls/reporting; process automation/RPA; data quality/governance; high-value procurement/vendor/P2P and adjacent operations.
4. Expand employer/ATS searches in Baku and explicitly Azerbaijan-eligible remote markets; record exact access constraints and published compensation where available.
5. Keep auditing old `UNKNOWN` salaries when fresh published figures surface; remove materially under-target candidates rather than protecting the count.
6. Formal maintenance when convenient: consolidate additive candidate ledgers into `CANDIDATES.csv` without changing counts.
7. Preserve browser-verification separation; the user will manually test attractive links later.
8. Continue until an explicit user stop instruction is recorded.
