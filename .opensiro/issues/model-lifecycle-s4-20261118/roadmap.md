# Codex — independent Upstream #58 Wave 4 S4 roadmap

- Receipt contract: proposal-gate
- Original repository: openai/codex
- Original HEAD: bb5b9c6240136de8ff4d30215e2341c44559aa04
- Observed at: 2026-11-20
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/8f436270813b844aafc16917d69bc09661ef1544/assessments/co/codex.md
- Accepted assessment blob SHA: 60c8459fdf05904f9ed29f552816ace9486e8410
- Accepted review ref: b974893c90048d147207ae9004489c02f3116426
- Accepted reviewed at: 2026-09-17
- Accepted Index commit: 8f436270813b844aafc16917d69bc09661ef1544
- Accepted Profile version: 0.2.1
- Accepted Skills methodology version: 0.3.1
- Accepted VSM vector: S1=A · S2=— · S3=C · S3*=C · S4=— · S5=—
- System in focus: Public Codex CLI/TUI/app-server, model catalog and supported optional multi-agent/Guardian modes, excluding proprietary provider policy and closed deployments
- Matching working fork: opensiro-contributions/codex
- Fork owner control: ACTIVE/ALLOW
- Repository-wide source map: codex-rs/models-manager/src/manager.rs; codex-rs/app-server/src/models_refresh_worker.rs; codex-rs/tui/src/app/startup_prompts.rs; codex-rs/tui/src/model_migration.rs; codex-rs/core/src/session/model_catalog_settings.rs; codex-rs/core/src/tools/handlers/multi_agents_spec.rs; codex-rs/ext/guardian-reviewer/src/routing.rs; codex-rs/protocol/src/config_types.rs; docs/contributing.md; native issues, PRs and tests
- Evaluation object: Optional prospective provider-model lifecycle adaptation with independent future options and a lawful next-turn S4-to-S3-to-S4 feedback loop, not a current-session capacity retry
- Existing-work overlap: Native online catalog refresh, provider/auth-aware cache, explicit migration prompts, future-turn settings and guardian/root-worker controls already ship; they do not establish independent prospective interpretation, S3 decision return and later operational feedback
- Our on-top contribution: Opt-in developer-composed, provider-scoped future-transition advisor; dated external notice to retain/prepare-approved-migration/hold choice, typed host S3 proposal and acknowledgement, observed next-turn effect and result returned to S4
- Incremental benefit: HYPOTHETICAL, future experiment only; no measured demand, runtime savings, maintainer endorsement or shipped code
- Decision scope: Architectural C constructibility only, not Codex product adoption or an Index regrade
- Priority rationale: S1 operational; S3 and S3* already historical C; S2 not yet source-proven; S5 remains parent-governed; S4 is a candidate with an independently owned future-options decision and lawful host feedback path
- Target transition: S4=— -> S4=C
- P1 dependencies: Verify external notice provenance/expiry, provider/model eligibility and developer policy; design idempotent typed S3 host proposal-ack; ensure next-turn-only application, denial feedback and source-native positive/negative tests
- P2 optional: Decision-quality reporting and future measured cost/benefit, not needed for minimum S4 C
- Proposed C construction: Optional first-party advisor interprets externally attributable future provider retirement/capability notices with catalog and user constraints, autonomously selects retain/prepare-approved-migration/hold option in delegated scope, sends typed proposal to host/S3 for approval and next-turn effect, then observes approved/denied application and actual later-run outcome to update future options; parent retains ultimate model and permission rights
- C sufficiency falsifier: Equivalent first-party future S4 decision, enforceable host S3 choice and returned later outcome already ship, or no lawful supported next-turn/host path can be composed, or proposal collapses to alert-only/user-only choice
- Scenario basis: HYPOTHETICAL
- Proposal-stage decision: GO
- Research disposition: NEEDS_EVIDENCE
- Proposed validation: Native positive vendor sunset notice with allowed successor and later run feedback; negatives for wrong-provider notice, stale data, unapproved model/cost, absent actor, running-turn mutation, host denial, repeated proposal, missing effect and absent later feedback; compare native picker+catalog baseline
- Validation state: NOT_RUN
- Proposal falsifier: Equivalent shipped full S4 decision-owner closure, prohibited parent policy transfer or missing effect/return; unmeasured user value alone is not a constructibility falsifier
- Result: PLAN_ONLY
- External issue: DRAFT — NOT PUBLISHED
- Public fork Issue: DRAFT — NOT PUBLISHED
- Cost status: NOT_MEASURED
- S1 disposition: A historical, coding agent owns tool choices and operational feedback; NO_TARGET
- S2 disposition: — historical, message/task delegation does not alone evidence peer interference regulation; DEFER pending owner proof
- S3 disposition: C historical, optional MultiAgentV2 root controls live worker tree; NO_TARGET
- S3* disposition: C historical, configured separate Guardian approval reviewer gates actions; NO_TARGET
- S4 disposition: — historical, current catalog refresh and reactive prompts do not prove future intelligence to S3 and return; P0
- S5 disposition: — historical, host/developer/user retains policy, credentials and model selection; NO_TARGET

## Identity and pins

The independent first pass [was sealed here](https://github.com/opensiro/upstream/issues/58#issuecomment-7043626535) before reading the historical case. Current original [HEAD](https://github.com/openai/codex/commit/bb5b9c6240136de8ff4d30215e2341c44559aa04), accepted [Index included at pinned main](https://github.com/opensiro/vsm-harness-index/blob/8f436270813b844aafc16917d69bc09661ef1544/assessments/co/codex.md) and [published v0.18.0 protocol](https://github.com/opensiro/upstream/commit/28ea2cce06b517bc4550dceddb00210b1e0dc85c) are separate sources. The accepted 2026-09-17 Index assessment remains unchanged; its age exceeds 30 days, so a separate reassessment is advisable before any implementation. No current Index regrade is claimed.

## Rights and authority

Original is Apache-2.0. [Codex contributing policy](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/docs/contributing.md) does not accept external code PRs; this limits contribution/publication channels but does not prove the future C constructor impossible. User/host decides whether any model choice is permitted, and proprietary backend/deployer authority is outside this declared harness boundary. The fork is ACTIVE/ALLOW only for internal metadata. No original issue, original PR, public fork GitHub Issue, or external comment was published.

## Existing work / overlap

- [Online catalog manager](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/models-manager/src/manager.rs) distinguishes cache, provider identity, online and offline refresh; [refresh worker](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/app-server/src/models_refresh_worker.rs) polls every 270 seconds.
- [Startup migration](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/tui/src/app/startup_prompts.rs) and [picker](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/tui/src/model_migration.rs) offer reactive user-accepted model replacement. [Merged PR #47932](https://github.com/openai/codex/pull/47932) retained migration prompts; [merged #50013](https://github.com/openai/codex/pull/50013) handles server defaults; [merged #58134](https://github.com/openai/codex/pull/58134) offers documented retirement guidance. These are not evidence of already owned independent future S4 closure.
- [Next-turn session settings](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/core/src/session/model_catalog_settings.rs) explicitly preserve running-step settings; a future S4 actor may only propose an authorized next-turn change. [Original issue #55983](https://github.com/openai/codex/issues/55983) OPEN concerns operational capacity fallback, not future environment intelligence.

## Function ownership

1. S1 operations: autonomous local agent/tool work. No new S1 constructor.
2. S2 coordination: first-party worker messaging exists, but peer-interference damping decision ownership is unverified; not regraded or chosen as target.
3. S3 current control: root can assign/inspect/interrupt live team using [multi-agent tools](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/core/src/tools/handlers/multi_agents_spec.rs); accepted conditional C.
4. S3* independent audit: [Guardian reviewer](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/ext/guardian-reviewer/src/routing.rs) can gate action; accepted conditional C.
5. S4 future environment: reactive catalog and migration do not show prospective autonomous future-option choice, host application, and observed return; a developer-composed C path is technically hypothesized.
6. S5 identity/policy: ultimate scope, provider credentials, selected model and permission policy remain human/host configured, not a transferred S5 power.

## Parallel contribution-on-top review

| Link | Track A native shipped/proposed | Track B minimal missing first-party link | Negative control |
| --- | --- | --- | --- |
| Future disturbance | online catalog and current model metadata | dated attributable retirement/capability event, interpretation of future options | current-only catalog, stale or wrong provider |
| S4 decision | user migration picker | autonomous opt-in retain / prepare-approved-migration / hold within developer allowlist | always-switch or user-only choice |
| S4-to-S3 decision/effect | host next-turn model settings and policy | narrow typed proposal, auth/eligibility, accept/deny acknowledgement, next-turn-only apply | direct S4 mutation or bypass cost rights |
| S3-to-S4 feedback | host emits settings and operational results | correlate proposal with actual later chosen model and run outcome, update future options | one-way digest, log-only acknowledgement |

Simplest native alternative is existing catalog polling + reactive picker, which should remain unchanged for defaults. Standalone provider digest is incomplete S4 closure; temporary-capacity retry is a different S1 continuity problem. A complete C witness requires all four new/existing linked obligations with conditional authorization, effect and later feedback.

## Capability priority

P0: optional original-native model-transition intelligence completing S4 C if later implemented and independently validated. P1: provider/notice provenance, explicit delegated authority and checked S3 proposal/ack, idempotence and native tests; these must precede implementation. P2: optional additional comparison estimates. **GO / NEEDS_EVIDENCE** applies only to architectural construction.

## Implementation options

Reuse current catalog, session model settings, migration prompt and host policy; introduce one bounded first-party advisor and a minimal typed proposal/ack/observed-outcome interface. The actor cannot write current-running-turn settings, grant credentials, change more-expensive models silently, or choose ultimate S5 policy. Future native tests would compare approved migration and hold choices with original native picker before any product decision.

## Specification and domain alternatives

The [historical 2026-11-19 case](https://github.com/opensiro-contributions/codex/blob/a97563d594f23023a6104773ff4f2a3ba0c1e48b/.opensiro/issues/model-lifecycle-s4-20261118/roadmap.md) was NO_GO / NO_USEFUL_CHANGE partly because no measured *product usefulness* or independently evidenced new model-choice rights were found. A [new independent Wave 4 first pass](https://github.com/opensiro/upstream/issues/58#issuecomment-7043626535) judged a lawful developer-composed prospective S4 owner **architecturally constructible** under published assessment-neutral v0.18.0; measured value and maintainer adoption are separate future questions. Historic Git ancestry remains unchanged; current decision is GO / NEEDS_EVIDENCE. No Profile/Skills change or claim of maintainer intent.

## Cost experiment

HYPOTHETICAL: compare dated notice, next-turn applied effect and returned outcome against existing picker/catalog behavior, including false proposals and fallback denial. Native experiments NOT_RUN; cost/savings NOT_MEASURED; potential source-specific deployment feasibility still needs evidence.

## Delivery and publication

Case links: [Human issue.md](issue.md) and [AI constructor-sufficiency.md](constructor-sufficiency.md). Internal fork case is plan-only; product implementation NOT_DONE, original and public fork publication NOT_PUBLISHED, Index unchanged. No shipped S4 C. Readback of persisted artifact SHA and structural validator required before marking verified.

## Native-specific advisory addendum — v0.18.1 (2026-11-20)

This is an **attributed refinement of the same existing Wave 4 case**, not a new independent rerun, evidence of adoption, or a change to the sealed `GO / NEEDS_EVIDENCE` verdict. The detailed [Codex-native actor/handoff/effect/return design](constructor-sufficiency.md#v0181-native-specific-clarification-2026-11-20-nonbinding) reuses [`ModelsManager::model_catalog_updates`](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/models-manager/src/manager.rs), [app-server catalog refresh](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/app-server/src/models_refresh_worker.rs), [user migration outcome](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/tui/src/model_migration.rs), and [next-turn session settings](https://github.com/openai/codex/blob/bb5b9c6240136de8ff4d30215e2341c44559aa04/codex-rs/core/src/session/model_catalog_settings.rs). The *minimum additional source-native work* is a provider-scoped, provable future-notice interpreter; one authorized proposal/ack path into the existing host/session model-setting path; and correlated **actual later-turn** outcome feedback. Catalog refresh alone is not S4 future intelligence, and a settings-applied event alone does not attest later-run success.

**User-facing hypothetical result:** receive a model-retirement proposal before a disruption, accept/deny it under existing Codex policy, and verify later model effect + result without changing an in-flight step. This is a bounded opt-in research construct, not assumed demand, cost saving or an intended maintainer priority. Keep `P0 S4=— -> S4=C`, `P1` authority/provenance/negative/feedback tests and optional `P2` as previously recorded. Original/Index pins and historical comparisons unchanged. Official native tests **NOT_RUN**, cost **NOT_MEASURED**. [Nonbinding patch v0.18.1](https://github.com/opensiro/upstream/blob/main/changes/v0.18.1.md); new Upstream per-run report PR **NOT CREATED**.
