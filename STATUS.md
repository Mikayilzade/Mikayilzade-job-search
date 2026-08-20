# Job Search Status

## Current state
- Phase: SEARCH / CANDIDATE POOL BUILD.
- Last completed run: Autonomous Run #3 — 2026-08-20 around 04:27–04:55 AZT.
- **Candidate pool: 64 / 100.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- `CANDIDATES.csv` is the master 100-target ledger.
- Repository remains the sole persistent source of truth.

## Run result
- Added **8 new scored candidates**; no weak padding.
- Strongest new additions:
  1. **ATB Bank — Procurement Lead/Chief Specialist — 86** — ADJACENT / Priority A. Strong bridge from P2P/vendor/master-data/process control into procurement procedures, supplier coordination and commercial documentation. Company vacancy index is current-looking and shows the role posted 31.07.2026; browser check still required.
  2. **OBA Market — Revenue Lead Accountant — 86** — CORE / Priority A. Strong finance-operations overlap: counterparty reconciliations, contract/bonus checks, debtor aging, system postings, income analysis, document control and month-target tracking. Company listing was crawled very recently and shows a 26.08.2026 deadline; browser check required.
  3. **Yelo Bank — Procurement Contracts & Documentation Specialist — 82** — ADJACENT / Priority B. Supplier lists, contracts, amendments, acts, approvals and contractor coordination map closely to vendor/P2P work; the main risk is junior-title compensation. Current-looking exact listing shows deadline 06.09.2026.
- Also added:
  - **IDDA — Internal Audit Lead Specialist — 81**.
  - **Kapital Bank — Strategy, Budget & Analytics Specialist — 80**.
  - **Bank Respublika — System Analyst / IT Business Analyst — 79**.
  - **VIP Services Group — FP&A Specialist — 79**.
  - **Expressbank — Corporate Client Service Specialist/Lead — 79**.
- All eight new entries are `TOOL_SNAPSHOT`; none was promoted to browser-confirmed live.
- No change to `VACANCIES.csv` because the user has not browser-confirmed any of these new links.

## Browser-confirmed live subset
1. Xsolla — Finance Coordinator — 86.
2. Unibank — Financial Efficiency Lead/Chief Specialist — 79.
3. Xsolla — Delivery Manager, Self-Service — 74 — remote/Baku — USD 30k–80k/year published.
4. Bolt — Operations Manager — 71.

## Data discipline
- Candidate quality matters more than filling the number.
- Prefer score 70+; 65–69 only with a specific strategic reason.
- Local Baku and explicit Azerbaijan remote are preferred.
- Remote without country access evidence must be flagged or excluded.
- Deduplicate before every addition.
- Known closed/404/expired roles never count.
- `TOOL_SNAPSHOT` may count as a candidate but never as browser-confirmed live.
- `USER_BROWSER_LIVE` and `USER_BROWSER_CLOSED` override tool snapshots.
- A newly surfaced distinct job ID/repost may be retained even when an older role at the same employer/title was previously rejected, but the distinction must be documented.

## NEXT ACTION
1. Continue from **64 / 100** and aim for roughly **6–10 genuinely useful additions per run**.
2. Prioritize direct/high-score opportunities first: AP/P2P/treasury/accounting operations, SAP/ERP/MDG/master data, vendor management, procurement operations and finance controls.
3. Deep-search current-looking Baku employer/job indexes for finance systems, business/process analysis, data quality/governance, reporting/analytics, procurement analytics and internal controls.
4. Continue international/remote search only where Azerbaijan/CIS/worldwide access is explicit or legally defensible.
5. Look for exact employer/ATS links where possible, but retain strong `LIST` candidates when the current company vacancy index clearly surfaces the role.
6. Keep full score arithmetic, link quality, source-age note, why-fit and gaps for every addition.
7. Update `CANDIDATES.csv`, `DASHBOARD.md` and this file every run. Do not change `VACANCIES.csv` without user-browser confirmation.
8. Stop expanding at **100 / 100** and move to user shortlist/browser checks, deep role analysis, CV variants and application sequencing.
