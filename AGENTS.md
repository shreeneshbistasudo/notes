# Obsidian Vault: /home/shreenesh/notes

Plain markdown vault. No build, no git, no CI.

## Vault structure

| Directory | Purpose |
|-----------|---------|
| `Daily/` | Daily notes (daily-notes core plugin enabled) |
| `Archive/` | Reference notes, old research |
| `programming/` | Dev notes |
| `Projects/` | Project-specific notes |
| `Resources/` | Reference material |

## Important settings

- `alwaysUpdateLinks: true` — renaming/moving a note auto-updates all `[[wikilinks]]` pointing to it.
- `promptDelete: false` — deleting a note moves it to `.trash/` (not permanent).

## Obsidian MCP

Already configured in `~/.config/opencode/opencode.jsonc`. Use Obsidian MCP tools (`obsidian_create_note`, `obsidian_read_note`, `obsidian_update_note`, `obsidian_daily_note`, `obsidian_search_vault`, `obsidian_delete_note`, etc.) to interact with the vault. Do NOT read/write vault markdown files directly with filesystem tools unless the MCP tool is unavailable for the specific operation.

## Plugins (community)

- **Templater** (`templater-obsidian`) — installed, no templates configured yet.
- **Excalidraw** (`obsidian-excalidraw-plugin`) — for diagrams.
- **Open in Terminal** (`open-in-terminal`) — opens terminal from Obsidian.

## Theme

Catppuccin (CSS theme).

## Notes

- No `.gitignore` or git repo — do not `git init` unless asked.
- `Daily/` notes use the `yyyy-MM-dd` format (Obsidian daily-notes default).
- Frontmatter tags are preferred over inline `#tags`.
