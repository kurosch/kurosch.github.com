# AGENTS.md

## EGM Toolkit (Elephant-Goldfish Model)

The [EGM](https://egm.dev) spec-driven development toolkit from [google/elephant-goldfish-model](https://github.com/google/elephant-goldfish-model) is vendored at the repository root in [`.vibe/`](.vibe/README.md).

- **Skills** (`.vibe/skills/`): `egm-bootstrap`, `egm-brainstorm`, `egm-lite`, `egm-draft`, `egm-review`, `egm-review-loop`, `egm-resolve`, `egm-drift-report`
- **Goldfish reviewer personas** (`.vibe/agents/`), document standards and rubrics (`.vibe/resources/`), guides (`.vibe/docs/`)
- Usage: see `.vibe/docs/getting_started.md`; per-harness install commands (Antigravity, Claude Code, Codex, ...) in `.vibe/docs/harnesses.md`

To activate EGM as a plugin in your harness, install it from the marketplace, e.g. for Claude Code:

```bash
claude plugin marketplace add google/elephant-goldfish-model
claude plugin install egm@egm
```

The vendored `.vibe/` copy is kept in sync with upstream (currently `ef27af6b1d76901d09bb346eea62ce377546052f`, 2026-11-23).
