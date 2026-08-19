# Job Search Status

## Current state
- Phase: SEARCH / CANDIDATE POOL BUILD.
- Last completed run: Autonomous Run #2 — 2026-08-20 around 03:33–03:55 AZT.
- **Candidate pool: 56 / 100.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- `CANDIDATES.csv` is the master 100-target ledger.
- Repository remains the sole persistent source of truth.

## Run result
- Added **8 new scored candidates**; no weak padding.
- Strongest new additions:
  1. **Baker Hughes — AP Accountant — 95** — CORE / Priority A. This is the closest functional match found so far: weekly payments for Azerbaijan/Kazakhstan, payment proposals, vendor/bank queries, internet banking, monthly bank reconciliations, VAT/WHT/customs payments and cash-flow reporting map almost directly to existing AP work. The current LinkedIn result references requisition R165111 and appeared only days old, but it remains `TOOL_SNAPSHOT` until browser-checked.
  2. **Baku Steel — Senior Vendor Management Specialist — 88** — ADJACENT / Priority A. Very strong vendor-governance/P2P/master-data/process-control transfer; company vacancy index was crawled last week and shows the role posted 05.08.2026.
  3. **Group of Companies at Baku City Residences — CRM Business Analyst / CRM Administrator — 84** — ADJACENT / Priority B. Strong systems/process bridge through requirements gathering, vendor coordination, workflow improvement, data accuracy, KPI dashboards, documentation and user training.
- Also added:
  - **PASHA Bank — Financial Control Specialist — 84**.
  - **Unibank — Internal Control Reporting Lead Specialist — 83**.
  - **Xalq Bank — Budget Planning & Cost Control Specialist/Lead — 80**.
  - **Xalq Bank — Operational Risk Senior/Chief Specialist — 80**.
  - **Wolt — Account Management Lead, Azerbaijan — 72** — stretch based on KPI/partner operations and commercial upside.
- All eight new entries are `TOOL_SNAPSHOT`; none was promoted to browser-confirmed live.
- Current searches also surfaced stale/expired pages (for example older Bank of Baku and AzerGold records); those were not added.

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
1. Continue from **56 / 100** and aim for roughly **6–10 genuinely useful additions per run**.
2. Prioritize direct/high-score opportunities first: AP/P2P/treasury/accounting operations, SAP/ERP/MDG/master data, vendor management and finance controls.
3. Deep-search current-looking Baku employer/job indexes for finance systems, business/process analysis, data quality/governance, procurement analytics and internal controls.
4. Continue international/remote search only where Azerbaijan/CIS/worldwide access is explicit or legally defensible.
5. Look for exact employer/ATS links where possible, but retain strong `LIST` candidates when the current company vacancy index clearly surfaces the role.
6. Keep full score arithmetic, link quality, source-age note, why-fit and gaps for every addition.
7. Update `CANDIDATES.csv`, `DASHBOARD.md` and this file every run. Do not change `VACANCIES.csv` without user-browser confirmation.
8. Stop expanding at **100 / 100** and move to user shortlist/browser checks, deep role analysis, CV variants and application sequencing.
