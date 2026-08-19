# Search Rules

## Economic target
Minimum target: 2,500 AZN net/month equivalent. Prefer 3,000–5,000+ AZN or strong upside. Unpublished compensation stays `UNKNOWN`; never invent employer salary.

## Hiring accessibility
- `LOCAL_AZ` — Baku/Azerbaijan employment.
- `REMOTE_AZ_EXPLICIT` — Baku/Azerbaijan/CIS including Baku is explicitly eligible.
- `REMOTE_WORLDWIDE` — explicit worldwide/global remote.
- `CONTRACTOR_PLAUSIBLE` — legal contractor/B2B/EOR route is plausible and not prohibited.
- `RELOCATION` — worthwhile relocation/visa route.
- `UNCLEAR` — cannot be treated as accessible until resolved.

Never evade employment, tax, immigration, KYC, sanctions, geo-restrictions or platform rules.

## Critical freshness limitation
ChatGPT web/search results may contain a stored crawl snapshot rather than the page's current browser state. A result can therefore still display a full job description and an `Apply` button after the real ATS/employer page has already been removed.

Observed examples on 2026-08-20:
- Xsolla HR Project Coordinator: web still exposed an older Lever page while the user's normal browser returned Lever 404.
- INFUSE Data-Focused Project Coordinator: web still exposed an older Greenhouse application while the user's normal browser said the vacancy was no longer available.
- Fairmont Cost Controller: search still exposed the prior job snapshot while the current page returned 404.
- Khazar Engineering Accountant: web search still held a posting with a future deadline while the user's current JobSearch page returned page-not-found.

Therefore **`web result exists` is never equivalent to `live vacancy`**.

## Freshness evidence levels
Use these exact concepts:

### `USER_BROWSER_LIVE`
Strongest evidence available in this workflow. The user opened the exact vacancy/apply URL in a normal browser during the current review and the role/application is present. This may be presented as currently live.

### `USER_BROWSER_CLOSED`
The user opened the exact URL and received 404, removed, expired, or no-longer-available. Immediately remove from the live pool and preserve in `REJECTED.csv`.

### `TOOL_SNAPSHOT`
Web/search/open returns vacancy content but also indicates it was crawled previously, or current browser state cannot be independently established. This is **discovery/current-looking evidence only**, not proof of live status.

### `DIRECT_404_OR_CLOSED`
A direct tool open currently returns 404/closed. Treat as closed unless stronger current employer evidence contradicts it.

### `STATUS_CONFLICT`
Different sources disagree. Do not call it live. Preserve the lead with the conflict explanation.

## What may count as confirmed live
A row may use `status=QUALIFIED` and `freshness=USER_BROWSER_LIVE` when current browser verification exists.

For autonomous search, a strong role may be retained as a **candidate needing browser verification**, but it must not be described as definitely live merely because a cached employer/ATS page is readable through web search.

Before any actual application or CV tailoring, open the exact apply URL again in a normal browser. Vacancy availability can change between runs.

## Fit scoring — transparent arithmetic
Every retained opportunity must store all six components. `fit_score` is their arithmetic sum:
- `skill_30` — direct existing-skill overlap: max 30.
- `transition_20` — realistic learnability/gap: max 20.
- `compensation_15` — published pay or defensible target likelihood: max 15.
- `access_15` — practical Baku hiring access: max 15.
- `lifestyle_10` — workload/hours/remote/commute fit: max 10.
- `upside_10` — career ceiling, skill growth, stability, salary upside: max 10.

Guide:
- 85–100: priority candidate.
- 75–84: strong candidate.
- 65–74: plausible stretch with meaningful upside.
- <65: reject unless there is a specific strategic reason.

`interview_chance` is separate from fit score.

## Application priority
- `A` — apply early if salary/critical unknowns pass.
- `B` — good application after A roles.
- `C` — stretch/upside.
- `WATCH` — promising but blocked by freshness/access/pay evidence.

## Compensation labels
- `PUBLISHED` — job/employer states it.
- `CANDIDATE_ASK` — candidate is asked for expected compensation.
- `ESTIMATED` — sourced external benchmark, never employer salary.
- `UNKNOWN` — no defensible figure.

## Interface maintenance
After every run:
1. Update `VACANCIES.csv` and `REJECTED.csv`.
2. Update `DASHBOARD.md` with clickable URLs, score arithmetic, salary, access and **verification evidence**.
3. Update `STATUS.md` with separate wording for browser-confirmed live roles versus tool-discovered/watch leads.
4. Never protect a counter at the expense of current-status accuracy.
