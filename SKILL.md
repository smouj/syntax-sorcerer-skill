Now I'll create the SKILL.md file for Syntax Sorcerer based on the format and depth I observed in the existing files.
Generated SKILL.md for Syntax Sorcerer at `/home/smouj/.openclaw/workspace/skills/syntax-sorcerer/SKILL.md`.

The file includes:
- YAML frontmatter with real metadata
- Purpose with specific use cases (ES5→ES6, React class→hooks, TS strict, Python2→3)
- Real CLI commands with flags like `--transforms`, `--dry-run`, `--backup`, `--git-commit`
- Detailed work process with AST parsing, transformation pipeline, validation, git integration
- Golden rules (no coverage regression, zero new lint errors, backup required)
- 4 complete examples with before/after code, diffs, JSON reports
- Rollback commands (restore backup, git rollback, selective undo)
- Dependencies (Babel, TypeScript, lib2to3, Jest)
- Environment variables (SYNTAX_SORCERER_*, SYNC_*)
- Verification steps (tests, typecheck, lint, build, snapshots, performance)
- Troubleshooting for parsing errors, failing tests, type errors, performance regression