# Codex — Wave 4 Human proposal

**Target transition:** S4=— -> S4=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

[roadmap.md](roadmap.md) is the canonical proposal receipt; [constructor-sufficiency.md](constructor-sufficiency.md) is the AI/source-native contract. This is internal PLAN_ONLY research, not implementation, product direction or an Index regrade.

## Accepted baseline and current Codex

Historical Index [included assessment](https://github.com/opensiro/vsm-harness-index/blob/8f436270813b844aafc16917d69bc09661ef1544/assessments/co/codex.md) reviewed 2026-09-17 (blob 60c8459fdf05904f9ed29f552816ace9486e8410, Profile 0.2.1, Skills 0.3.1) and new [original HEAD](https://github.com/openai/codex/commit/bb5b9c6240136de8ff4d30215e2341c44559aa04) are distinct.

| Function / role | Historical Index state | Current source-backed owner/closure | Priority / candidate |
| --- | --- | --- | --- |
| **S1 · Operations** | A | Local coding agent executes tools and responds to results ([core](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/core/src/session/mod.rs)) | NO_TARGET |
| **S2 · Peer coordination** | — | Worker communication and task assignment exist; dedicated peer interference regulation unverified ([multi-agent tools](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/core/src/tools/handlers/multi_agents_spec.rs)) | DEFER |
| **S3 · Current regulation** | C | Optional root can inspect and intervene in live worker tree ([tools](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/core/src/tools/handlers/multi_agents_spec.rs)) | NO_TARGET |
| **S3* · Audit** | C | Optional Guardian separately reviews and blocks selected risky actions ([review](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/ext/guardian-reviewer/src/routing.rs)) | NO_TARGET |
| **S4 · Future environment** | — | Catalog refresh and user migration prompts are reactive, with no autonomous future-options/next-turn-return chain ([refresh](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/app-server/src/models_refresh_worker.rs)) | P0 prospective S4 proposal |
| **S5 · Identity and policy** | — | User/host retains model selection, provider credentials and policies ([config](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/protocol/src/config_types.rs)) | NO_TARGET, parent owns policy |

## Proposed optional capability

A developer-composed, provider-scoped future-model advisor could inspect dated external model-retirement or capability notices, autonomously choose a permissible future strategy (retain, prepare-approved-migration or hold), request an approved change from the existing host/S3 for the next turn, then observe that next model choice and actual later run results. Human/host authority is preserved; silent model/provider/cost changes are forbidden. This is not an instruction that Codex ought to build it.

**Track A:** current [catalog](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/models-manager/src/manager.rs), [polling](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/app-server/src/models_refresh_worker.rs), [TUI migration](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/tui/src/model_migration.rs) and [next-turn settings](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/core/src/session/model_catalog_settings.rs); merged original [#47932](https://github.com/openai/codex/pull/47932) and [#50013](https://github.com/openai/codex/pull/50013). Capacity-recovery [issue #55983](https://github.com/openai/codex/issues/55983) is a separate current-task need.

**Track B:** P0 minimum future S4 decision + lawful host proposal/ack + actual later feedback. P1 source notice validation, user/developer allowlist, idempotence, supported next-turn-only effect and native positive/negative tests. P2 optional analytics. A digest alone or a reactive picker is NOT complete C.

## Comparison and stop gates

[Independent first pass](https://github.com/opensiro/upstream/issues/58#issuecomment-7043626535) was sealed before comparison. [Historical case](https://github.com/opensiro-contributions/codex/blob/a97563d594f23023a6104773ff4f2a3ba0c1e48b/.opensiro/issues/model-lifecycle-s4-20261118/roadmap.md) was NO_GO / NO_USEFUL_CHANGE when unmeasured product usefulness and absent explicit model-choice rights were treated as vetoes. Neutral v0.18.0 separates possible bounded C construction from product adoption. New proposal GO / NEEDS_EVIDENCE is hypothetical; no native tests or cost measurement. The original [contributing policy](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/docs/contributing.md) rejects external code PRs; original/public fork publication NOT_PUBLISHED. Original maintainers retain the decision to adopt or reject.
