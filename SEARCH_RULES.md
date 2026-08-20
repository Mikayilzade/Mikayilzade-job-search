# Search Rules

## Primary search target
Build and continuously improve a pool of **strong candidate vacancies with no numeric upper limit**. The former 100-candidate goal is a completed historical milestone only. Per the user's 2026-08-20 instruction, keep adding high-quality new options until the user explicitly stops the process.

`CANDIDATES.csv` is the master pool. A role may be retained when:
- the functional fit is plausible enough to justify attention;
- compensation plausibly meets the target or has meaningful upside;
- Baku/Azerbaijan access is local, explicit remote, or otherwise legally plausible;
- the vacancy/link is not already known closed, expired or impossible;
- a transparent score and reasoned gaps are recorded.

Browser verification is a separate field, not a prerequisite for discovery. `VACANCIES.csv` remains the user-browser-confirmed live subset. `REJECTED.csv` stores known closed/expired/inaccessible/conflicted or clearly uneconomic items.

## Economic target
Minimum target: 2,500 AZN net/month equivalent. Prefer 3,000–5,000+ AZN or strong upside. Unpublished compensation stays `UNKNOWN`; never invent employer salary. Reject clearly published compensation materially below target unless exceptional documented upside justifies retaining it as a strategic exception.

## Hiring accessibility
- `LOCAL_AZ` — Baku/Azerbaijan employment.
- `REMOTE_AZ_EXPLICIT` — Baku/Azerbaijan/CIS including Baku is explicitly eligible.
- `REMOTE_WORLDWIDE` — explicit worldwide/global remote.
- `CONTRACTOR_PLAUSIBLE` — legal contractor/B2B/EOR route is plausible and not prohibited.
- `RELOCATION` — worthwhile relocation/visa route.
- `UNCLEAR` — retain only if unusually strong and flag access uncertainty clearly.

Never evade employment, tax, immigration, KYC, sanctions, geo-restrictions or platform rules.

## Freshness limitation
ChatGPT web/search can expose stored crawl snapshots. Therefore `web result exists` is never equivalent to `live vacancy`.

Evidence levels:
- `USER_BROWSER_LIVE` — user opened exact application URL and vacancy was present.
- `USER_BROWSER_CLOSED` — user opened exact URL and it was removed/expired/404; remove from candidate/live pools and preserve in `REJECTED.csv`.
- `TOOL_SNAPSHOT` — useful discovery/current-looking evidence, but browser state is not guaranteed. May be retained as a candidate when otherwise strong.
- `DIRECT_404_OR_CLOSED` — treat as closed unless stronger current evidence contradicts it.
- `STATUS_CONFLICT` — conflicting sources; flag prominently and usually keep outside the main pool unless particularly strong for manual verification.

## Candidate quality threshold
- Prefer score **70+**.
- 85–100: priority candidate.
- 75–84: strong candidate.
- 70–74: worthwhile stretch/adjacent option.
- 65–69: include only for a specific strategic reason.
- <65: reject.

Do not inflate the pool with weak links just to increase the count.

## Fit scoring
Every retained candidate stores all six components; `fit_score` is their arithmetic sum:
- `skill_30` — direct existing-skill overlap: max 30.
- `transition_20` — realistic learnability/gap: max 20.
- `compensation_15` — published pay or defensible target likelihood: max 15.
- `access_15` — practical Baku hiring access: max 15.
- `lifestyle_10` — workload/hours/remote/commute fit: max 10.
- `upside_10` — career ceiling, skill growth, stability, salary upside: max 10.

`interview_chance` is separate from fit score.

## Application priority
- `A` — strongest candidate; inspect/apply early if live and critical unknowns pass.
- `B` — good candidate.
- `C` — stretch/upside.
- `WATCH` — interesting but blocked by serious access/fit/freshness issue.

## Compensation labels
- `PUBLISHED` — job/employer states it.
- `CANDIDATE_ASK` — candidate is asked for expected compensation.
- `ESTIMATED` — sourced external benchmark, never employer salary.
- `UNKNOWN` — no defensible figure.

## Search breadth
Do not limit to AP. Search CORE, ADJACENT and STRETCH across finance operations, P2P/AR/O2C, SAP/ERP/MDG, master data, procurement, reporting/data, process improvement, project/operations coordination, inventory/supply chain, finance systems, B2B customer/sales operations and other credible transferable-skill roles.

## Interface maintenance
After every run:
1. Update `CANDIDATES.csv` first; deduplicate by company/title/link.
2. Update `VACANCIES.csv` only when user-browser confirmation exists.
3. Update `REJECTED.csv` for known closed/expired/inaccessible/conflicted/clearly under-target items.
4. Update `DASHBOARD.md` with total candidate count, browser-confirmed count, clickable links, score, salary, access and verification level.
5. Update `STATUS.md` with true absolute candidate count and next action.
6. Never protect a counter at the expense of candidate quality.

## Completion condition
Only an **explicit user stop instruction** ends autonomous search expansion. Do not stop at any numeric count.
