# Search Rules

## Primary search target
The headline goal is **100 strong candidate vacancies**, not 100 browser-confirmed live pages.

`CANDIDATES.csv` is the master pool. A role may count toward the 100 when:
- the functional fit is plausible enough to justify the user's attention;
- compensation plausibly meets the target or has meaningful upside;
- Baku/Azerbaijan access is local, explicit remote, or otherwise legally plausible;
- the vacancy/link is not already known to be closed, expired or impossible for the candidate;
- a score and reasoned gaps are recorded.

The user may manually browser-check only the first 20–30 or whichever candidates look attractive. Therefore browser verification is a **separate field**, not a prerequisite for counting toward 100.

`VACANCIES.csv` remains the subset the user has browser-confirmed live. `REJECTED.csv` stores known closed/expired/inaccessible/conflicted items.

## Economic target
Minimum target: 2,500 AZN net/month equivalent. Prefer 3,000–5,000+ AZN or strong upside. Unpublished compensation stays `UNKNOWN`; never invent employer salary.

## Hiring accessibility
- `LOCAL_AZ` — Baku/Azerbaijan employment.
- `REMOTE_AZ_EXPLICIT` — Baku/Azerbaijan/CIS including Baku is explicitly eligible.
- `REMOTE_WORLDWIDE` — explicit worldwide/global remote.
- `CONTRACTOR_PLAUSIBLE` — legal contractor/B2B/EOR route is plausible and not prohibited.
- `RELOCATION` — worthwhile relocation/visa route.
- `UNCLEAR` — candidate may be retained only if the role is unusually strong and access uncertainty is clearly flagged; do not present it as accessible.

Never evade employment, tax, immigration, KYC, sanctions, geo-restrictions or platform rules.

## Critical freshness limitation
ChatGPT web/search results may contain a stored crawl snapshot rather than the page's current browser state. A result can still display a full job description and an Apply button after the real ATS/employer page has been removed.

Therefore **`web result exists` is never equivalent to `live vacancy`**.

## Freshness evidence levels
### `USER_BROWSER_LIVE`
The user opened the exact vacancy/apply URL in a normal browser and the role/application was present. May be presented as currently live.

### `USER_BROWSER_CLOSED`
The user opened the exact URL and received 404, removed, expired or no-longer-available. Remove from candidate/live pools and preserve in `REJECTED.csv`.

### `TOOL_SNAPSHOT`
Web/search/open exposes vacancy content or a recent index, but current browser state is not guaranteed. **This may count toward the 100-candidate pool**, provided it otherwise passes fit/access/economic filters. It must be labelled clearly and never described as definitely live.

### `DIRECT_404_OR_CLOSED`
A direct tool open currently returns 404/closed. Treat as closed unless stronger current evidence contradicts it.

### `STATUS_CONFLICT`
Different sources disagree. Usually keep outside the 100 unless there is a strong current-looking application route worth a manual browser check; if retained, flag the conflict prominently.

## Candidate quality threshold
- Prefer score **70+**.
- 85–100: priority candidate.
- 75–84: strong candidate.
- 70–74: worthwhile stretch/adjacent option.
- 65–69: include only for a specific strategic reason.
- <65: reject.

Do not fill the 100 with random low-quality links just to hit the counter.

## Fit scoring — transparent arithmetic
Every retained candidate stores all six components. `fit_score` is their arithmetic sum:
- `skill_30` — direct existing-skill overlap: max 30.
- `transition_20` — realistic learnability/gap: max 20.
- `compensation_15` — published pay or defensible target likelihood: max 15.
- `access_15` — practical Baku hiring access: max 15.
- `lifestyle_10` — workload/hours/remote/commute fit: max 10.
- `upside_10` — career ceiling, skill growth, stability, salary upside: max 10.

`interview_chance` can be refined later and is separate from fit score.

## Application priority
- `A` — strongest candidate; inspect/apply early if live and salary/critical unknowns pass.
- `B` — good candidate.
- `C` — stretch/upside.
- `WATCH` — interesting but blocked by a serious access/fit/freshness issue.

## Compensation labels
- `PUBLISHED` — job/employer states it.
- `CANDIDATE_ASK` — candidate is asked for expected compensation.
- `ESTIMATED` — sourced external benchmark, never employer salary.
- `UNKNOWN` — no defensible figure.

## Search breadth
Do not limit to AP. Search CORE, ADJACENT and STRETCH roles across finance operations, P2P/AR/O2C, SAP/ERP/MDG, master data, procurement, reporting/data, process improvement, project/operations coordination, inventory/supply chain, finance systems, B2B customer/sales operations and other credible transferable-skill roles.

## Interface maintenance
After every run:
1. Update `CANDIDATES.csv` first; deduplicate by company/title/link.
2. Update `VACANCIES.csv` only when user-browser confirmation exists.
3. Update `REJECTED.csv` for known closed/expired/inaccessible/conflicted items.
4. Update `DASHBOARD.md` with candidate count, browser-confirmed count, clickable links, score, salary, access and verification level.
5. Update `STATUS.md` with true `candidate pool X/100` and next action.
6. Never protect a counter at the expense of candidate quality.

## Completion condition
At **100 / 100 candidate leads**, stop expanding the pool. Next phase is user review, browser verification of attractive roles, deep requirement-by-requirement analysis, CV variants, vacancy-specific tailoring and application sequencing.
