# Vanilla WoW Addons — ICM core adoption standard

ICM is the standard context and evidence-continuity route for substantive tasks in this repository, effective November 1, 2026. It is not software, an agent launcher, a promise of speedup or a release authorization. Direct engineering remains appropriate for trivial changes.

## Canonical local references

- AGENTS.md: project rules and independent review.
- ICM-ROUTER.md: choose the least expensive safe path.
- workspaces/engineering/CONTEXT.md: bounded workspace map.
- Layer 2 instructions: stages/01-scope, 02-evidence, 03-verify, 04-report, each with Inputs, Process, Outputs and Check.
- Stable Layer 3 materials: Historical addon folders a/ through z/. No root README exists.
- Project safety: Preserve historic addon files and directory layout. No bulk edits, game-version assumptions, or disclosure of player/account data.

Upstream: https://github.com/RinDig/Interpretable-Context-Methodology and https://github.com/RinDig/icm-architect . Shared user Library reference: ICM_Superpowers_AI_Engineering_Playbook_Edition_2_8.md . Neither upstream skills nor Library documents are automatically installed/injected into an agent session.

## Minimum task evidence

A substantive task records (1) unique task ID, exact owner request, permitted/prohibited work; (2) repo, branch, source commit SHA, fixture/evidence-set ID/digest and observation date; (3) directly observed evidence with precise source anchors, distinguished from user reports, inference and unknowns; (4) tests with exact commands/environment/SHA and PASS, FAIL or NOT RUN, including relevant static/privacy/safety checks; (5) any disputes, changes and one precise, authorized next action. Do not promote missing evidence into certainty.

Keep raw outputs in a private task directory outside GitHub, e.g. $HOME/.icm-workspaces/vanilla-wow-addons/<task-id>/. Publish only separately approved, sanitized reports. No automatic directories or tool installs are created by these Markdown files.

## Strict resume and recovery

A receiver must validate task ID, source/evidence revision, valid predecessor artifacts and digest references. Missing, unreadable, malformed, human-modified, contradictory or stale artifacts cause a closed-stop; changes invalidate downstream verification/reporting. Ordinary resume never silently rebuilds or overwrites files. Only explicitly named recovery may reconstruct approved missing stages while preserving reviewed human work and labeling rebuilt evidence. Test runs must not be fabricated; NOT RUN is legitimate.

## Verification, review and release

Use appropriate Superpowers engineering practices (root cause, targeted TDD RED/GREEN for behavior changes, focused review and exact-HEAD verification) whether or not the tool is actually installed. Use Hypothesis/Semgrep/Graphify/REA selectively, never as a default installation campaign.

For coherent substantial change, the development conversation supplies a ready-to-copy NEW CHATGPT REVIEW prompt at review time with repository/PR, exact base/head SHAs, full diff, relevant safety requirements, tests and requested severity-ranked findings. The separate reviewer reads source and remains read-only. A draft prompt is not a completed independent review. Exact-HEAD CI, owner merge approval, installed-runtime validation and live operations are distinct gates. Documentation-only ICM adoption does not modify source behavior.
