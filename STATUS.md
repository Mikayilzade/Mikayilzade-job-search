# Job Search Status

## Current state
- Phase: **SEARCH ACTIVE / OPEN-ENDED EXPANSION**.
- Last completed run: **Autonomous Run #51 — 2026-08-22 around 12:00 AZT**.
- **Candidate pool: 350 unique total.**
- **Browser-confirmed live subset: 7.**
- User-facing interface: `DASHBOARD.md`.
- Historical master candidates remain in `CANDIDATES.csv`; additive candidate ledgers continue through `CANDIDATES_RUN51.csv`.
- Rejected history is in `REJECTED.csv` plus additive ledgers through `REJECTED_RUN51.csv`.
- Repository remains the sole persistent source of truth.
- Counter reconciliation: candidate IDs reach `C351`, but historical `C158` is absent, so the true unique count is 350.

## User override
Continue open-ended search and add new high-quality options until the user explicitly stops the process. The former 100-candidate cap is retired.

## Latest run result
Added **6** new candidates, C346–C351:
1. **Airswift — Project Requisitioner (Nationals Only) — C346 — 87 — Priority A / STATUS_CONFLICT.** Airswift's current Baku vacancy index lists a permanent Baku role dated 11 Aug 2026, while the linked exact detail page still carries older Sep 2025 metadata. Supplier payments, SAP data entry, purchasing procedures and project-document support fit exceptionally well, but browser freshness must be rechecked and the role requests 3+ years similar experience plus fluent English.
2. **Azerconnect Group — Junior SCM Support Analyst — C347 — 87 — Priority A.** Current copies show deadline **27–28 Aug** and hybrid office/home work. ERP Procurement/SCM requirements, issue resolution, module testing, functional documentation and end-user support are an unusually strong bridge from SAP S/4/MDG/P2P work. Oracle Fusion/EBS configuration/OUM are the main gaps; junior title creates compensation risk.
3. **Qafqaz NET LLC — Mühasib — C348 — 84 — Priority A.** Current copies show deadline around **2–3 Sep**. Daily accounting, incoming e-invoices, 1C posting, payments and document-flow coordination with procurement/sales/warehouse map closely to finance operations. Local 1C/e-invoice practice is the main gap; compensation is unpublished.
4. **IRES — Procurement Specialist — C349 — 81 — Priority B.** Deadline **13 Sep**. PR-to-PO processing, supplier/commercial-document comparison, payment terms, contracts and Finance coordination transfer strongly; sourcing, tender evaluation, negotiation, logistics/customs and 1C procurement are real gaps.
5. **SOCAR Upstream MI LLC — Procurement & Supply Chief Specialist — C350 — 77 — Priority B.** Fresh August listing, salary by agreement. ERP/Excel, supplier coordination and process discipline transfer, but annual procurement planning, strategy, market research and direct procurement ownership make this a meaningful stretch.
6. **Chirag Plaza — Mühasib — C351 — 77 — Priority B.** Deadline **7 Sep**, salary by agreement. Debtor/creditor accounting, bank payments, invoices/contracts/acceptance acts and reconciliations fit well; local tax/statutory reporting and a six-day schedule reduce attractiveness.

## Screened out this run
- **Caspian Cable Systems — Əməliyyatçı mühasib:** fresh current copy is functionally strong, but explicitly lists age 21–25; repository profile does not establish eligibility for that access criterion, and local tax/statutory scope is material. Recorded as WATCH_ACCESS in `REJECTED_RUN51.csv`.
- **New Look Consultancy — Mühasib köməkçisi:** 700 AZN and female-only application criterion; rejected.
- **Akabe İnşaat — Mühasib:** matching current copy publishes 1,000 AZN; rejected on economics.
- Marriott Baku accounting search snapshots were not added because current employer-search evidence was internally inconsistent across crawl versions; wait for a stable current exact requisition rather than padding the pool.

## Browser-confirmed live subset
1. **Xsolla — Finance Coordinator — 86**.
2. **Unibank — Financial Efficiency Lead/Chief Specialist — 79**.
3. **OBA — Maliyyə üzrə Analtik (Logistika üzrə) — 79**.
4. **Xsolla — Delivery Manager, Self-Service — 74** — remote/Baku — USD 30k–80k/year published.
5. **Tabaterra — Aparıcı mühasib — 74** — user-found exact HRX link; deadline 18 Sep.
6. **OBA — BI & SQL Reporting Specialist (Lead) — 72 practical re-review**.
7. **Bolt — Operations Manager — 71**.

## NEXT ACTION
1. Continue fresh search with emphasis on **direct AP/AR/controller, SAP/ERP functional support, payment/settlement operations, contract/commercial administration and P2P/procurement analytics**.
2. Re-check **Airswift Project Requisitioner** exact freshness first because current employer index and exact-page metadata conflict.
3. Prioritize employer career pages and current JobSearch/HRX/Glorri/SmartJob/Banco feeds; reject stale crawl-only vacancies when exact current evidence conflicts.
4. Search Azerbaijan-eligible international finance operations / ERP / payment roles with published compensation where possible; lawful worldwide contractor/EOR/relocation only.
5. Keep compensation filtering strict; junior/local accounting roles with clearly sub-target pay should go directly to rejected history.
6. Preserve browser verification separation: `VACANCIES.csv` changes only on user/browser-confirmed exact live evidence.
7. Treat Oracle configuration/OUM, direct strategic procurement, local tax/statutory ownership, SQL/BI, FP&A/budgeting, formal audit/risk/compliance and fluent/native-language requirements as real gaps unless demonstrated otherwise.
8. Continue until an explicit user stop instruction is recorded.
