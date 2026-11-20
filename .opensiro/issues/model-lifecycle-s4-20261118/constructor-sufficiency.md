# Codex — Wave 4 AI constructor sufficiency

**Target transition:** S4=— -> S4=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

Canonical [roadmap.md](roadmap.md) and [issue.md](issue.md) own the historical six-function table and source pins. First pass [sealed before historical review](https://github.com/opensiro/upstream/issues/58#issuecomment-7043626535); original pinned [commit](https://github.com/openai/codex/commit/bb5b9c6240136de8ff4d30215e2341c44559aa04). This is NOT a shipped or tested constructor and does not change Index.

## Function-specific Track A and Track B

| C-sufficiency link | First-party Track A | Independent Track B minimal next link | Falsifier |
| --- | --- | --- | --- |
| Environmental future input | [ModelsManager](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/models-manager/src/manager.rs) has online/cache/provider-scoped catalog | dated externally attributable future model retirement/capability notice with origin and expiry | current catalog only or stale alert |
| Autonomous strategy choice | [Migration UI](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/tui/src/model_migration.rs) obtains user acceptance | optional first-party model-transition advisor chooses retain / prepare-approved-migration / hold against approved eligible set, records rationale | no distinct advisor choice or always auto-switch |
| S4-to-S3 authorized action | [Session settings](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/core/src/session/model_catalog_settings.rs) change only at next turn | typed proposal to host/S3, accept/deny/defer feedback, apply next-turn-only under policy | direct current-turn change, no authorized port |
| S3-to-S4 later return | host can read chosen model and operational outcome | correlate proposal ID, applied/denied choice and subsequent model/run result; update future options | one-way digest or missing actual later feedback |

Track A also includes [4m30s catalog refresh](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/app-server/src/models_refresh_worker.rs), [provider-scoped deprecation prompts](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/tui/src/app/startup_prompts.rs), merged original [PR #47932](https://github.com/openai/codex/pull/47932) and [PR #50013](https://github.com/openai/codex/pull/50013). [Issue #55983](https://github.com/openai/codex/issues/55983) concerns recovery from temporary capacity failure, not independent prospective S4 ownership. First-party optional root-worker and Guardian ([routing](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/ext/guardian-reviewer/src/routing.rs)) do not supply S4 by themselves.

## Proposed source-native C witness

Scenario HYPOTHETICAL: a future dated vendor sunset notice predicts reduced availability before failure. Developer opts into a bounded advisory provider+model allowlist. Advisor assesses competing future choices and publishes a typed, expiring proposal to existing host/S3. S3 applies only an already-authorized next-turn configuration or rejects it, returning an attributed response. Later operational/model outcome flows back to advisor to revise its subsequent choice. User/host S5 rights and current-running-step model remain untouched. This complete path is **PROPOSED_C_SUFFICIENT IF IMPLEMENTED AND VALIDATED**, not evidence of a current C.

## P0 / P1 / P2 and native acceptance

P0: smallest optional independent future S4 actor with lawful next-turn host proposal/ack and observed later run return. P1: provider notice provenance, expiry, authorization, blocked unaffordable/unavailable model, duplicate prevention, denial feedback and native tests. P2: optional measured cost/quality comparisons.

Positive: independently select from at least two valid future options on a dated vendor notice; S3 approves, next turn actually changes within approved configuration, later result returns and changes future strategy. Negative: stale/unsigned notice, unauthorized provider/model/cost, no permission, same-running-turn change, denied proposal, duplicate and missing effect/feedback must NOT be passed as C. Contrast with native catalog + picker; compare actual original-native regression results before implementation conclusions.

**Stop/falsify:** equivalent shipped first-party prospective S4 ownership/effect/return; no lawful host/S3 new port; pure user-only prompt or alert; or impossible feedback. Absence of measured product adoption value does not prove architectural impossibility. Native tests NOT_RUN, cost NOT_MEASURED; original [docs/contributing.md](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/docs/contributing.md) forbids external code PRs. No external/public fork Issue or PR was published.
