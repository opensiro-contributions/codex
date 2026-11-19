# openai/codex — Upstream #58 independent Human decision

**Target transition:** NO_QUALIFIED_C_TARGET
**Proposal-stage decision:** NO_GO
**Research disposition:** NO_USEFUL_CHANGE

[roadmap.md](roadmap.md) — canonical receipt; [constructor-sufficiency.md](constructor-sufficiency.md) — technical AI contract. Internal draft, NOT PUBLISHED.

## Accepted baseline and current source

Accepted historical [Index review](https://github.com/opensiro/vsm-harness-index/blob/c2e43bf4750841277b3e58d8ba80314121734764/assessments/co/codex.md) (2026-09-17, Profile 0.2.1, Skills 0.3.1; blob `60c8459fdf05904f9ed29f552816ace9486e8410`). Original current [HEAD](https://github.com/openai/codex/commit/2f0374456fd5cd280ee76de54220ab8315a0f8d0) is separately pinned and not automatically reclassified.

| Function / role | Historical Index state | Current owner/closure | Priority / candidate |
| --- | --- | --- | --- |
| **S1 · Operations** | A | standard agent performs autonomous tool operations and responds to results | NO_TARGET / DEFER |
| **S2 · Coordination** | — | ordinary subagent delegation does not establish peer S2 interference regulation | NO_TARGET / DEFER |
| **S3 · Current regulation** | C | optional MAv2 root controls active worker tree | NO_TARGET / DEFER |
| **S3* · Independent audit** | C | optional Guardian independently challenges proposed action | NO_TARGET / DEFER |
| **S4 · Prospective environment** | — | model catalog refresh is current configuration, not prospective S4 | NO_TARGET / DEFER |
| **S5 · Ultimate identity/policy** | — | human/deployer governance and configured permissions retain ultimate policy right | NO_TARGET / DEFER |

## Operator question and answer

A hypothetical automatically selected model/provider lifecycle migration beyond ordinary catalog refresh and user-controlled routes. Track A native: Provider/model catalog refresh, policy-checked model availability and user-configured routes already exist. Existing threads retain their model route; MultiAgentV2/Guardian have separate scopes. `docs/contributing.md` explicitly forbids external code PRs.. Track B: NO new first-party S4 constructor: a trend watcher/model migration controller lacks evidenced future-environment actor with lawful model-choice rights or unique return-to-later operation; retain provider/user choices and current catalog. **NO_GO** because Demonstrated externally changing provider capability makes the existing catalog and user choice insufficient, while a legitimate opt-in autonomous S4 owner makes a distinct authorized later-run decision; original maintainers then accept the boundary remains unproven and the existing native work is better scoped. This is not a claim the original issues were resolved.

## Evidence and next step

Original [codex-rs/app-server/src/model_catalog.rs](https://github.com/openai/codex/blob/2f0374456fd5cd280ee76de54220ab8315a0f8d0/codex-rs/app-server/src/model_catalog.rs); [codex-rs/features/src/lib.rs](https://github.com/openai/codex/blob/2f0374456fd5cd280ee76de54220ab8315a0f8d0/codex-rs/features/src/lib.rs); [docs/contributing.md](https://github.com/openai/codex/blob/2f0374456fd5cd280ee76de54220ab8315a0f8d0/docs/contributing.md); native links [pull / 62525](https://github.com/openai/codex/pull/62525); [pull / 62499](https://github.com/openai/codex/pull/62499); [issues / 56705](https://github.com/openai/codex/issues/56705). P1: First reproduce model lifecycle failure under current provider policy; respect original issue-only contribution policy and preserve retained thread model binding. Previous Codex case NO_GO on model lifecycle; source changes and policy still provide no new qualified autonomous S4 need. This is a fresh source-pinned comparison, not a new Index grade.. New tests NOT_RUN, cost NOT_MEASURED. No third-party publication, source edit or Index regrade. Owner ACTIVE/ALLOW applies to internal fork meta only. AI-assisted draft.
