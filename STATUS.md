# Job Search Status

## Current state
- Phase: SEARCH / CANDIDATE POOL BUILD.
- Last completed run: Autonomous Run — 2026-08-20 around 01:30–01:45 AZT.
- **Candidate pool: 40 / 100.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- `CANDIDATES.csv` is the master 100-target ledger.
- Repository remains the sole persistent source of truth.

## Run result
- Added **8 new scored candidates**; no weak padding.
- New strongest additions:
  1. **Holcim Azerbaijan — SAP Master Data Expert — 91** — ADJACENT / Priority A. A new LinkedIn job ID/repost surfaced after the previously closed Holcim role. Near-direct overlap with SAP master data, S/4/MDG, data quality, process gap analysis, SOP standardization and Finance/Procurement/Supply Chain streams.
  2. **Deloitte — Consultant, Business Process Solutions — 88** — CORE / Priority A. Direct payables/receivables, payment, bookkeeping and client-accounting overlap; local statutory/tax consulting scope is the main expansion.
  3. **Araz Supermarket — SAP Consultant — 87** — ADJACENT / Priority A. SAP master data, business-process mapping, data governance and MM/FI exposure fit strongly; formal consultant/configuration ownership is the main gap.
- Also added:
  - Sigma Technical Services — Senior Accountant — 85.
  - Weatherford — Senior Accountant — 80.
  - TRIBU Search — Group Financial Controller — 76.
  - Life at Bir — Junior Business Analyst (Financial & Strategic) — 78.
  - Deloitte — Business Analyst, Sustainability — 73.
- Kept all new results as `TOOL_SNAPSHOT`; none was promoted to browser-confirmed live.
- Current search also resurfaced stale/expired roles (for example Rabitabank Middle IT Business Analyst with a July 9 deadline and Bank of Baku MIS roles with July deadlines); these were not added.

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
- A newly surfaced distinct job ID/repost may be retained even when an older role at the same employer was previously closed, but the new row must explicitly note that distinction.

## NEXT ACTION
1. Continue from **40 / 100** and aim for roughly **6–10 genuinely useful additions per run**.
2. Deep-search Baku/current-looking finance operations, SAP/ERP/MDG/master-data, procurement/P2P, controls, shared-services and accounting roles first.
3. Expand current search into business/process analysis, finance systems, project/process coordination, data quality/governance, inventory/supply chain and B2B operations when score remains 70+.
4. Prioritize explicit Azerbaijan/CIS/global remote opportunities, especially SAP functional support, ERP implementation/support, finance systems and data governance.
5. Seek more current employer/ATS or fresh indexed roles rather than repeatedly recycling stale LinkedIn snapshots.
6. Keep score arithmetic, exact/list link quality, source-age note, why-fit and key gaps for every addition.
7. Update `CANDIDATES.csv`, `DASHBOARD.md` and this file every run. Do not change `VACANCIES.csv` without user-browser confirmation.
8. Stop expanding at **100 / 100** and move to user shortlist/browser checks, deep role analysis, CV variants and application sequencing.
