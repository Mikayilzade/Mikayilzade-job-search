# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #25 — 2026-08-21 around 14:45 AZT**.
- **Candidate pool: 214 total.**
- **Browser-confirmed live subset: 4.**
- User-facing interface: `DASHBOARD.md`.
- Historical master ledger: `CANDIDATES.csv` (C001–C143).
- Additive ledgers: `CANDIDATES_RUN15.csv` through `CANDIDATES_RUN25.csv`. Treat all together as the current source of truth until consolidation.
- Rejected history is in `REJECTED.csv` plus additive rejected ledgers through `REJECTED_RUN25.csv`.
- Repository remains the sole persistent source of truth.

## Counter note
The highest candidate ID is C215 while the absolute pool is 214 because prior candidate C158 was removed after published compensation proved materially below target. Do not infer pool size from the highest ID alone.

## User override
On 2026-08-20 the user explicitly removed the previous 100-candidate cap. Continue adding high-quality options until the user explicitly stops the process.

## Latest run result
Added **6** new candidates, C210–C215:
1. **Hyatt Regency — Accounts Payable Clerk — 92 — CORE / Priority A.** Vendor invoices, expense allocation, payments, vendor records and vendor reconciliations are almost a direct match to current AP strengths. Current indexed listing states deadline 10.09.2026. Main unresolved item is compensation and exact Hyatt employer ATS/browser state.
2. **Kapital Bank Life — Maliyyə təhlili və idarəetmə hesabatlığı şöbəsinin mütəxəssisi/aparıcı mütəxəssisi — 86 — ADJACENT / Priority A.** Financial-result analysis, management reporting, IFRS support, auditor coordination and Excel provide a strong bridge from finance operations. Current LinkedIn indexes resurface the role as recent; exact browser freshness must be checked. Main gaps are deeper IFRS/reporting ownership and high English.
3. **SAMİRAMİS — Baş mühasib müavini (Xidmət sahəsi üzrə) — 84 — CORE / Priority A.** AP/AR, bank/cash transactions, invoice control, monthly reporting and accounting operations map strongly to existing skills. Current exact listing states deadline 12.09.2026. Main gaps are local statutory/tax/full-financial-statement ownership and daily 1C 8.2.
4. **Qaya Nəqliyyat — Baş Mühasib — 82 — CORE / Priority B.** Current exact listing states deadline 28.08.2026 and publishes **AZN 3,000–5,000/month**. Daily finance operations, reporting and controls transfer well, but chief-accountant tax/statutory/government-reporting and leadership ownership are substantial gaps. Gross/net basis is not stated.
5. **PASHA Bank — Daxili Audit üzrə Aparıcı Auditor — 82 — ADJACENT / Priority B.** Audit procedures, evidence collection, process-owner interviews, findings, working papers and remediation monitoring fit controls/audit-support strengths. Current JobSearch page states deadline 30.08.2026. Formal risk-based audit and direct banking audit are gaps.
6. **Xalq Bank — Daxili Audit İdarəsinin Daxili audit şöbəsi / Mütəxəssis — 79 — ADJACENT / Priority B.** Current exact JobSearch page states deadline 28.08.2026. Internal-control/risk review and financial-record reliability fit; required master's degree and 3 years banking experience materially reduce interview probability.

## Rejected this run
`REJECTED_RUN25.csv` adds:
- **Novo Nordisk — Finance Business Partner — CLOSED.** Exact LinkedIn page says no longer accepting applications; older Baku requisitions had February/March 2026 deadlines, so fresh-looking index cards are stale.
- **VMF KAFE — Accountant — REJECTED_COMP.** Fresh 18.08.2026 listing publishes salary **700–750 AZN**, far below target.

`VACANCIES.csv` was not changed because no new user-browser confirmation was available. C210–C215 remain `TOOL_SNAPSHOT` pending manual browser verification.

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
2. Before deduplication, read `CANDIDATES.csv` and all additive candidate ledgers through `CANDIDATES_RUN25.csv`; current absolute pool is 214. Also read all rejected ledgers through `REJECTED_RUN25.csv`.
3. Prioritize direct AP/Finance Ops; SAP/S4/MDG/master data; finance systems/ERP; controls/reporting; process automation/RPA; data quality/governance; high-value procurement/vendor/P2P and adjacent operations.
4. Give extra attention to fresh employer/ATS pages and newly indexed roles in finance systems, reporting, AP/AR, bank operations/control, master data/data governance and automation. Prefer exact employer/careers pages when discoverable.
5. Audit old `UNKNOWN` salaries whenever fresh published figures surface; remove materially under-target candidates rather than protecting the count.
6. Formal maintenance when convenient: consolidate additive candidate/rejected ledgers into master CSVs without changing counts or losing history.
7. Preserve browser-verification separation; the user will manually test attractive links later.
8. Continue until an explicit user stop instruction is recorded.
