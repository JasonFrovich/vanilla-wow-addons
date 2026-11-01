# Vanilla WoW Addons — AI engineering entrypoint

**MANDATORY ICM STANDARD (2026-11-01):** Read this file first for every code, script, document or automation change. Follow [ICM-ROUTER.md](ICM-ROUTER.md) and [docs/ICM_CORE_ADOPTION_STANDARD.md](docs/ICM_CORE_ADOPTION_STANDARD.md). This policy is proposed on a review branch until merged.

## Safety / source-of-truth boundary
Treat the addon repository as game/UI code. Respect game-client API compatibility and existing packaging. Never change installed addons, game files, or game accounts during documentation adoption.

## Engineering rules
1. Read the project README and relevant code/tests, branch/HEAD, latest PM issue comments and existing project decisions before modifying anything.
2. Apply Interpretable Context Methodology: **Scope → Evidence → Verify → Report**. Use task-scoped stage `CONTEXT.md` documents where complexity justifies them; preserve source-pinned human-editable evidence.
3. Use Superpowers methods for real engineering: systematic debugging, meaningful RED/GREEN tests when behavior changes, code review, and exact-HEAD verification. Do not claim tools, test runs or independent reviews that did not occur.
4. Keep changes minimal and functional. Do not rewrite historical commands, alter unrelated files, modify live data, or silently discard earlier work.
5. Keep personal data, credentials, recipient documents, private logs and unreviewed raw evidence out of GitHub.
6. Prepare a copy-ready **read-only fresh ChatGPT review prompt** for a coherent substantive release candidate; do not demand per-commit independent review.
7. No merge, installation, production deployment, scheduled job, privileged action, migration, cleanup or deletion is authorized by these governance files.

## Required report
`PM_CHECK` · `ICM_STATUS` · `SUPERPOWERS` · `OTHER_TOOLS` · `PRODUCT_STATUS` · `NEXT_ACTION`.

For routine narrow changes, record these in the PR. For complex work, route to a bounded workspace and verify every stage handoff.
