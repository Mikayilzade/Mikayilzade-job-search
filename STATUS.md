# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #24 — 2026-08-21 around 13:40 AZT**.
- **Candidate pool: 208 total.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- Historical master ledger: `CANDIDATES.csv` (C001–C143).
- Additive ledgers: `CANDIDATES_RUN15.csv` through `CANDIDATES_RUN24.csv`. Treat all together as the current source of truth until consolidation.
- Rejected history is in `REJECTED.csv` plus `REJECTED_RUN19.csv` through `REJECTED_RUN24.csv`.
- Repository remains the sole persistent source of truth.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue adding high-quality options until the user explicitly stops the process.

## Latest run result
Added **7** new candidates, C203–C209:
1. **Mars Overseas Baku — Baş mütəxəssis (Mühasibatlıq şöbəsi) — 91 — CORE / Priority A.** ERP functionality oversight, accounting records, internal controls, audit support, reporting, process improvement and staff guidance create an unusually strong Finance Ops/S4 bridge. Current exact listing states deadline 04.09.2026. Main gaps: high 1C 8.3/1C ERP, FMCG preference and broader statutory-accounting ownership.
2. **Bank of Baku — Ümumi audit şöbəsinin aparıcı auditoru — 84 — ADJACENT / Priority B.** Official employer page states deadline 31.08.2026 and 1–2 years relevant experience. Internal-control evaluation, financial/operational analysis, audit testing and findings reporting transfer strongly; formal risk-based audit ownership and banking-audit depth are gaps.
3. **STP-HEAVY ENGINEERING — Tender məhsullarının alışı üzrə aparıcı mütəxəssis — 84 — ADJACENT / Priority B.** Official STP careers page currently lists the role. Supplier selection, tender procurement, payment follow-up, contracts and reporting map well to vendor/P2P strengths. Direct industrial sourcing/tender negotiation and Sumqayit commute are key risks.
4. **SOCAR Downstream Management — Mal-materialların çatdırılması üzrə mütəxəssis — 82 — ADJACENT / Priority B.** Current company/employer indexes surface the role. Delivery scheduling, order/material tracking, documentation and coordination transfer from P2P/ERP operations. Direct materials-logistics/oil-industry experience and exact detailed requirements remain unresolved.
5. **Mars Overseas Baku — Hesabatlıq şöbəsinin rəhbəri — 80 — STRETCH / Priority B.** Financial/budget/management reporting, audit follow-up and process improvement offer strong upside. Current sources show deadline around 05–06.09.2026. Department leadership and end-to-end budgeting/forecasting ownership are substantial gaps.
6. **Bank of Baku — Menecment informasiya sistemləri şöbəsinin eksperti — 78 — ADJACENT / Priority B.** Official employer page states deadline 31.08.2026 and no relevant experience requirement. Reporting, BI publication, troubleshooting, testing and data-control work fit reporting/automation strengths; high SQL/PLSQL, Oracle BI and high English/Russian are material gaps.
7. **Azersun Holding / Azərbaycan Sənaye Bankı — Risklərin təhlili və hesabatlılıq üzrə baş mütəxəssis — 76 — STRETCH / Priority C.** Financial-result analysis, reporting, risk-map documentation and audit/process review are transferable, but LCR/GAP/stress-testing and direct banking-risk experience create a meaningful transition gap. Current sources show deadline around 09–10.09.2026.

## Rejected this run
`REJECTED_RUN24.csv` adds:
- **Azərbaycan Respublikasının Mərkəzi Bankı — Data Operations / data əməliyyatları üzrə böyük mütəxəssis — EXPIRED.** Current public copy shows deadline 18.08.2026, so stale search copies are not counted.

`VACANCIES.csv` was not changed because no new user-browser confirmation was available. C203–C209 remain `TOOL_SNAPSHOT` pending manual browser verification.

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
1. Continue open-ended search; target roughly 6–10 genuinely useful new candidates per run when the market supports it, but do not pad.
2. Before deduplication, read `CANDIDATES.csv` and all additive candidate ledgers through `CANDIDATES_RUN24.csv`; current absolute pool is 208. Also read all rejected ledgers through `REJECTED_RUN24.csv`.
3. Prioritize direct AP/Finance Ops; SAP/S4/MDG/master data; finance systems/ERP; controls/reporting; process automation/RPA; data quality/governance; high-value procurement/vendor/P2P and adjacent operations.
4. Give extra attention to fresh employer/ATS pages, especially newly posted finance systems/ERP, reporting, bank operations/control, master-data/data-governance and automation roles; record exact access constraints and published compensation where available.
5. Keep auditing old `UNKNOWN` salaries when fresh published figures surface; remove materially under-target candidates rather than protecting the count.
6. Formal maintenance when convenient: consolidate additive candidate/rejected ledgers into master CSVs without changing counts.
7. Preserve browser-verification separation; the user will manually test attractive links later.
8. Continue until an explicit user stop instruction is recorded.
