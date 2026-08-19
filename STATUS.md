# Job Search Status

## Current state
- Phase: SEARCH / CANDIDATE POOL BUILD.
- Last completed run: Manual overnight Run — 2026-08-20 around 00:38–01:05 AZT.
- **Candidate pool: 32 / 100.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- `CANDIDATES.csv` is now the master 100-target ledger.
- Repository remains the sole persistent source of truth.

## User decision that changes the workflow
The user will manually browser-check attractive links later. The autonomous goal is therefore 100 strong candidate leads, not 100 browser-confirmed live pages. The user may only inspect the first 20–30 if lower-ranked titles are not interesting.

This solves the web-cache limitation without sacrificing autonomous search: `TOOL_SNAPSHOT` candidates can count toward 100 if they are strong and not already known closed, but must never be described as definitely live.

## Manual run result
- Started from 4 browser-confirmed live roles.
- Built a new `CANDIDATES.csv` master pool with **32 scored candidates**.
- Dashboard now separates `Candidate pool 32/100` from `Browser-confirmed live 4`.
- Added strong new directions including:
  - LeverX — SAP Functional Support Consultant — Azerbaijan explicitly eligible remote; especially strong MDG customer/vendor overlap.
  - LeverX — SAP Functional Consultant — Azerbaijan explicitly eligible remote.
  - OBA Market — Senior Finance Controller.
  - Milli Aviasiya Akademiyası — Data Analytics Specialist.
  - Yelo Bank — Data Analyst (Credit Monitoring), Business Data Analyst and Data Governance/Data Steward.
  - IDDA — Data Quality, Data Management and Senior IT Business Analyst roles.
  - Baku Steel — Procurement & Logistics Department Manager.
  - Hikvision — Procurement & Supply Specialist.
  - VTB, Expressbank, Azerbaijan Railways and OBA adjacent operations/data/process roles.
- Preserved previously strong unconfirmed candidates such as Technip, ABB, Avis, CCI, DP World, Azerconnect and Weatherford.
- Known browser-dead jobs (Khazar, INFUSE old coordinator, Xsolla HR Project Coordinator, Fairmont) remain outside the candidate count.

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

## NEXT ACTION
1. Continue from **32 / 100** and aim to add roughly **6–10 genuinely useful new candidates per hourly run** until reaching 100; do not pad with weak links.
2. Deep-search current-looking employer/job indexes in Baku: banks, telecom, oil & gas, engineering, retail/FMCG, logistics, transport, shared services, major local groups and international employers.
3. Deep-search explicit Azerbaijan/CIS/global remote roles, especially SAP/ERP/MDG, finance systems, P2P/AR/O2C, project/process coordination, data quality/governance, procurement operations and business operations.
4. Expand title-agnostically into warehouse/inventory, supply chain, project/program coordination, implementation/onboarding, customer/sales operations and process-quality roles when skill transfer is credible.
5. Require a score breakdown and short why-fit/gaps for every addition.
6. Keep exact links when possible; if only an employer vacancy list is available, mark `link_quality=LIST` so the user knows to search the title on that page.
7. Update `CANDIDATES.csv`, `DASHBOARD.md` and this `STATUS.md` every run. Update `VACANCIES.csv` only after user-browser confirmation; update `REJECTED.csv` when a role is known closed/inaccessible.
8. When candidate pool reaches **100/100**, stop expanding the pool and report completion. Next phase: user shortlist/browser checks, deep requirement-by-requirement analysis, CV variants and application sequencing.
