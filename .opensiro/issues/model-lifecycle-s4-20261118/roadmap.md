# Capability Roadmap Receipt: Codex model lifecycle

## Identity and pins

- Original repository: openai/codex
- Original HEAD: 58ad62ce09dd7da5531cecb15fd69a21aa465332
- Observed at: 2026-11-18
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/34e11ec4dd52e1ba3ee0111d8bca73f13918f54f/assessments/co/codex.md
- Accepted assessment blob SHA: 60c8459fdf05904f9ed29f552816ace9486e8410
- Accepted review ref: b974893c90048d147207ae9004489c02f3116426
- Accepted reviewed at: 2026-09-17
- System in focus: public first-party Codex CLI/TUI/app-server runtime and its supplied provider/catalog, team and approval-review surfaces, one coding-agent organization
- Accepted Index commit: 34e11ec4dd52e1ba3ee0111d8bca73f13918f54f
- Catalog blob SHA: e0d5579bea2b200aa08ef4497cc1ab735252349a
- Historical Profile / Methodology: 0.2.1 / 0.3.1
- Accepted vector: A — C C — —
- Last successful semantic review/check: 2026-09-17, age 62 days
- Result: NO_USEFUL_CHANGE
- Final operator decision: NO_GO
- External issue: DRAFT — NOT PUBLISHED
- Cost status: NOT_MEASURED

Catalog exact identity: harness_id codex; https://github.com/openai/codex; review_ref b974893c90048d147207ae9004489c02f3116426. The original Git commit endpoint resolves that revision. Accepted assessment status is included, not proposed; catalog and RANKINGS blob readback at the pinned commit matched the selection inputs. Original current HEAD is separate from the historical review ref. Recommend Index-owned source-pinned reassessment because the last successful semantic review is over 30 days old; no such reassessment is performed or presumed accepted here.

Excluded ownership: closed-source desktop/IDE internals, model-provider strategy, corporate governance, custom external controllers and repository-development actors. Issue reports about the IDE are user-need evidence, not proof that its implementation is public or that this runtime owns the defect.

[Human](https://github.com/opensiro-contributions/codex/blob/opensiro/meta/.opensiro/issues/model-lifecycle-s4-20261118/issue.md) and [AI/developer contract](https://github.com/opensiro-contributions/codex/blob/opensiro/meta/.opensiro/issues/model-lifecycle-s4-20261118/constructor-sufficiency.md) repeat NO_GO, the historical vector and priorities.

## Rights and authority

Verified public working fork opensiro-contributions/codex: fork=true, parent/source openai/codex, connector push permission true. Default branch main pin 6bd17ba6ae6ca2788026bd789f28f38b754d7379, tree cab582a63dde7c38813dbddc1ed641a8b72db39f. opensiro/meta was confirmed absent through matching refs, and no fork roadmap Issue was found. Initialize metadata from that pinned fork default, with restrictive PAUSE/DORMANT defaults. This is a bounded initial research materialization, not an invented ALLOW, human PAUSE instruction or permission for later effectful work. Recheck for collisions immediately before branch creation.

[Apache-2.0 license](https://github.com/openai/codex/blob/58ad62ce09dd7da5531cecb15fd69a21aa465332/LICENSE), blob 4606e72e042564097e8780d66c1d4dcb611869bd, read in full. [Contribution policy](https://github.com/openai/codex/blob/58ad62ce09dd7da5531cecb15fd69a21aa465332/docs/contributing.md) allows issue reports/analysis and prohibits external code contributions/PRs. A CLA document exists; no personal signature, human technical review, AI-policy clearance beyond inspected sources or maintainer acceptance is claimed.

The user command authorizes plan-only internal case preparation. Separate exact current-conversation consent for any public fork Issue or third-party action was not supplied. No such action is taken.

## Existing work / overlap

Original source and exact PR metadata/diffs read through connected GitHub:
- #44250 MERGED, head/merge eb7bd64ef935cedb6a2c90c77c78d6677f1efb45; retired saved model handling and migration/persistence tests. Its historical diff is not substituted for current source.
- #29942 MERGED, head 5e04cde54eaaa34e476cd025516ce89752f039b9, merge 6d9dbacf1af69fc9b633132e34d63be202556a24; opt-in provider-aware static-catalog fallback.
- #46324 MERGED, head/merge 5492c2b06e9d3e1c09cf65e5923930a6b57b4e9e; compaction recovery. Current main has narrower terminal/provider/auth guards.
- #57337 OPEN DRAFT, head 9f7a233df849c5415cbde8eb7d4413e93da66a6c, base b6e65bfc05994fda9900bc6dfaeac2caf654eafe; catalog release backport, not shipped solely by being proposed.
- #25440 and #57321 OPEN; full issue bodies/comments inspected. Reported config/auth incompatibility and migrated-thread history defects are not independently reproduced. No maintainer request for a new autonomous strategy owner was found in these discussions.

PR metadata, head/base and relevant diffs were checked, not just titles. The technical companion links current native implementation and explains residual tasks. No modification to another author's branch.

## Function ownership

[Profile S4 semantics](https://github.com/opensiro/vsm-harness-profile/blob/12c23de53b039bc01fba92c9f837498b0cb1e6f3/PROFILE.md#9-system-4--outside-and-then-intelligence) require external/prospective distinctions, options and S3 coupling. Catalog refresh is sensing/transport; startup migration gives the user a choice and applies accepted selection; compaction fallback is current recovery. These facts do not prove a first-party developer-composable S4 actor.

Current source witnesses:
- startup_prompts.rs blob 71cc1a0bde6894d7494e9163d6e9fd79f2f1ec69
- models-manager manager.rs blob cdc890e54065d616f0bd723ea8abd93c2d15b768
- models-manager catalog.rs blob 6137875a63ff0ce7f40985265d5d912332263527
All refer to original HEAD above. Additional source links and the five-link rejected constructor analysis are in the AI companion. No present VSM reassessment or C claim.

## Capability priority

**NO_GO. P0: candidate rejected now. P1: no admitted implementation work. P2: NONE.**

The investigated operator wants continuity when a model changes. The simplest native path is current provider/catalog migration plus a narrow repair where independently reproduced. A speculative autonomous S4 loop has no demonstrated additional operator outcome in the examined evidence. This does not prove every existing migration problem fixed.

S1=A, S3=C and S3*=C are not mandatory C targets. S2 lacks a qualified task in this S4-focused case. S5 policy remains outside the proposed authority. The complete matrix and exclusions are shared by Human/AI.

## Implementation options

No implementation. Native catalog, migration prompt, accepted selection/persistence and compaction mechanisms are the baseline. Conditional reopening requires a real prospective task beyond them, a legitimate composable autonomous actor, scoped alternative choices, first-party later-operation application and truthful returned outcomes. Authority/freshness/hidden-target/absent-actor negatives must be applicable to the actual source, not copied template tests.

Source tests were read, NOT RUN. No Rust build, model inference, before/after behavior, savings, deployment or independent review is claimed. The examples in the AI companion are future comparisons, not passed acceptance.

## Specification and domain alternatives

No Profile/Skills patch is warranted by the bounded result. A separately scoped experimental fork remains possible under license, actual owner rights and a demonstrated task, but is not recommended as a way to evade the current NO_GO or original PR policy. New useful evidence should first enrich an existing original report if separately authorized.

## Cost experiment

For the same retirement/provider/auth/session task, compare native migration plus repair against future S4 composition. Measure implementation, integration, review/testing, ongoing migration support, regressions and successful later-work continuity. All observed comparative values are NOT_MEASURED. No lower-cost claim.

## Delivery and publication

PLAN_ONLY research. Final operator decision **NO_GO** in all three documents. One case under opensiro/meta only; no product diff, new contributions record, Index edit, external Issue/comment/PR or public fork GitHub Issue.

Exact proposed fork destination: opensiro-contributions/codex.
Exact proposed title: Codex: model lifecycle adaptation roadmap, NO_GO (OpenSiro plan-only).
Exact proposed body: issue.md in this same case.
Publication status: NOT PUBLISHED; exact current-conversation consent absent. Given NO_GO, no new original feature Issue is recommended. An original maintainer draft is not fabricated merely to fill the workflow.

The structural validator must pass before initial metadata publication, followed by exact commit/file readback. Structural PASS is not semantic/behavioral/permission certification. Read back actual meta commit before claiming PERSISTED.

Selection provenance: current Upstream 7b23cc852b34fbb564c2fdb12ee00d994fc0c7dd, selector run offline from fetched pinned Index inputs after unauthenticated API 403. Bounded manual GitHub source screening followed. OpenClaw already has a case; Hermes has a case and PAUSE/DORMANT; DeepSeek has no external-PR route and no matching review issue from the bounded query; DoomPi yielded a sandbox repair, not this strategic demand. Codex is the selected original for this completed case. Unique contributor count UNKNOWN; 135784 source stars are a labeled current popularity fallback, not relevance/authority proof. No exhaustive claim over all Index candidates.
