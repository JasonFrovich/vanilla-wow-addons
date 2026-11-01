# Vanilla WoW Addons — ICM Layer 1 workspace

Read ../../AGENTS.md and ../../ICM-ROUTER.md, then ../../docs/ICM_CORE_ADOPTION_STANDARD.md. Select only stages needed. Store private task evidence under $HOME/.icm-workspaces/vanilla-wow-addons/<task-id>/, outside the repository.

| Stage | Contract | Purpose |
| --- | --- | --- |
| 01 | stages/01-scope/CONTEXT.md | Task, authority, scope, source commit |
| 02 | stages/02-evidence/CONTEXT.md | Observed evidence, provenance, unknowns |
| 03 | stages/03-verify/CONTEXT.md | Predecessor validation, tests and safety |
| 04 | stages/04-report/CONTEXT.md | Resumable decision, next owner gate |

A stage must not import facts from another case or invent a missing predecessor. Routine resume is read/validate only. Explicit recovery is a separate reviewed action. Project safety: Preserve historic addon files and directory layout. No bulk edits, game-version assumptions, or disclosure of player/account data.
