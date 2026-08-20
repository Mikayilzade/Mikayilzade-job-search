# Job Search Status

## Current state
- Phase: SEARCH / CANDIDATE POOL BUILD.
- Last completed run: Autonomous Run #4 — 2026-08-20 around 05:29–05:55 AZT.
- **Candidate pool: 71 / 100.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- `CANDIDATES.csv` is the master 100-target ledger.
- Repository remains the sole persistent source of truth.

## Run result
- Added **7 new scored candidates**; no weak padding.
- Strongest new additions:
  1. **Descon Engineering Limited — Supply Chain Executive — 84** — ADJACENT / Priority B. Strong P2P-to-supply-chain bridge through PO/RFQ, vendor coordination, SAP-MM, documentation, supplier follow-up and SCM reporting. Main gaps are direct MRP/material planning/logistics/sourcing ownership.
  2. **METAK LLC — Satınalma üzrə aparıcı mütəxəssis — 84** — ADJACENT / Priority B. Procurement reporting, ERP order tracking, supplier coordination, documentation and analytics map strongly to existing vendor/P2P strengths; direct tendering/sourcing/manufacturing-material knowledge is the gap. Listing states competitive salary plus annual bonus, but no amount is published.
  3. **Deloitte — Consultant, Software Asset Management — 82** — ADJACENT / Priority B. PO/contracts, entitlement records, data quality, dashboards/KPIs, cost-saving analysis, requirements and implementation support transfer well from vendor/master-data/process work; software licensing and ITAM/SAM domain depth are new.
- Also added:
  - **Azsoftware — Procurement Manager — 82**.
  - **METAK — ERP Specialist — 79**.
  - **Life at Bir — IT Business Analyst — 77**.
  - **Baku Steel — Logistics Specialist / Lead — 75**.
- All seven additions are `TOOL_SNAPSHOT`; browser-confirmed live count remains **4**.
- Added two rejected/history records to avoid rediscovery:
  - Yelo Bank performance-management role — exact indexed detail showed expired deadline 09.08.2026.
  - McKinsey Fellow Business Analyst — structurally mismatched because the listing explicitly targets candidates with less than two years of work experience.
- `VACANCIES.csv` was not changed because there was no new user-browser confirmation.

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
1. Continue from **71 / 100** and aim for roughly **6–10 genuinely useful additions per run**.
2. Prioritize remaining direct/high-score opportunities: AP/P2P/treasury/accounting operations, SAP/ERP/MDG/master data, finance systems, vendor management, procurement operations and controls.
3. Continue deep-searching current-looking Baku employer/job indexes for data quality/governance, reporting/analytics, process improvement, procurement analytics, supply-chain operations and business/process analysis.
4. Continue international/remote search only where Azerbaijan/CIS/worldwide access is explicit or legally defensible.
5. Look for exact employer/ATS links where possible; retain strong `LIST` candidates when a current company vacancy index clearly surfaces the title.
6. Preserve transparent score arithmetic, link quality, source-age note, why-fit and gaps for every addition.
7. Update `CANDIDATES.csv`, `DASHBOARD.md` and this file every run. Do not change `VACANCIES.csv` without user-browser confirmation.
8. Stop expanding at **100 / 100** and move to user shortlist/browser checks, deep role analysis, CV variants and application sequencing.
