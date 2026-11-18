# Codex: model lifecycle adaptation roadmap, NO_GO (OpenSiro plan-only)

PLAN_ONLY. Final operator decision: **NO_GO** for a new autonomous S4 constructor. GitHub Issue: NOT PUBLISHED.

## 1. Why OpenSiro and central accepted assessment

OpenSiro studies whether reusable VSM-informed specifications can standardize AI-agent harness development and lower implementation, integration, review and maintenance costs. Lower cost is an unmeasured hypothesis. Codex maintainers retain their own architecture and priorities.

**Accepted historical starting point: S1=A · S2=— · S3=C · S3*=C · S4=— · S5=—.**
[Accepted Index assessment](https://github.com/opensiro/vsm-harness-index/blob/34e11ec4dd52e1ba3ee0111d8bca73f13918f54f/assessments/co/codex.md), reviewed 2026-09-17, original review ref `b974893c90048d147207ae9004489c02f3116426`, Profile 0.2.1 / Methodology 0.3.1. Assessment blob: `60c8459fdf05904f9ed29f552816ace9486e8410`.

| Function | Accepted state | Meaning at the assessed boundary | Roadmap consequence |
| --- | --- | --- | --- |
| S1 | A | Coding agent owns operational tool choices and feedback | No new C work |
| S2 | — | Generic delegation/messages did not establish interference-specific coordination | Outside this model-lifecycle hypothesis |
| S3 | C | Optional first-party worker-tree current-control construction path | Reuse; no replacement manager |
| S3* | C | Configurable independent Guardian approval review | Preserve existing authority |
| S4 | — | No prospective environment-to-capability adaptation loop established | Investigated, new constructor rejected now |
| S5 | — | Ultimate policy is configured outside the runtime organization | No authority transfer proposed |

These are ownership arrangements, not a maturity score. The assessment is **62 days old** on 2026-11-18: recommend an Index-owned source-pinned reassessment before relying on it for present grades. This plan does not regrade Codex.

## 2. User task and final decision

Investigated task: when a provider retires a saved model or changes available capabilities, an operator wants later Codex work to use a supported model without losing the ongoing conversation.

Candidate P0: let a developer install an autonomous S4 actor that evaluates future model changes, chooses migrate/retain/hold, applies the choice to later work and receives actual operational feedback.

**NO_GO:** the bounded evidence does not establish enough additional user value for this constructor. Current source already supplies provider-scoped catalog discovery and migration guidance, accepted model-selection changes and compaction recovery. The concrete reports below concern compatibility and thread-history defects; they do not establish a demand for autonomous strategic selection. This is a decision against speculative feature work now, not proof that every migration problem is solved.

[AI/developer evidence and falsification contract](https://github.com/opensiro-contributions/codex/blob/opensiro/meta/.opensiro/issues/model-lifecycle-s4-20261118/constructor-sufficiency.md) · [source-pinned receipt](https://github.com/opensiro-contributions/codex/blob/opensiro/meta/.opensiro/issues/model-lifecycle-s4-20261118/roadmap.md).

## 3. Existing native work and remaining problems

| Native work / report | Observed source status, 2026-11-18 | Consequence |
| --- | --- | --- |
| [Provider-aware startup migration](https://github.com/openai/codex/blob/58ad62ce09dd7da5531cecb15fd69a21aa465332/codex-rs/tui/src/app/startup_prompts.rs) and [catalog manager](https://github.com/openai/codex/blob/58ad62ce09dd7da5531cecb15fd69a21aa465332/codex-rs/models-manager/src/manager.rs) | Present in pinned main | Reuse supported model metadata and user choice |
| [PR #44250](https://github.com/openai/codex/pull/44250) | MERGED; migration of saved selections even when retired entries disappear | Do not duplicate migration plumbing |
| [PR #29942](https://github.com/openai/codex/pull/29942) | MERGED; opt-in static-provider fallback | Preserve explicit choices and dynamic-provider limits |
| [PR #46324](https://github.com/openai/codex/pull/46324), [current fallback](https://github.com/openai/codex/blob/58ad62ce09dd7da5531cecb15fd69a21aa465332/codex-rs/core/src/compact_model_fallback.rs) | MERGED; current source has additional guards | Reactive recovery is useful; it is not proof of S4 |
| [#25440](https://github.com/openai/codex/issues/25440) | OPEN, user-reported config/auth compatibility problem | Existing repair/report route; current reproduction not established here |
| [#57321](https://github.com/openai/codex/issues/57321) | OPEN; reporter says migrated conversation continues but disappears from IDE history | Investigate indexing separately; a new S4 actor would not itself repair it |
| [PR #57337](https://github.com/openai/codex/pull/57337) | OPEN DRAFT release backport | Proposed release catalog update, not shipped by being open |

Current source pin: [`58ad62ce09dd7da5531cecb15fd69a21aa465332`](https://github.com/openai/codex/commit/58ad62ce09dd7da5531cecb15fd69a21aa465332). Source inspection is not runtime verification.

## 4. Priorities and minimum sufficient result

- **P0: REJECTED NOW.** No new autonomous S4 constructor or controller.
- **P1: no implementation backlog created.** Preserve the existing native migration/catalog path. A separately requested repair should start from a reproducible current-version instance of an existing report.
- **P2: NONE.** No additional S2/S3/S3*/S5 constructor, parent mode or autonomy ladder.

A useful future S4 proposal would need a real prospective operator scenario that the native baseline cannot meet, a legitimate developer-composed decision owner, supported alternatives, authorized application to later operation and actual returned outcomes. Generic catalog hooks or a model router are insufficient.

## 5. Acceptance and stop

No product tests were run; no implementation was attempted. Existing source tests were inspected, not executed. A follow-up must distinguish a real migration repair from prospective S4 and compare the identical user task with the current native path. Stop if only a missing historical grade or an extra callback justifies the feature.

The technical companion specifies native comparison cases and the evidence that could reopen the decision. **NO_GO** is the completed research verdict; another routine continuation is not required.

## 6. Independent paths and cost

Product-native bug analysis may use existing Codex issues. Profile/Skills feedback is warranted only if an actual semantic counterexample is found. A domain-specific experimental fork would be a separate project with its own demand and rights.

For the same model-retirement task, compare native catalog/migration plus a narrow repair with an S4-composable alternative: implementation, integration, review/test, repeat-migration support, regression load and task continuity. **Cost status: NOT_MEASURED.** No savings or superior quality is claimed.

## 7. Rights and delivery

[Current contribution policy](https://github.com/openai/codex/blob/58ad62ce09dd7da5531cecb15fd69a21aa465332/docs/contributing.md) accepts issue reports, analysis and feature requests, and does **not** accept external code contributions/PRs. Apache-2.0 licensing permits lawful derivative work subject to its conditions; it does not override that maintainer policy. No CLA signature or human review is asserted.

The verified working fork is [opensiro-contributions/codex](https://github.com/opensiro-contributions/codex); research files belong only on `opensiro/meta`. The initial metadata uses restrictive PAUSE/DORMANT defaults, not an invented human RESUME. No product branch change is requested.

This text is the exact proposed fork Issue body. Destination: `opensiro-contributions/codex`. Publication requires separate exact current-conversation approval. An original-repository issue is not recommended for this rejected feature; use existing reports for separately authorized useful evidence.

**AI disclosure:** Prepared with AI assistance. No native execution, independent human technical review, present-grade upgrade, measured cost reduction or maintainer endorsement is claimed.
