# Job Search Status

## Current state
- Phase: SEARCH / CANDIDATE POOL BUILD.
- Last completed run: Autonomous Run #6 — 2026-08-20 around 07:27 AZT.
- **Candidate pool: 85 / 100.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- `CANDIDATES.csv` is the master 100-target ledger.
- Repository remains the sole persistent source of truth.

## Run result
- Added **6 new scored candidates**; no weak padding.
- Strongest new additions:
  1. **Coca-Cola CCI — Supply Chain Planning Specialist — 82** — ADJACENT / Priority B. SAP production-plan maintenance, MRP, purchasing-demand creation, supplier coordination and cross-functional planning create a credible P2P/ERP bridge. Main gap is direct manufacturing planning/MRP experience.
  2. **Four Seasons — Marketing Operations Coordinator — 80** — ADJACENT / Priority B. Unusual title but operational responsibilities fit well: vendor quotations, supplier coordination, contracts, PO/invoice tracking, budget administration, deadlines, approvals and project coordination. Marketing/PR domain is new.
  3. **Aznof — Mühasib — 78** — CORE / Priority B. Supplier/subcontractor reconciliations, purchase/sales entries, inventory movement, expense-plan control and finance reporting fit well, but the 6-day workweek lowers lifestyle score and local 1C/statutory depth is a gap.
- Also added:
  - **Veyseloglu — Biznes Proseslərinin İdarəedilməsi Meneceri — 78** — strong process/SOP/ERP/continuous-improvement transfer, but indexed job IDs conflict on status and formal BPM/project-management depth is a gap.
  - **Techpro DC — Vendor Business Manager — 77** — vendor/stakeholder operations transfer, with likely sales/channel-management gap.
  - **EPAM — Service Delivery Manager — 70** — retained only as a high-upside stretch because SLA/KPI/escalation/process governance transfer, but formal IT service delivery, 24x7 support, ITIL and technical stack gaps are substantial.
- All six are `TOOL_SNAPSHOT`; browser-confirmed live count remains **4**.
- `VACANCIES.csv` was not changed because there was no new user-browser confirmation.
- Fresh search also identified several roles that were intentionally not added: KBR Junior Materials/Procurement is already closed with a June deadline; Holcim Procurement Specialist says no longer accepting applications; an old Veyseloglu BPM job ID says closed, which is why the newer current-looking ID is flagged as status conflict rather than live.

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
- Old readable snapshots with clearly old posting ages are rejected rather than used as padding unless there is distinct evidence of a current repost/new job ID.

## NEXT ACTION
1. Continue from **85 / 100** and aim for roughly **6–10 genuinely useful additions per run**.
2. Prioritize direct/high-score opportunities still underrepresented: AP/P2P/treasury/accounting operations, SAP/ERP/MDG/master data, finance systems, vendor management, procurement analytics/operations and controls.
3. Continue searching current JobSearch/Glorri/employer indexes with explicit August/September 2026 deadlines for Baku finance, procurement, reporting, controls, data quality, process improvement and business/process-analysis roles.
4. Continue international/remote search only where Azerbaijan/CIS/worldwide access is explicit or legally defensible.
5. Prefer exact current employer/job-board URLs with concrete future deadlines when available; use LinkedIn snapshots only as candidate evidence, never proof of live status.
6. Preserve transparent score arithmetic, link quality, source-age note, why-fit and gaps for every addition.
7. Update `CANDIDATES.csv`, `DASHBOARD.md`, `REJECTED.csv` as needed and this file every run. Do not change `VACANCIES.csv` without user-browser confirmation.
8. Stop expanding at **100 / 100** and move to user shortlist/browser checks, deep role analysis, CV variants and application sequencing.
