# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #38 — 2026-08-22 around 01:55 AZT**.
- Last manual vacancy review: **2026-08-22 — Tabaterra / Target Logistics**.
- **Candidate pool: 276 unique total.**
- **Browser-confirmed live subset: 7.**
- User-facing interface: `DASHBOARD.md`.
- Historical master candidates remain in `CANDIDATES.csv`; additive candidate ledgers continue through `CANDIDATES_RUN38.csv`.
- Rejected history is in `REJECTED.csv` plus additive ledgers through `REJECTED_RUN38.csv`.
- Repository remains the sole persistent source of truth.
- Counter reconciliation: candidate IDs reach `C277`, but historical `C158` is absent, so the true unique count is 276.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue autonomous search and add new high-quality options until the user explicitly stops the process.

## Latest run result
Added **6** new candidates, C272–C277:
1. **SOCAR Tech — Data Governance Specialist — C272 — 84 — ADJACENT / Priority A.** Strongest new transferable-skills match: data quality, metadata, governance, process design, cross-functional improvement and controls map unusually well to S4/MDG/master-data experience. Deadline **28 Aug 2026**; salary unpublished.
2. **Bank Respublika — Operations Control / Initial Control Specialist or Lead — C273 — 82 — ADJACENT / Priority A.** Daily/monthly operational reporting, control checks, query handling, product/report testing and process compliance align well with reconciliation/audit-support/control experience. Fresh repost; deadline **17 Sep 2026**.
3. **PASHA Bank — Payment Execution Junior Specialist — C277 — 81 — CORE / Priority A.** Payment execution, transaction validation, documentation, support and system registration are very close to the candidate's current AP/payment-operations work. Main risk is the **junior title / unknown pay**, not functional fit. Deadline **31 Aug 2026**.
4. **Xalq Bank — Payment Systems Senior/Chief Specialist — C274 — 80 — ADJACENT / Priority B.** Excel, Power Query, payments reporting and analytical work transfer strongly; direct card-payments/banking experience is the real gap. Deadline **11 Sep 2026**.
5. **Aqrar Tədarük və Təchizat — Procurement Specialist/Lead/Chief range — C276 — 76 — ADJACENT / Priority B.** Strong P2P/document/supplier/reporting overlap, but direct public-procurement law and sourcing experience are meaningful gaps. Deadline **13 Sep 2026**.
6. **Enerji Məsələlərini Tənzimləmə Agentliyi — Economic Analysis, Tariff & Statistics Specialist — C275 — 72 — ADJACENT / Priority C.** Excel/reporting/financial-analysis basics fit, but DAX/Power BI/Oracle SQL and tariff/economic-analysis depth make it a genuine stretch.

## Rejected / conflict this run
- **Azerimed — Mühasib-operator:** 600–700 AZN; far below target.
- **AZAL — Operational Procurement Specialist:** exact current snapshot deadline was 21 Aug 2026; expired.
- **OnWay — Delivery Manager:** six-day week, personal-car requirement, KPI/bonus pay without guaranteed base, plus direct logistics gap.
- **PASHA Bank — RPA Junior Specialist:** potentially excellent automation fit, but current index conflicts with exact third-party pages showing the prior requisition expired in early August; hold outside pool until a current exact application page is resolved.

## Browser-confirmed live subset
1. **Xsolla — Finance Coordinator — 86**.
2. **Unibank — Financial Efficiency Lead/Chief Specialist — 79**.
3. **OBA — Maliyyə üzrə Analtik (Logistika üzrə) — 79**.
4. **Xsolla — Delivery Manager, Self-Service — 74** — remote/Baku — USD 30k–80k/year published.
5. **Tabaterra — Aparıcı mühasib — 74** — user-found exact HRX link; deadline 18 Sep.
6. **OBA — BI & SQL Reporting Specialist (Lead) — 72 practical re-review**.
7. **Bolt — Operations Manager — 71**.

## NEXT ACTION
1. Continue open-ended search; target roughly 6–10 genuinely useful new candidates per run when the market supports it, but keep fewer when quality/economics do not justify more.
2. Prioritize direct AP/Finance Ops, SAP/S4/MDG/master data, finance systems/ERP, treasury/payments/settlements, controls/reporting, process automation/RPA and data quality/governance.
3. Keep searching Glorri/HRX/employer-specific local sources because user-found vacancies proved generic searches can miss relevant roles.
4. Search Azerbaijan-eligible international remote roles and selective Baku international-organization/embassy roles where published compensation and transferable operations skills justify a title change.
5. Search business-side SAP/ERP and payment operations roles rather than technical Basis/ABAP/DBA/payment-engineering roles.
6. Continue early compensation filtering and do not inflate scores for unpublished local salaries; junior titles require explicit compensation verification.
7. Dedupe against `CANDIDATES.csv`, all `CANDIDATES_RUN*.csv`, `REJECTED.csv`, and all `REJECTED_RUN*.csv` before every addition.
8. Preserve browser-verification separation; `VACANCIES.csv` changes only on browser-confirmed evidence.
9. Treat SQL/BI/FP&A/budgeting/forecasting/ERM, manufacturing accounting, local tax/statutory ownership and direct banking/card-domain requirements as real gaps unless demonstrated otherwise.
10. Re-check PASHA Bank RPA if an exact current employer/ATS application page appears; the skill fit would be unusually strong.
11. Continue until an explicit user stop instruction is recorded.
