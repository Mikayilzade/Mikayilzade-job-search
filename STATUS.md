# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #21 — 2026-08-21 around 10:35 AZT**.
- **Candidate pool: 191 total.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- Historical master ledger: `CANDIDATES.csv` (C001–C143).
- Additive ledgers: `CANDIDATES_RUN15.csv` (C144–C150), `CANDIDATES_RUN16.csv` (C151–C157), `CANDIDATES_RUN17.csv` (C159–C165 after correction), `CANDIDATES_RUN18.csv` (C166–C172), `CANDIDATES_RUN19.csv` (C173–C178), `CANDIDATES_RUN20.csv` (C179–C185), and `CANDIDATES_RUN21.csv` (C186–C192). Treat all together as the current 191-candidate source of truth until consolidation.
- Rejected history is in `REJECTED.csv`, `REJECTED_RUN19.csv`, `REJECTED_RUN20.csv`, and `REJECTED_RUN21.csv`.
- Repository remains the sole persistent source of truth.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue adding high-quality options until the user explicitly stops the process.

## Latest run result
Added **7** new candidates, C186–C192:
1. **ERPgo — ERP Support Consultant — 89 — ADJACENT / Priority A.** Official employer application page exposes an exact full-time Baku ERP Support Consultant role. ERP support, issue triage, process understanding, user coordination and documentation are a very strong S4/MDG transition. Main gaps: formal ERP consulting/support ownership and deeper configuration knowledge. Salary/deadline unpublished.
2. **PASHA Life — Hesabatlılıq şöbəsinin baş mütəxəssisi — 86 — ADJACENT / Priority A.** Reporting, data quality, cross-functional finance coordination and process efficiency fit strongly; recent employer/social reposts still surface the vacancy. Main gap: IFRS/group reporting depth and full financial-statement ownership.
3. **Fancy Group — Uçot və inzibati işlər üzrə mütəxəssis — 84 — CORE / Priority B.** Primary documents, cash accounting, 1C entries, stock movement and document controls are strong transactional-finance overlap. Current JobSearch page gives deadline 14.09.2026. Main risk: level may be below current seniority; compensation is interview-based.
4. **FOTON — Satınalmalar üzrə Baş Mütəxəssis — 82 — ADJACENT / Priority B.** Tender/RFQ administration, supplier negotiations, purchase orders and document flow are a credible P2P progression. Current copy shows deadline 06.09.2026. Main gaps: 4–5 years direct procurement/tender ownership and construction-material purchasing.
5. **PASHA Bank — Təşkilati Risklərin İdarə Edilməsi üzrə Baş mütəxəssis — 79 — ADJACENT / Priority B.** Controls, monitoring, policy/process review and reporting transfer from reconciliations/audit support; current JobSearch requisition deadline 15.09.2026. Main gaps: ICAAP, enterprise-risk frameworks and senior banking-risk ownership.
6. **Bank Respublika — PL/TMM və Komplayens Kiçik Mütəxəssis/Mütəxəssis — 76 — ADJACENT / Priority B.** Data review, exception detection and controlled documentation fit; current listing explicitly allows candidates without prior AML experience and promises mentoring. Deadline 11.09.2026. Main risks: regulated AML/compliance domain and junior compensation uncertainty.
7. **PASHA Bank — Model riskləri üzrə Kiçik mütəxəssis — 74 — STRETCH / Priority C.** Governance, monitoring, reporting and data-quality skills transfer, but model-risk frameworks/statistics/financial-risk concepts and fluent English are substantial gaps. Current sources show deadline around 14–18.09.2026; exact browser deadline needs checking.

## Rejected this run
`REJECTED_RUN21.csv` adds 3 economically weak roles:
- **Harvesso — Foreign Procurement Specialist — 800 AZN net fixed + KPI bonus**.
- **Army Group — Maliyyə müdiri — 2,000–2,500 AZN**; top of the range only reaches the target threshold while scope is manager-level.
- **Eurostar Group — Keyfiyyətə Nəzarət üzrə Mütəxəssis — 1,300 AZN**.

`VACANCIES.csv` was not changed because no new user-browser confirmation was available. All C186–C192 remain `TOOL_SNAPSHOT` pending manual browser verification.

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
1. Continue open-ended search; target roughly 6–10 genuinely useful new candidates per run when the market supports it.
2. Before deduplication, read `CANDIDATES.csv` and all additive candidate ledgers through `CANDIDATES_RUN21.csv`; current absolute pool is 191. Also read all rejected ledgers through `REJECTED_RUN21.csv`.
3. Prioritize direct AP/Finance Ops; SAP/S4/MDG/master data; finance systems/ERP; controls/reporting; process automation/RPA; data quality/governance; high-value procurement/vendor/P2P and adjacent operations.
4. Expand current employer/ATS searches in Baku and explicitly Azerbaijan-eligible remote markets; record exact access constraints and published compensation where available.
5. Keep auditing old `UNKNOWN` salaries when fresh published figures surface; remove materially under-target candidates rather than protecting the count.
6. Formal maintenance when convenient: consolidate additive candidate/rejected ledgers into master CSVs without changing counts.
7. Preserve browser-verification separation; the user will manually test attractive links later.
8. Continue until an explicit user stop instruction is recorded.
