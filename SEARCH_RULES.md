# Search Rules

## Acceptance threshold
An opportunity may count toward 100 only if it is realistically worth applying to **and its current availability is verified through a live exact application route in the same run**.

Minimum economic target: 2,500 AZN net/month equivalent. Prefer 3,000–5,000+ AZN or strong upside. If compensation is unpublished, a strong role may remain qualified only when employer/role seniority plausibly supports the target; compensation stays `Unknown` and must be checked before application.

## Hiring accessibility
Record one of:
- `LOCAL_AZ` — Baku/Azerbaijan employment.
- `REMOTE_AZ_EXPLICIT` — remote listing explicitly includes Baku/Azerbaijan/CIS including Baku.
- `REMOTE_WORLDWIDE` — explicit worldwide/global remote.
- `CONTRACTOR_PLAUSIBLE` — legal contractor/B2B/EOR route is plausible and not prohibited.
- `RELOCATION` — worthwhile relocation/visa route.
- `UNCLEAR` — cannot count as accepted until resolved.

Never evade employment, tax, immigration, KYC, sanctions, geo-restrictions or platform rules.

## Verification — strict freshness rule
Search engines, LinkedIn snippets, aggregators and cached page text are discovery sources only. They are not enough by themselves to count a vacancy toward 100.

Before `QUALIFIED`, verify in the same run:
1. Exact employer careers page or employer-controlled ATS is live and contains the exact role; or, where the employer genuinely recruits through a named third-party platform, an exact live application page is clearly current.
2. Apply route is open or page explicitly accepts applications.
3. Location/work model and hiring accessibility fit the candidate.

Employer source overrides aggregators. If exact live route cannot be established, store the lead in `REJECTED.csv` as `WATCH`, `STATUS_CONFLICT`, `UNVERIFIED`, or similar and do not count it.

Freshness labels used in the dashboard:
- `LIVE_EMPLOYER` — exact employer careers page verified.
- `LIVE_ATS` — exact employer-controlled ATS verified.
- `LIVE_THIRD_PARTY_APPLY` — exact current application on a named third-party platform where no better employer route was established.
- `UNVERIFIED` / `UNVERIFIED_ATS` / `STATUS_CONFLICT` — does not count.
- `EXPIRED` / `CLOSED` — does not count.

## Fit scoring — transparent arithmetic
Every accepted vacancy must store all six components. `fit_score` must equal their arithmetic sum — no unexplained holistic score.

- `skill_30` — direct overlap with existing skills and experience: max 30.
- `transition_20` — realistic gap / learnability without pretending missing experience exists: max 20.
- `compensation_15` — published pay or defensible likelihood of meeting target: max 15.
- `access_15` — practical hiring accessibility from Baku: max 15.
- `lifestyle_10` — workload, hours, pressure, commute/remote fit: max 10.
- `upside_10` — career ceiling, skill growth, stability and future salary potential: max 10.

Guide:
- 85–100: priority application.
- 75–84: strong candidate.
- 65–74: plausible stretch; keep only with meaningful upside.
- <65: reject unless there is a specific strategic reason.

`interview_chance` is tracked separately and is **not** part of fit score. A great fit can still have low interview probability due to competition, title mismatch, language, missing formal experience or applicant volume.

`application_priority`:
- `A` — apply early if salary/critical unknowns pass.
- `B` — good application after higher priorities.
- `C` — stretch/upside application.
- `WATCH` — not counted until freshness/access/pay issue is resolved.

## Compensation
Salary status:
- `PUBLISHED` — employer/job page states it.
- `CANDIDATE_ASK` — applicant is asked to state desired compensation.
- `ESTIMATED` — externally benchmarked estimate, never presented as employer salary.
- `UNKNOWN` — no defensible figure yet.

Never invent precision. Any market estimate must be explicitly labelled and sourced.

## Freshness
Store discovery and last verification dates. Re-check every accepted role immediately before CV tailoring/application. Closed/expired jobs move to rejected history rather than disappearing.

## Search mix target
Across 100 accepted opportunities aim roughly for:
- 40–50 CORE.
- 30–40 ADJACENT.
- 10–20 STRETCH.
Do not force quotas if the market does not support them.

## Interface maintenance
After every run:
1. Update `VACANCIES.csv` and `REJECTED.csv`.
2. Update `DASHBOARD.md` so the user can see scores, salary, freshness, access, interview chance, links, gaps and next action without reading CSV.
3. Update `STATUS.md` with the true accepted count and exact next action.
