# Vanilla WoW Addons — ICM Core Adoption Standard

**Effective policy date:** 2026-11-01. **State:** Proposed in a review branch; operational on the target branch only after an authorized merge. This is a documented engineering standard, not a runtime feature or permission to deploy.

ICM means **Interpretable Context Methodology**: bounded, interpretable context, versioned source references, and checked handoffs. Use **Superpowers engineering practices** for systematic investigation, test-first implementation when behavior changes, source review and verification. GitHub hosts source-pinned evidence. Neither process implies a model, skill, CI system or reviewer has actually run.

## Selection and responsibility
- Every script, program, maintenance task and GitHub contribution must **follow this policy**. For a trivial, self-contained change, a compact Scope → Evidence → Verify → Report record in the PR is sufficient; don't generate unnecessary stages.
- For substantive, multi-file, high-risk or cross-conversation work, use a task-scoped workspace with `CONTEXT.md` and bounded `01-scope`, `02-evidence`, `03-verify`, `04-report` stages as appropriate. Stage instructions include inputs, process, outputs and an explicit verification check. Keep raw/private outputs uncommitted.
- Start at `AGENTS.md`, follow `ICM-ROUTER.md`, read the actual project README/source/test safety contracts and latest relevant GitHub issue/PR and PM decisions. Never import another project's stale assumptions.
- Distinguish user-reported facts, observed source/runtime evidence, hypotheses, unsupported claims and unknowns. Verify exact branch, commit SHA, artifact paths and SHA-256 where applicable.
- A handoff must contain exact scope/question, source SHA, input/fixture identity, evidence provenance, test commands/results or NOT RUN, blockers, next permitted action, and a predecessor digest/reference. Refuse stale, missing, malformed or inconsistent handoffs. Ordinary resume must never overwrite user-edited prior evidence; explicit recovery is separate, fail-closed and limited.
- Code-first: fix working code rather than repeatedly performing documentation-only audits. For behavior changes: reproduce failure safely (RED), implement minimally, verify passing result (GREEN), run relevant tests/CI at exact HEAD. For documentation-only policy updates: verify link/files/contents and state tests NOT RUN.
- For coherent substantive release candidates, the development chat supplies a **complete copy-ready independent new-ChatGPT reviewer prompt** with repo/PR/base+head SHAs, full-diff inspection, risks and read-only instructions. Do not demand a reviewer chat for every trivial change. A prompt is not a completed review.
- No assumptions of test results, installed-runtime parity, independent AI productivity gains or operational authorization. Hypothesis, Semgrep, Graphify and GitHub Actions are useful where installed/available and relevant; clearly label anything NOT RUN.
- Merges, installs, privileged changes, cloud actions, scheduled jobs, deletions, data migration, and deployment require their own explicit authorization. ICM docs grant none.

## Project-specific boundaries
Treat the addon repository as game/UI code. Respect game-client API compatibility and existing packaging. Never change installed addons, game files, or game accounts during documentation adoption.

## Mandatory completion report
Report exactly these fields in developer handoffs: `PM_CHECK`, `ICM_STATUS`, `SUPERPOWERS`, `OTHER_TOOLS`, `PRODUCT_STATUS`, `NEXT_ACTION`. Each field must distinguish verified facts, review-only changes and missing checks.

## Minimal handoff artifact format
```markdown
# Context handoff
Scope: [exact question / intended behavior]
Source: [repository, branch, exact commit SHA]
Evidence: [source links, direct observations, artifact references/digests]
Verification: [actual commands, environment, results / NOT RUN]
Decision: [accepted/rejected hypothesis and why; open unknowns]
Safety boundaries: [what was not changed / not authorized]
Next action: [single specific permitted action]
```

## References
- Repository `AGENTS.md`, `ICM-ROUTER.md` and `README.md` (where present)
- Official ICM: https://github.com/RinDig/Interpretable-Context-Methodology
- Shared cross-project guidance: `ICM_Superpowers_AI_Engineering_Playbook_Edition_2_8.md` in ChatGPT Library, which is **not automatically loaded in new chats**. Always inspect local repo contracts first.
