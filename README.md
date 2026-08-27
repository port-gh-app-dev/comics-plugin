# comics-plugin

Claude Code plugin scaffold for DC Comics discovery.

## Included plugin files

- `.claude-plugin/plugin.json` — plugin manifest
- `.mcp.json` — MCP server configuration (filesystem server for this project)
- `skills/dc-comics-discovery/SKILL.md` — DC discovery skill
- `commands/discover-dc-comics.md` — slash command entrypoint

## Local install (project scope)

From this repository root:

```bash
claude plugin install . -s project
```
