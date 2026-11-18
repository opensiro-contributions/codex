# Codex model-lifecycle S4: evidence and falsification contract

PLAN_ONLY. **Final operator decision: NO_GO** for the proposed autonomous S4 constructor.
[Human decision](https://github.com/opensiro-contributions/codex/blob/opensiro/meta/.opensiro/issues/model-lifecycle-s4-20261118/issue.md) · [receipt](https://github.com/opensiro-contributions/codex/blob/opensiro/meta/.opensiro/issues/model-lifecycle-s4-20261118/roadmap.md).

## 1. Boundary and baseline

Exact original: openai/codex at `58ad62ce09dd7da5531cecb15fd69a21aa465332`, observed 2026-11-18. System in focus: public first-party CLI/TUI/app-server runtime, provider/catalog interfaces and optional team/review paths. Closed-source desktop/IDE implementation, provider-side model strategy, OpenAI corporate governance, arbitrary user-built agents and repository-development agents are outside the credited ownership boundary.

Historical accepted vector: **A — C C — —** in S1/S2/S3/S3*/S4/S5 order. [Index](https://github.com/opensiro/vsm-harness-index/blob/34e11ec4dd52e1ba3ee0111d8bca73f13918f54f/assessments/co/codex.md), blob `60c8459fdf05904f9ed29f552816ace9486e8410`; review source `b974893c90048d147207ae9004489c02f3116426`; 2026-09-17; Profile 0.2.1 / Methodology 0.3.1. Age 62 days. Reassessment advisory only; no current S4 grade is assigned.

Origin: ASSESSMENT_INFORMED as a narrative description. The Index was consulted before this source investigation, but no independent immutable pre-source prediction establishes ASSESSMENT_DERIVED. No contribution record is created for this plan.

## 2. Shipped versus proposed evidence

| Element | Exact first-party source / inspected behavior | Reuse or gap |
| --- | --- | --- |
| Provider/auth-scoped catalogs | [thread catalog](https://github.com/openai/codex/blob/58ad62ce09dd7da5531cecb15fd69a21aa465332/codex-rs/core/src/thread_manager/model_catalog.rs); [manager](https://github.com/openai/codex/blob/58ad62ce09dd7da5531cecb15fd69a21aa465332/codex-rs/models-manager/src/manager.rs) | Reuses catalog factory, current provider identity, refresh policy and current successful response; discovery is not the strategic decision |
| Saved-model retirement | [startup prompts](https://github.com/openai/codex/blob/58ad62ce09dd7da5531cecb15fd69a21aa465332/codex-rs/tui/src/app/startup_prompts.rs), model_upgrade_for_migration / should_show_model_migration_prompt | Catalog metadata has precedence; retired-slug fallback is provider-scoped; unavailable or hidden target is skipped |
| Decision and application | Same source, handle_model_migration_prompt_if_needed / apply_accepted_model_migration; [prompt](https://github.com/openai/codex/blob/58ad62ce09dd7da5531cecb15fd69a21aa465332/codex-rs/tui/src/model_migration.rs) | User accepts/rejects/exits where applicable; acceptance changes launch/config model and effort and emits selection/persistence events. This is not a developer-composed autonomous S4 actor |
| Later execution recovery | [compaction fallback](https://github.com/openai/codex/blob/58ad62ce09dd7da5531cecb15fd69a21aa465332/codex-rs/core/src/compact_model_fallback.rs) | Reactive retry uses already-selected current model within provider/auth and terminal-error guards. It is not future-option development |
| Native tests | [model catalog tests](https://github.com/openai/codex/blob/58ad62ce09dd7da5531cecb15fd69a21aa465332/codex-rs/tui/src/app/tests/model_catalog.rs) | Source cases cover catalog refresh, retired metadata precedence, accepted model/effort persistence, hidden/missing targets, acknowledgements and stale choices. Inspected, NOT RUN |
| Current user reports | [#25440](https://github.com/openai/codex/issues/25440), [#57321](https://github.com/openai/codex/issues/57321) | Compatibility/indexing reports remain open. Neither report verifies the proposed strategic controller's material delta |

PR overlap pins:
- #44250 MERGED, head/merge `eb7bd64ef935cedb6a2c90c77c78d6677f1efb45`; diff specifically adds retired-selection migration and persistence/target tests.
- #29942 MERGED, head `5e04cde54eaaa34e476cd025516ce89752f039b9`, merge `6d9dbacf1af69fc9b633132e34d63be202556a24`; diff threads opt-in provider fallback through thread start and static model selection.
- #46324 MERGED, head/merge `5492c2b06e9d3e1c09cf65e5923930a6b57b4e9e`; diff broadens retry and adds a native compaction regression. Current source adds further guards, so the old diff is not today's complete behavior.
- #57337 OPEN DRAFT, head `9f7a233df849c5415cbde8eb7d4413e93da66a6c`, base `b6e65bfc05994fda9900bc6dfaeac2caf654eafe`; inspected provider/catalog/backport diff. No autonomous strategy port is supplied. It is not credited as shipped.

Search census: exact-title model migration and model fallback PR searches across states; model migration/deprecated issues; 6 open model-title PRs inspected at title/body level, with the release backport diff read because it plausibly overlaps. This bounded census is not an exhaustive full-repository proof of absence. No matching prior fork case/ref or fork roadmap Issue was found before initialization.

## 3. Function owner and candidate construction path

Prospective S4 requires external/future distinctions, developed alternatives and two-way operational coupling, per [Profile section 9](https://github.com/opensiro/vsm-harness-profile/blob/12c23de53b039bc01fba92c9f837498b0cb1e6f3/PROFILE.md#9-system-4--outside-and-then-intelligence). Current-task retries and catalog transport alone do not meet that function.

Investigated actor/task/output: a deployment developer binds an autonomous actor; upcoming provider retirement triggers evaluation; it chooses a lawful model alternative or hold; a later eligible Codex operation uses the chosen configuration and returns actual outcome to the owner of current commitments.

The following is a **rejected candidate analysis**, not an API specification or implementation backlog:

| Required link | Existing support | Missing or unqualified evidence |
| --- | --- | --- |
| Future disturbance | Provider catalog metadata and migration/retirement data | No demanded deployment-specific prospective strategy case beyond current migration/recovery |
| Alternatives and versioned state | Available model presets, provider identity, target validation | No qualified need for a separate strategy option store |
| Decisive actor/right | Operator migration choice; existing configured model-selection rules | No established first-party developer-composed autonomous S4 decision owner |
| Authorized operation | Startup choices, config/selection events, supported thread model controls | A new actor cannot acquire provider credentials, override explicit pins, alter Guardian/host permissions or cross provider/auth scopes |
| Returned operational feedback | Model selection state; reactive compaction outcome telemetry | No verified strategic decision-to-later-task-result correlation; persistence is not proof of successful inference |

**Constructor sufficiency: NOT ESTABLISHED.** The full path is not supplied by a generic hook. Creating all five components would still not justify doing so without a material operator counterfactual. No present C or P S4 claim follows from human model selection.

## 4. Priority and complete target matrix

| Function | Accepted historical state | Current evidence used / target decision |
| --- | --- | --- |
| S1 | A | Existing operational loop, no C conversion targeted |
| S2 | — | Outside selected S4 investigation; no new collision hypothesis established |
| S3 | C | Existing current-control construction path remains a historical baseline; no replacement manager |
| S3* | C | Preserve configured reviewer/host authority; no extra reviewer |
| S4 | — | P0 candidate rejected: useful additional C outcome not established |
| S5 | — | Host/user governing decisions remain reserved; no policy transfer |

**P0: REJECTED NOW. P1: NONE admitted for implementation. P2: NONE.** A native repair could be separately investigated from #25440 or #57321 but is not relabeled an S4 upgrade. Existing A/C states do not require further C engineering.

## 5. Native comparison and conditional reopening

These repository-specific cases are **proposed future comparisons, NOT RUN**, and are not authorization to implement:

| Comparison | Observable native baseline | Evidence needed to reopen S4 |
| --- | --- | --- |
| Retired saved selection, visible supported replacement | model_upgrade_for_migration, target checks, accepted_model_migration_persists_target_default_reasoning_effort | A real future-capability choice not already met by operator migration; verify subsequent task model and continuity |
| Operator keeps supported current model / acknowledges prompt | selecting_use_existing_model_rejects_upgrade and acknowledgement tests | Lawful alternative decisions must change later operation without overriding the operator |
| Target unavailable/hidden or provider/auth changes | model_migration_prompt_skips_when_target_missing_or_hidden; queued_model_choice_expires_when_the_default_provider_changes | A proposed actor must fail closed on scope/availability change and provide truthful rejection |
| Previous-model compaction failure after a valid switch | Current compact_model_fallback guards and native compaction tests | Actual success/failure returned to current management; no claim of strategic learning from retry alone |
| Migrated thread missing from IDE history | #57321 reports continued conversation but failed listing | Reproduce and repair the owning history surface; an S4 wrapper must not be treated as fixing it |

Native test commands are deferred until a concrete repair/implementation is selected and its current repository instructions are read. No made-up executed command or passing behavior is reported. This PLAN_ONLY no-change decision does not require model calls or a Rust build.

## 6. Rights, cost and terminal contract

Apache-2.0 conditions apply to derivatives; current docs/contributing.md permits issue analysis and rejects external code PRs. docs/CLA.md exists but no personal attestation has been supplied or signed. No maintainer policy or CI approval is inferred. Only bounded internal research metadata is prepared; initial PAUSE/DORMANT is a restrictive bootstrap, not a human authorization grant. Later mutation must respect that state.

Paired task: same retirement, account/provider, saved session and expected continuity. Compare native migration plus narrow repair against any future S4 composition using total engineering/review/test/support effort and real later-task outcomes. **Cost: NOT_MEASURED.** No performance or savings result.

**Final operator decision: NO_GO.** Do not build the speculative S4 constructor now. Reopen only on first-party evidence of a materially different prospective user task, a simpler-native-baseline failure, legitimate composable actor rights, a supported distribution route and verifiable feedback. The present decision is complete, not NEEDS_EVIDENCE awaiting another continuation.

No public Issue/PR/comment, product change, Index edit or independent human validation is claimed. [Human backlink](https://github.com/opensiro-contributions/codex/blob/opensiro/meta/.opensiro/issues/model-lifecycle-s4-20261118/issue.md).
