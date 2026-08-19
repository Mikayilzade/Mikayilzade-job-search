# Search Rules

## Acceptance threshold
An opportunity may be added to `VACANCIES.csv` only if it is active or has a defensible active application route and is realistically worth applying to.

Minimum economic target: 2,500 AZN net/month equivalent. If compensation is unpublished, keep a strong opportunity only when employer/role seniority plausibly supports the target; mark compensation confidence `LOW` and flag salary verification as mandatory.

## Hiring accessibility
Record one of:
- `LOCAL_AZ` — Baku/Azerbaijan employment; no foreign-hire issue.
- `REMOTE_AZ_EXPLICIT` — remote listing explicitly includes Baku/Azerbaijan/CIS including Baku.
- `REMOTE_WORLDWIDE` — employer explicitly allows worldwide/global remote.
- `CONTRACTOR_PLAUSIBLE` — direct employment unclear, but legal contractor/B2B/EOR route is plausible and not prohibited.
- `RELOCATION` — worthwhile only with relocation/visa route.
- `UNCLEAR` — cannot count as accepted until resolved, unless exceptionally strong and explicitly marked provisional.

Never suggest evading employment, tax, immigration, KYC, sanctions, geo-restrictions, or platform rules.

## Verification
Prefer employer career pages. Job boards can establish discovery/currentness but should be cross-checked when practical. Conflicting deadlines/statuses go to `REJECTED.csv` or remain provisional until resolved.

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

## Search mix target
Across 100 accepted opportunities aim roughly for:
- 40–50 CORE.
- 30–40 ADJACENT.
- 10–20 STRETCH.
Do not force quotas if the market does not support them.
