# Job Search Status

## Current state
- Phase: SEARCH / STRICT FRESHNESS AUDIT
- Last completed run: Manual Run #3 — 2026-08-19; immediate post-run correction after user live-page check.
- Candidate opportunities remaining after Halliburton correction: **16 / 100 provisional**.
- Halliburton Accountant, Sr removed from accepted pool after the user's live Halliburton page at 2026-08-19 23:22 Baku time showed only Lab Tech-Chemistry and no accountant vacancy.
- Rejected / expired / watch-not-counted leads recorded: **19**.
- Repository is the source of truth, but all 16 legacy accepted entries must now be re-audited under the stricter freshness rule before final application prioritization.

## Freshness correction
Search/index data can lag the employer's current careers page. A search result that appears new or says `Actively Hiring` is no longer sufficient evidence of an active vacancy. Halliburton demonstrated this failure mode: cached/indexed results still surfaced `Accountant, Sr`, while the user's current employer page did not.

From now on:
- Search engines, LinkedIn snippets and aggregators are discovery only.
- Exact employer/ATS application pages are required wherever available.
- If the employer page conflicts with indexed/search data, employer page wins.
- If the tool-accessible employer page itself is based on an older crawl/cache, the vacancy must be marked with freshness uncertainty rather than presented as definitely live.
- Before the user applies, exact live status must be checked again.

## Current candidate ranking pending strict re-audit
1. **Azercell — Procurement Analyst** — ADJACENT — fit 92.
2. **Technip Energies — Accounting Specialist** — CORE — fit 91.
3. **ABB — Procurement reporting and analysis specialist** — ADJACENT — fit 90.
4. **Avis Azerbaijan — Accounting Specialist - Receivables** — CORE — fit 89.
5. **Khazar Engineering & Fabrication — Accountant** — CORE — fit 88.
6. **Xsolla — Finance Coordinator** — CORE — fit 86.
7. **Coca-Cola CCI — Master Data Responsible** — ADJACENT — fit 85.
8. **DP World — MCV Management Accountant** — CORE — fit 85.
9. **INFUSE — Data-Focused Project Coordinator** — ADJACENT — fit 84.
10. **Bank of Baku — Business Development Analytical Expert** — ADJACENT — fit 83.
11. **Fairmont — Cost Controller** — ADJACENT — fit 80.
12. **Unibank — Financial Efficiency Lead/Chief Specialist** — ADJACENT — fit 79.
13. **Azerconnect — Finance Functional Consultant** — ADJACENT — fit 78.
14. **Xsolla — Delivery Manager, Self-Service** — STRETCH — fit 74.
15. **Weatherford — Inventory Coordinator** — STRETCH — fit 73.
16. **Bolt — Operations Manager** — STRETCH — fit 71.

## NEXT ACTION
1. Do **not** search for new vacancies first. Audit every one of the remaining 16 accepted records under the new strict freshness rule.
2. For each, resolve the most exact employer-controlled careers/ATS URL available and record whether the accessible data is truly current, recently crawled, or freshness-uncertain.
3. Move any closed, missing, expired or unverified role to `REJECTED.csv`; do not preserve a role merely to maintain the counter.
4. Recalculate the true accepted count after the audit.
5. Only then resume new searches toward 100, using search/index results as discovery rather than proof of availability.
6. Re-check exact live status again immediately before CV tailoring/application because even a verified role can close between runs.
