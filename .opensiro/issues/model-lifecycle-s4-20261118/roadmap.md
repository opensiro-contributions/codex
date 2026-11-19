# openai/codex — Upstream #58 independent v0.18 receipt

- Receipt contract: proposal-gate
- Original repository: openai/codex
- Original HEAD: 2f0374456fd5cd280ee76de54220ab8315a0f8d0
- Observed at: 2026-11-19
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/c2e43bf4750841277b3e58d8ba80314121734764/assessments/co/codex.md
- Accepted assessment blob SHA: 60c8459fdf05904f9ed29f552816ace9486e8410
- Accepted review ref: b974893c90048d147207ae9004489c02f3116426
- Accepted reviewed at: 2026-09-17
- Accepted Index commit: c2e43bf4750841277b3e58d8ba80314121734764
- Accepted Profile version: 0.2.1
- Accepted Skills methodology version: 0.3.1
- Accepted VSM vector: S1=A · S2=— · S3=C · S3*=C · S4=— · S5=—
- System in focus: Public first-party Codex CLI/TUI/app-server model catalogs, current config, MultiAgentV2 and Guardian; excludes model-provider proprietary strategy and closed desktop systems
- Matching working fork: opensiro-contributions/codex
- Fork owner control: ACTIVE/ALLOW per .opensiro/state.json
- Repository-wide source map: codex-rs/app-server/src/model_catalog.rs; codex-rs/features/src/lib.rs; docs/contributing.md; original README, docs, tests, license, contributing and focused original Issues/PRs
- Evaluation object: A hypothetical automatically selected model/provider lifecycle migration beyond ordinary catalog refresh and user-controlled routes
- Existing-work overlap: Provider/model catalog refresh, policy-checked model availability and user-configured routes already exist. Existing threads retain their model route; MultiAgentV2/Guardian have separate scopes. `docs/contributing.md` explicitly forbids external code PRs.
- Our on-top contribution: NO new first-party S4 constructor: a trend watcher/model migration controller lacks evidenced future-environment actor with lawful model-choice rights or unique return-to-later operation; retain provider/user choices and current catalog
- Incremental benefit: no distinct measured improvement over native repair and parent controls; no deployed C claimed
- Decision scope: one current-head C feasibility test, not repository-wide Index reclassification
- Priority rationale: S3/S3* already composable; S1 autonomous; S2 needs interference proof; S4 lacks source-grounded lawful adaptation need and source contribution is restricted
- Target transition: NO_QUALIFIED_C_TARGET
- P1 dependencies: First reproduce model lifecycle failure under current provider policy; respect original issue-only contribution policy and preserve retained thread model binding
- P2 optional: NONE
- Proposed C construction: NO new first-party S4 constructor: a trend watcher/model migration controller lacks evidenced future-environment actor with lawful model-choice rights or unique return-to-later operation; retain provider/user choices and current catalog
- C sufficiency falsifier: Demonstrated externally changing provider capability makes the existing catalog and user choice insufficient, while a legitimate opt-in autonomous S4 owner makes a distinct authorized later-run decision; original maintainers then accept the boundary
- Scenario basis: HYPOTHETICAL
- Proposal-stage decision: NO_GO
- Research disposition: NO_USEFUL_CHANGE
- Proposed validation: Compare current catalog invalidation, provider policy denial and retained live threads with hypothetical future changes; no new authorized code path or native tests executed
- Validation state: NOT_RUN
- Proposal falsifier: Demonstrated externally changing provider capability makes the existing catalog and user choice insufficient, while a legitimate opt-in autonomous S4 owner makes a distinct authorized later-run decision; original maintainers then accept the boundary
- Result: NO_USEFUL_CHANGE
- External issue: DRAFT — NOT PUBLISHED
- Public fork Issue: DRAFT — NOT PUBLISHED
- Cost status: NOT_MEASURED
- S1 disposition: standard agent performs autonomous tool operations and responds to results
- S2 disposition: ordinary subagent delegation does not establish peer S2 interference regulation
- S3 disposition: optional MAv2 root controls active worker tree
- S3* disposition: optional Guardian independently challenges proposed action
- S4 disposition: model catalog refresh is current configuration, not prospective S4
- S5 disposition: human/deployer governance and configured permissions retain ultimate policy right

## Identity and pins

[Accepted included Index assessment](https://github.com/opensiro/vsm-harness-index/blob/c2e43bf4750841277b3e58d8ba80314121734764/assessments/co/codex.md) at frozen `c2e43bf4750841277b3e58d8ba80314121734764`, reviewed 2026-09-17 at [original review commit](https://github.com/openai/codex/commit/b974893c90048d147207ae9004489c02f3116426); historical blob `60c8459fdf05904f9ed29f552816ace9486e8410`; Profile 0.2.1, Skills 0.3.1. Distinct [current original HEAD](https://github.com/openai/codex/commit/2f0374456fd5cd280ee76de54220ab8315a0f8d0). Source-first decision precedes comparison to original fork case. No present Index regrade.

## Rights and authority

Fork parent and owner-controlled ACTIVE/ALLOW on `opensiro/meta` independently checked. Original repo public with read rights, licensed OSS; contributor policy checked. Codex CONTRIBUTING explicitly disallows external code PRs; only original Issues/analysis are allowed by maintainers (still not published by OpenSiro). Third-party messages/public fork Issues not authorized. Original product, deployment and Index unchanged.

## Existing work / overlap

Source [codex-rs/app-server/src/model_catalog.rs](https://github.com/openai/codex/blob/2f0374456fd5cd280ee76de54220ab8315a0f8d0/codex-rs/app-server/src/model_catalog.rs); [codex-rs/features/src/lib.rs](https://github.com/openai/codex/blob/2f0374456fd5cd280ee76de54220ab8315a0f8d0/codex-rs/features/src/lib.rs); [docs/contributing.md](https://github.com/openai/codex/blob/2f0374456fd5cd280ee76de54220ab8315a0f8d0/docs/contributing.md). Original Issues/PRs: [pull / 62525](https://github.com/openai/codex/pull/62525); [pull / 62499](https://github.com/openai/codex/pull/62499); [issues / 56705](https://github.com/openai/codex/issues/56705). Provider/model catalog refresh, policy-checked model availability and user-configured routes already exist. Existing threads retain their model route; MultiAgentV2/Guardian have separate scopes. `docs/contributing.md` explicitly forbids external code PRs.. OPEN_PR is not SHIPPED, and search absence cannot certify global absence.

## Function ownership

- **S1** historical **A**: standard agent performs autonomous tool operations and responds to results. No new credited ownership or compulsory A-to-C conversion.
- **S2** historical **—**: ordinary subagent delegation does not establish peer S2 interference regulation. No new credited ownership or compulsory A-to-C conversion.
- **S3** historical **C**: optional MAv2 root controls active worker tree. No new credited ownership or compulsory A-to-C conversion.
- **S3*** historical **C**: optional Guardian independently challenges proposed action. No new credited ownership or compulsory A-to-C conversion.
- **S4** historical **—**: model catalog refresh is current configuration, not prospective S4. No new credited ownership or compulsory A-to-C conversion.
- **S5** historical **—**: human/deployer governance and configured permissions retain ultimate policy right. No new credited ownership or compulsory A-to-C conversion.

## Parallel contribution-on-top review

| Candidate function/outcome | Track A: original and competing work | Track B: smallest on-top complete C or NONE | What would disprove this decision? |
| --- | --- | --- | --- |
| A hypothetical automatically selected model/provider lifecycle migration beyond ordinary catalog refresh and user-controlled routes | Provider/model catalog refresh, policy-checked model availability and user-configured routes already exist. Existing threads retain their model route; MultiAgentV2/Guardian have separate scopes. `docs/contributing.md` explicitly forbids external code PRs. | NO new first-party S4 constructor: a trend watcher/model migration controller lacks evidenced future-environment actor with lawful model-choice rights or unique return-to-later operation; retain provider/user choices and current catalog | Demonstrated externally changing provider capability makes the existing catalog and user choice insufficient, while a legitimate opt-in autonomous S4 owner makes a distinct authorized later-run decision; original maintainers then accept the boundary |
| Source-native later-operation feedback | First-party sessions, host policy and existing task controls | No independent new actor or gate; preserve parent authority and implement base defects via native issues | Evidence of a missing authorized independent decision that changes subsequent operations |

## Capability priority

P0: **NO_QUALIFIED_C_TARGET**. P1: First reproduce model lifecycle failure under current provider policy; respect original issue-only contribution policy and preserve retained thread model binding. P2: NONE. **NO_GO / NO_USEFUL_CHANGE**; no mandatory C target just because S2/S3*/S4/S5 is absent.

## Implementation options

NO new first-party S4 constructor: a trend watcher/model migration controller lacks evidenced future-environment actor with lawful model-choice rights or unique return-to-later operation; retain provider/user choices and current catalog. A complete novel constructor would have to identify separate owner and decision, first-party interface, enforcement and feedback with a parent-bounded correction; Demonstrated externally changing provider capability makes the existing catalog and user choice insufficient, while a legitimate opt-in autonomous S4 owner makes a distinct authorized later-run decision; original maintainers then accept the boundary. Source-native alternative is more limited and sufficient for the present evidence.

## Specification and domain alternatives

Previous Codex case NO_GO on model lifecycle; source changes and policy still provide no new qualified autonomous S4 need. This is a fresh source-pinned comparison, not a new Index grade.. Intent behind any absent functions UNKNOWN, not a default intentional absence. No Profile or Skills specification patch proposed.

## Cost experiment

Compare current catalog invalidation, provider policy denial and retained live threads with hypothetical future changes; no new authorized code path or native tests executed. Matched implementation/integration/test hours, false decisions, token/latency and cost unmeasured; NOT_RUN / NOT_MEASURED.

## Delivery and publication

Canonical [Human](issue.md) and [AI](constructor-sufficiency.md) agree: **NO_GO / NO_USEFUL_CHANGE**. Only internal .opensiro receipt modified, original-facing Issue/PR/comment and public fork Issue NOT PUBLISHED, source code untouched and historical Index assessment unchanged.
