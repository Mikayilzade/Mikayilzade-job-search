# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #23 — 2026-08-21 around 12:45 AZT**.
- **Candidate pool: 201 total.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- Historical master ledger: `CANDIDATES.csv` (C001–C143).
- Additive ledgers: `CANDIDATES_RUN15.csv` through `CANDIDATES_RUN23.csv`. Treat all together as the current source of truth until consolidation.
- Rejected history is in `REJECTED.csv` plus `REJECTED_RUN19.csv` through `REJECTED_RUN23.csv`.
- Repository remains the sole persistent source of truth.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue adding high-quality options until the user explicitly stops the process.

## Latest run result
Added **3** high-quality new candidates, C200–C202; market quality did not justify padding to 6–10:
1. **Company — Maliyyə hesabatı üzrə mütəxəssis — 86 — ADJACENT / Priority A.** Fresh exact JobSearch page, deadline 20.09.2026. Financial-reporting analysis, management reporting, budget participation, reporting automation, Excel and Power Query fit strongly. Main gap: direct consolidated reporting/accounting-policy ownership.
2. **Radisson Baku Hotel — Accounts Receivable — 86 — CORE / Priority A.** Exact current JobSearch page, deadline 14.09.2026. Receivables, payments, invoices, reconciliations and reporting are direct transferable finance-operations skills. Main gaps: 1C and hotel AR experience.
3. **Qala Group — Baş Təchizat Mütəxəssisi / Senior Procurement Specialist — 80 — ADJACENT / Priority B.** Exact current page with direct application route and deadline 12.09.2026. Strong P2P/vendor/ERP/Excel/reporting transfer; direct strategic procurement, category management and negotiations are the main gaps.

## Rejected this run
`REJECTED_RUN23.csv` adds:
- **Kontakt Home — İradların həlli üzrə inzibatçı — 650–900 AZN — REJECTED_COMP.**
- **Akabe İnşaat — Mühasib — 700–1000 AZN — REJECTED_COMP.**
- **Krispy Kreme — Təchizat üzrə mütəxəssis — 1000–1500 AZN — REJECTED_COMP.**
- **Araz Supermarket — SAP Consultant — CLOSED.** Exact LinkedIn page states no longer accepting applications.

`VACANCIES.csv` was not changed because no new user-browser confirmation was available. C200–C202 remain `TOOL_SNAPSHOT` pending manual browser verification.

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
2. Before deduplication, read `CANDIDATES.csv` and all additive candidate ledgers through `CANDIDATES_RUN23.csv`; current absolute pool is 201. Also read all rejected ledgers through `REJECTED_RUN23.csv`.
3. Prioritize direct AP/Finance Ops; SAP/S4/MDG/master data; finance systems/ERP; controls/reporting; process automation/RPA; data quality/governance; high-value procurement/vendor/P2P and adjacent operations.
4. Give extra attention to fresh employer/ATS pages, especially newly posted finance-reporting, ERP/data-governance, bank systems and finance-automation roles; record exact access constraints and published compensation where available.
5. Keep auditing old `UNKNOWN` salaries when fresh published figures surface; remove materially under-target candidates rather than protecting the count.
6. Formal maintenance when convenient: consolidate additive candidate/rejected ledgers into master CSVs without changing counts.
7. Preserve browser-verification separation; the user will manually test attractive links later.
8. Continue until an explicit user stop instruction is recorded.
