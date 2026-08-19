# Search Rules

## Acceptance threshold
An opportunity may be added to `VACANCIES.csv` only if it is realistically worth applying to **and its current availability is verified through a live exact application route in the same run**.

Minimum economic target: 2,500 AZN net/month equivalent. If compensation is unpublished, keep a strong opportunity only when employer/role seniority plausibly supports the target; mark compensation confidence `LOW` and flag salary verification as mandatory.

## Hiring accessibility
Record one of:
- `LOCAL_AZ` — Baku/Azerbaijan employment; no foreign-hire issue.
- `REMOTE_AZ_EXPLICIT` — remote listing explicitly includes Baku/Azerbaijan/CIS including Baku.
- `REMOTE_WORLDWIDE` — employer explicitly allows worldwide/global remote.
- `CONTRACTOR_PLAUSIBLE` — direct employment unclear, but legal contractor/B2B/EOR route is plausible and not prohibited.
- `RELOCATION` — worthwhile only with relocation/visa route.
- `UNCLEAR` — cannot count as accepted until resolved.

Never suggest evading employment, tax, immigration, KYC, sanctions, geo-restrictions, or platform rules.

## Verification — strict freshness rule
Search engines, LinkedIn snippets, aggregators and cached page text are **discovery sources only**. They are never sufficient by themselves to count a vacancy toward 100.

Before a vacancy counts as `QUALIFIED`, verify in the same run:
1. An exact employer careers page or employer-controlled ATS page is live and contains the exact role; or, where the employer genuinely recruits only through a named third-party platform, an exact live application page is available and clearly current.
2. The apply route is still open or the page explicitly states the vacancy is accepting applications.
3. Location/work model and hiring accessibility are consistent with the candidate's situation.

If the live employer page disagrees with a search result, the live employer page always wins. If an exact live application route cannot be established, place the lead in `REJECTED.csv` as `WATCH`, `STATUS_CONFLICT`, or `UNVERIFIED` and do not count it toward 100.

A listing being newly indexed, labelled `Actively Hiring`, or showing a recent date on LinkedIn/search is **not proof of current availability**.

## Fit scoring (0–100)
Score holistically:
- 30: direct skill overlap.
- 20: realistic transition gap / learnability.
- 15: compensation likelihood.
- 15: hiring accessibility from Baku.
- 10: workload/lifestyle fit.
- 10: career upside/stability.

Guide:
- 85–100: priority application.
- 75–84: strong candidate.
- 65–74: plausible stretch; keep only with meaningful upside.
- <65: reject unless there is a very specific strategic reason.

## Compensation
Use published salary when available. Otherwise use `Unknown` and confidence, not invented precision. Market estimates must be labeled as estimates and sourced when later used for application decisions.

## Freshness
Store `discovered_at` and `last_verified_at`. Re-check accepted jobs before CV tailoring/application. Expired/filled jobs move to rejected/closed history rather than being silently deleted.

Any accepted vacancy discovered under an older/weaker freshness rule must be re-audited under the strict live-application rule before final application prioritization.

## Search mix target
Across 100 accepted opportunities aim roughly for:
- 40–50 CORE.
- 30–40 ADJACENT.
- 10–20 STRETCH.
Do not force quotas if the market does not support them.
