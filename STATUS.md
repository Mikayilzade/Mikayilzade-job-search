# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #45 — 2026-08-22 around 08:30 AZT**.
- Last manual vacancy review: **2026-08-22 — Tabaterra / Target Logistics**.
- **Candidate pool: 318 unique total.**
- **Browser-confirmed live subset: 7.**
- User-facing interface: `DASHBOARD.md`.
- Historical master candidates remain in `CANDIDATES.csv`; additive candidate ledgers continue through `CANDIDATES_RUN45.csv`.
- Rejected history is in `REJECTED.csv` plus additive ledgers through `REJECTED_RUN45.csv`.
- Repository remains the sole persistent source of truth.
- Counter reconciliation: candidate IDs reach `C319`, but historical `C158` is absent, so the true unique count is 318.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue autonomous search and add new high-quality options until the user explicitly stops the process.

## Latest run result
Added **5** new candidates, C315–C319:
1. **Baku Electronics — ERP üzrə mütəxəssis — C315 — 83 — ADJACENT / Priority A.** Employer careers index is current and lists deadline **18 Sep 2026**. ERP operations, master/stock data, user support, issue resolution and finance/procurement document processing transfer unusually well from SAP/S4/MDG finance operations. Main gaps: explicit SQL and Power BI proficiency plus direct retail ERP configuration.
2. **Xalq Bank — Ödəniş sistemləri ilə iş şöbəsinin aparıcı / baş mütəxəssisi — C316 — 80 — ADJACENT / Priority B.** Current banking vacancy indexes list deadline **11 Sep 2026**. Payment/reporting/Excel/Power Query overlap is strong, but direct bank-card/payment-system experience is explicitly required.
3. **AZCD Group — Internal Control Specialist — C317 — 79 — ADJACENT / Priority B.** Employer career page currently exposes the vacancy. Process-control testing, weakness identification, inventory/process monitoring and remediation fit controls/reconciliation strengths. Exact posting date, deadline and compensation are unpublished.
4. **Azerbaijan International Mining Company — Procurement Specialist (Baku) — C318 — 78 — ADJACENT / Priority B.** Fresh local indexes list it posted **11 Aug 2026**. P2P/vendor/ERP/Excel and commercial-comparison skills transfer well; direct sourcing/negotiation and production-material procurement are the main gaps.
5. **Bank of Baku — Qeyri-kredit məhsulları şöbəsinin aparıcı eksperti — C319 — 71 — ADJACENT / Priority C.** Employer careers index currently lists a Baku iteration through **31 Aug 2026**. Reporting/data/process strengths transfer, but 2–3 years card-product banking experience plus Power BI/SQL make it a real stretch.

## Rejected this run
- **Azərbaycan Dəmir Yolları — Müqavilələrin tərtibatı və sənədlərlə iş üzrə mütəxəssis:** conflicting current copies show 14 Aug vs 7 Sep deadlines; exact employer status unresolved and Civil Code/contract-drafting gap is material.
- **Target Logistics — Logistics Specialist:** 15:00–01:00 office schedule, 1,500–3,000 AZN KPI-dependent pay and direct freight/customs requirements make the tradeoff weak.

## Browser-confirmed live subset
1. **Xsolla — Finance Coordinator — 86**.
2. **Unibank — Financial Efficiency Lead/Chief Specialist — 79**.
3. **OBA — Maliyyə üzrə Analtik (Logistika üzrə) — 79**.
4. **Xsolla — Delivery Manager, Self-Service — 74** — remote/Baku — USD 30k–80k/year published.
5. **Tabaterra — Aparıcı mühasib — 74** — user-found exact HRX link; deadline 18 Sep.
6. **OBA — BI & SQL Reporting Specialist (Lead) — 72 practical re-review**.
7. **Bolt — Operations Manager — 71**.

## NEXT ACTION
1. Continue open-ended search; add roughly 6–10 genuinely useful new candidates per run when quality/economics support it.
2. Re-check strongest unverified direct fits first: **Hyatt Regency AP, Pizza Mizza AP, ADA University AP, Marpro Logistics AP/AR Controller, Starcom Accountant, PASHA Bank Financial Control, Carlsberg Planning & Delivery, BAT Corporate Finance, Landau Aparıcı mühasib and Baku Electronics ERP**.
3. Prioritize direct AP/Finance Ops, SAP/S4/MDG/master data, finance systems/ERP, treasury/payments/settlements, controls/reporting, process automation/RPA and data quality/governance.
4. Keep searching employer-specific pages and Glorri/HRX/JobSearch; fresh roles continue to appear there before broader indexes catch up.
5. Search more AP/AR controller, finance-operations, payment operations, ERP implementation/support and business-application support roles.
6. Search Azerbaijan-eligible international remote roles and selective Baku international-organization/embassy roles where compensation and transferable operations skills justify a title change.
7. Search business-side SAP/ERP and payment operations rather than technical Basis/ABAP/DBA/payment-engineering roles.
8. Continue early compensation filtering and do not inflate scores for unpublished local salaries.
9. Dedupe against `CANDIDATES.csv`, all `CANDIDATES_RUN*.csv`, `REJECTED.csv`, and all `REJECTED_RUN*.csv` before every addition.
10. Preserve browser-verification separation; `VACANCIES.csv` changes only on browser-confirmed evidence.
11. Treat SQL/BI/FP&A/budgeting/forecasting/ERM, manufacturing accounting, payroll/HCM, local tax/statutory ownership, mandatory accounting certifications and direct audit methodology as real gaps unless demonstrated otherwise.
12. Continue until an explicit user stop instruction is recorded.
