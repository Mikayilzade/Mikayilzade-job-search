# Job Search Status

## Current state
- Phase: SEARCH / QUALIFICATION with browser-aware freshness.
- Last correction: Manual live-browser audit — 2026-08-20 around 00:16–00:19 AZT.
- **Browser-confirmed live opportunities: 4.**
- User-facing interface: `DASHBOARD.md`.
- Repository remains the sole persistent source of truth.

## Root-cause finding
The prior `strict live` rule was still too weak because ChatGPT web/search can return stored crawl snapshots of employer/ATS pages. A page being readable through web does not prove that the same exact URL is currently live in a normal browser.

The user tested all 8 dashboard links:
- LIVE: Xsolla Finance Coordinator; Unibank Financial Efficiency Lead/Chief Specialist; Xsolla Delivery Manager, Self-Service; Bolt Operations Manager.
- CLOSED/REMOVED: Khazar Engineering Accountant; INFUSE Data-Focused Project Coordinator; Xsolla HR Project Coordinator; Fairmont Cost Controller.

Observed cache-lag examples:
- Xsolla HR: normal browser showed Lever 404 while web still exposed an older job snapshot.
- INFUSE: normal browser said vacancy no longer available while web still exposed an older Greenhouse application snapshot.
- Fairmont: current exact page is 404 while search still contains the previous job description.
- Khazar: normal browser returned page-not-found while search still contained a cached posting with future deadline.

Therefore `LIVE_ATS` / `LIVE_EMPLOYER` based solely on readable web snapshot is retired as proof of current availability.

## Confirmed live pool
1. **Xsolla — Finance Coordinator** — CORE — 86 — Priority A — Baku on-site — user-browser confirmed live.
2. **Unibank — Financial Efficiency Lead/Chief Specialist** — ADJACENT — 79 — Priority B — Baku — user-browser confirmed live.
3. **Xsolla — Delivery Manager, Self-Service** — STRETCH — 74 — Priority C — remote, Baku explicit — user-browser confirmed live — USD 30k–80k/year published.
4. **Bolt — Operations Manager** — STRETCH — 71 — Priority C — Baku on-site — user-browser confirmed live.

## Data discipline from now on
- `USER_BROWSER_LIVE` is strong current availability evidence.
- `USER_BROWSER_CLOSED` immediately removes a role from the live pool.
- Web/search/ATS content with an older crawl is `TOOL_SNAPSHOT`: useful for discovery and analysis, but not proof of current availability.
- Direct 404/closed evidence wins over a cached positive snapshot.
- Before CV tailoring or application, exact URL must be opened again.
- Keep salary status, access, score arithmetic, fit gaps and interview chance separate from freshness.

## NEXT ACTION
1. Continue searching broadly for strong Baku/Azerbaijan and explicitly eligible remote opportunities.
2. For every new result, record whether evidence is `TOOL_SNAPSHOT` or genuinely browser-confirmed; never call a cached snapshot definitely live.
3. Keep promising current-looking tool discoveries as Watch/candidates rather than deleting them solely because browser confirmation is not yet available.
4. Do not inflate the live count from cached data.
5. Later perform a deeper requirement-by-requirement review of each browser-confirmed vacancy: responsibilities, must-haves, transferable evidence, real gaps, CV changes, likely interview questions, compensation, workload and red flags.
6. Discuss with the user whether the headline target `100` should mean (A) 100 strong candidate leads with a separate live-verification flag, or (B) 100 browser-confirmed live vacancies. Option A is far more autonomous; Option B requires repeated real-browser validation.
