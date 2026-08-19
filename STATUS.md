# Job Search Status

## Current state
- Phase: SEARCH / QUALIFICATION under strict freshness rule.
- Last completed run: Manual Interface + Freshness Audit Run — 2026-08-19 23:35 AZT.
- **Strictly qualified live opportunities: 7 / 100.**
- Strong watch/unverified leads remain preserved in `REJECTED.csv` and `DASHBOARD.md` but do not count.
- User-facing interface: **`DASHBOARD.md`**.
- Repository remains the sole source of truth.

## What changed in this run
- Added transparent scoring fields to `VACANCIES.csv`: six score components, interview chance, application priority, freshness and salary status.
- `fit_score` is now required to equal: skills/30 + transition/20 + compensation/15 + access/15 + lifestyle/10 + upside/10.
- Created `DASHBOARD.md` with expandable vacancy cards showing salary, apply link, freshness, exact score arithmetic, why-fit, gaps and next action.
- Completed a strict re-audit of the 16 legacy candidate records after the Halliburton false-positive exposed stale-search risk.
- Pruned the accepted pool from 16 provisional records to **7 currently defensible live records** rather than preserving an inflated count.

## Live pool after audit
1. **Khazar Engineering & Fabrication — Accountant** — CORE — 88 — Priority A — exact current third-party application, deadline 21.08.2026.
2. **Xsolla — Finance Coordinator** — CORE — 86 — Priority A — exact Lever ATS live.
3. **INFUSE — Data-Focused Project Coordinator** — ADJACENT — 84 — Priority A — exact Greenhouse ATS live, remote contract.
4. **Fairmont — Cost Controller** — ADJACENT — 80 — Priority B — exact Accor employer page live.
5. **Unibank — Financial Efficiency Lead/Chief Specialist** — ADJACENT — 79 — Priority B — current official employer vacancy list, deadline 04.09.2026.
6. **Xsolla — Delivery Manager, Self-Service** — STRETCH — 74 — Priority C — exact Lever ATS live, Baku explicitly eligible, published USD 30k–80k/year.
7. **Bolt — Operations Manager** — STRETCH — 71 — Priority C — exact Bolt employer page live.

## Important audit removals / watch leads
- **Azercell Procurement Analyst:** exact employer page says deadline 11.08.2026; aggregator date was wrong.
- **Bank of Baku Analytical Expert:** exact employer page says deadline 31.07.2026; removed.
- **Technip Energies Accounting Specialist:** conflicting indexed status and no exact current employer/ATS route established; watch only.
- **ABB Procurement reporting & analysis:** fresh discovery sources exist, but exact ABB employer vacancy was not resolved; watch only.
- **Avis Receivables:** exact LinkedIn role exists, but employer/ATS live route not independently established; watch only.
- **Azerconnect Finance Functional Consultant:** fresh strong lead and exact Oracle ATS URL exist, but ATS page itself was not directly validated through the available web path; watch until confirmed.
- **Coca-Cola CCI Master Data Responsible:** new-looking company LinkedIn repost conflicts with older exact listing; current employer requisition unresolved.
- **Weatherford Inventory Coordinator:** LinkedIn discovery only; exact Weatherford employer/ATS route unresolved.
- **DP World MCV Management Accountant:** exact Oracle ATS URL exists and third-party deadline says 20.08.2026, but ATS itself was not directly validated; urgent watch lead.

## Data discipline
- Never protect the counter at the expense of accuracy.
- Search/LinkedIn recency is discovery, not proof.
- Exact employer/ATS status wins.
- Every accepted vacancy must be rechecked immediately before CV tailoring/application.
- Every future run must maintain `DASHBOARD.md` as well as the CSV ledgers.

## NEXT ACTION
1. Re-attempt exact ATS validation for urgent high-value watch leads, especially DP World and Azerconnect; if confirmed live, return them to `VACANCIES.csv` with full transparent scorecards.
2. Continue new search toward 100, but only count roles that pass the strict live-route rule in the same run.
3. Prioritize fresh employer/ATS sources and international/local employers where compensation can plausibly exceed 2,500 AZN net.
4. Expand beyond finance into master data, procurement/P2P, reporting, process improvement, ERP support, operations, supply chain/warehouse, project coordination, customer operations and other strong transferable-skill roles.
5. Seek published salary or defensible salary evidence; never invent a local salary figure.
6. After every run update `VACANCIES.csv`, `REJECTED.csv`, `DASHBOARD.md`, and this file.
