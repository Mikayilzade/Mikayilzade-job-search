# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #32 — 2026-08-21 around 21:32 AZT**.
- **Candidate pool: 256 unique total.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- Historical master candidates remain in `CANDIDATES.csv`; additive candidate ledgers continue through `CANDIDATES_RUN32.csv`.
- Rejected history is in `REJECTED.csv` plus additive ledgers through `REJECTED_RUN32.csv`.
- Repository remains the sole persistent source of truth.
- Counter reconciliation: candidate IDs reach `C257`, but historical `C158` is absent, so the true unique count is 256.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue autonomous search and add new high-quality options until the user explicitly stops the process.

## Latest run result
Added **5** new candidates, C253–C257:
1. **Bravo Supermarket Azerbaijan — Internal Control Specialist — 87 — ADJACENT / Priority A.** Employer careers page currently exposes the vacancy/send-CV route. Internal-control testing, business-process reviews, weakness remediation and Excel are unusually transferable; compensation and posting date are unpublished.
2. **IRES — Procurement Specialist — 86 — ADJACENT / Priority A.** Current exact JobSearch listing; deadline 13.09.2026. PR-to-PO, supplier comparisons, bid sheets, payment terms, contracts and finance coordination strongly match P2P/vendor/ERP strengths.
3. **Unibank — eCommerce və Ekvayrinq üzrə Mütəxəssis / aparıcı Mütəxəssis — 77 — ADJACENT / Priority B.** Published 21.08.2026; deadline 20.09.2026. Merchant onboarding/partner operations and issue handling transfer, but direct acquiring/commercial growth experience is a gap.
4. **Bank of Baku — Əməliyyat bölməsinin kiçik eksperti — 75 — ADJACENT / Priority B.** Published 21.08.2026; deadline 22.08.2026. Document validation/system entries/transaction operations fit, but junior title creates serious compensation/seniority risk.
5. **ABB — Risk data analitiki/aparıcı risk data analitiki — 71 — STRETCH / Priority C.** Published 20.08.2026; deadline 19.09.2026. Large-data/KPI/business-requirement work transfers, while Python/SQL/statistics/ML are major gaps.

## Rejected / watch this run
- **Supertoys — Payroll Accountant:** 1,200 AZN, below target.
- **Home Finance BOKT — Senior Finance Specialist:** 1,200 AZN + bonus, below target.
- **Xalq Bank — Internal Control Monitoring:** mandatory bank monitoring/business-credit experience + master's degree makes transition unattractive versus better controls roles.
- **ABB — Card Center Assistant:** primarily physical delivery/basic reporting; seniority/economic mismatch.
- **ABB — Model Risk Specialist/Lead:** Python/SQL/model validation/statistics/ML gap too large.
- **Xalq Bank — Payment Technology Support:** status conflict; current index exists, but detailed copies carry old deadline and deep Java/SQL/CMS requirements.

## Browser-confirmed live subset
1. **Xsolla — Finance Coordinator — 86**.
2. **Unibank — Financial Efficiency Lead/Chief Specialist — 79**.
3. **Xsolla — Delivery Manager, Self-Service — 74** — remote/Baku — USD 30k–80k/year published.
4. **Bolt — Operations Manager — 71**.

## NEXT ACTION
1. Continue open-ended search; target roughly 6–10 genuinely useful new candidates per run when the market supports it, but do not lower quality to hit a quota.
2. Prioritize direct AP/Finance Ops, SAP/S4/MDG/master data, finance systems/ERP, treasury/payments, controls/reporting, process automation/RPA, data quality/governance and selective high-upside adjacent roles.
3. Broaden fresh employer/ATS searches beyond saturated generic accounting/procurement boards, including Azerbaijan-eligible international remote roles; verify country eligibility rather than assuming remote means Azerbaijan.
4. Audit high-scoring UNKNOWN-compensation roles as credible pay evidence appears; move clearly sub-target roles to rejected.
5. Dedupe against `CANDIDATES.csv`, all `CANDIDATES_RUN*.csv`, `REJECTED.csv`, and all `REJECTED_RUN*.csv` before every addition.
6. Preserve browser-verification separation; `VACANCIES.csv` changes only on browser-confirmed evidence.
7. Continue until an explicit user stop instruction is recorded.
