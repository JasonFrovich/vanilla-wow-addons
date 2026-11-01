# Vanilla WoW Addons — ICM Router (Layer 0)

Start: **[AGENTS.md](AGENTS.md)** → **[Core ICM standard](docs/ICM_CORE_ADOPTION_STANDARD.md)** → relevant source/tests and current PM GitHub evidence.

| Request | Route | Gate |
| --- | --- | --- |
| Trivial local source or documentation correction | Direct Superpowers engineering + compact Scope/Evidence/Verify/Report in PR | Test/review actual diff; no invented outcomes |
| Substantive, multi-file, safety-sensitive or cross-session task | Task-scoped `workspaces/<case>/CONTEXT.md` with stage contracts, then actual source/tests | Source SHA, predecessor digest, human edits and fail-closed resume |
| Engineering continuation across chats | Read current repo state and saved handoff, verify exact SHA and evidence provenance | No silent recovery of missing or stale stages |
| Release candidate / merge / deploy | Consolidated regression and source review; copy-ready independent ChatGPT review prompt where substantive | Separate owner authority for merge/install/deploy |
| Privileged, data, deletion or automation action | Project-specific safety/authorization contract in `AGENTS.md` and README | ICM never confers operational permission |

**Boundary:** Treat the addon repository as game/UI code. Respect game-client API compatibility and existing packaging. Never change installed addons, game files, or game accounts during documentation adoption.

Outputs are observations and evidence, not proof that ICM itself executes, deploys, improves model reasoning or protects runtime systems. Required reporting: `PM_CHECK`, `ICM_STATUS`, `SUPERPOWERS`, `OTHER_TOOLS`, `PRODUCT_STATUS`, `NEXT_ACTION`.
