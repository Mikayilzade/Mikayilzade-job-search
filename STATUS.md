# Job Search Status

## Current state
- Phase: SEARCH / CANDIDATE POOL BUILD.
- Last completed run: Autonomous Run #5 — 2026-08-20 around 06:31–06:55 AZT.
- **Candidate pool: 79 / 100.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- `CANDIDATES.csv` is the master 100-target ledger.
- Repository remains the sole persistent source of truth.

## Run result
- Added **8 new scored candidates**; no weak padding.
- Strongest new additions:
  1. **MUK — Financial Manager — 90** — CORE / Priority A. Treasury, payment calendar, supplier invoices, currency payments, cash-flow planning/reporting, budgeting, reconciliations, audits, large-data Excel and AR control map unusually closely to current finance-operations experience. Main gaps are 1C8/Navision depth and direct financial-manager/forecast ownership; browser freshness and salary remain unknown.
  2. **Starcom — Accountant — 88** — CORE / Priority A. Exact JobSearch posting shows deadline 07.09.2026. Invoices/e-invoices, reconciliations, bank payments, month-end, reporting, audit support, budget-vs-actual analysis and process improvement are highly transferable. Local tax/accrual/journal depth is the main gap; salary is negotiable but unpublished.
  3. **Makfit — Accountant — 87** — CORE / Priority A. Current-looking indexed role with AP/AR, reconciliations, financial reporting, budgeting, accounting systems and process streamlining. Broader statutory/accounting ownership and salary are the main unknowns.
- Also added:
  - **Marriott International — Accounts Receivable — 85**.
  - **Ram Holding — Satınalma üzrə baş mütəxəssis — 85** — exact JobSearch deadline 06.09.2026.
  - **Veyseloglu — Analitika və Hesabatvermə üzrə Mütəxəssis — 81**.
  - **MER Group — Mühasib — 79** — stated deadline 06.09.2026.
  - **GEN PHARMA — Product Planning Specialist — 78**.
- All eight additions are `TOOL_SNAPSHOT`; browser-confirmed live count remains **4**.
- `VACANCIES.csv` was not changed because there was no new user-browser confirmation.
- Added rejected/history records to prevent stale rediscovery:
  - AzerGold finance/corporate-systems-data sector head — official careers deadline 07.08.2026, expired.
  - STP Procurement Specialist — exact snapshot labelled one year old; not counted.
  - Caspian Innovation Center Financial Data Analyst — exact snapshot labelled two years old; not counted.

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
1. Continue from **79 / 100** and aim for roughly **6–10 genuinely useful additions per run**.
2. Prioritize direct/high-score opportunities still underrepresented: AP/P2P/treasury/accounting operations, SAP/ERP/MDG/master data, finance systems, vendor management, procurement analytics/operations and controls.
3. Continue searching current JobSearch/Glorri/employer indexes with explicit August/September 2026 deadlines for Baku finance, procurement, reporting, controls, data quality, process improvement and business/process-analysis roles.
4. Continue international/remote search only where Azerbaijan/CIS/worldwide access is explicit or legally defensible.
5. Prefer exact current employer/job-board URLs with concrete future deadlines when available; use LinkedIn snapshots only as candidate evidence, never proof of live status.
6. Preserve transparent score arithmetic, link quality, source-age note, why-fit and gaps for every addition.
7. Update `CANDIDATES.csv`, `DASHBOARD.md`, `REJECTED.csv` as needed and this file every run. Do not change `VACANCIES.csv` without user-browser confirmation.
8. Stop expanding at **100 / 100** and move to user shortlist/browser checks, deep role analysis, CV variants and application sequencing.
