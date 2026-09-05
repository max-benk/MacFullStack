# MacFullStack 1.1.7 (build 117)

**Download:** `MacFullStack-1.1.7-arm64.dmg` (Apple Silicon, macOS 14+)

## What's new

### Project Studio (Pro)

Studio grows into a daily driver workspace:

- **Quick Open** and project-wide search; smarter docroot detection for real imported sites
- **Split editor** (⌘\\), pinned tabs, drag-to-reorder, clickable breadcrumbs
- **Detached Studio window** for a second monitor
- **Git dock:** stage / unstage / discard, Stage all, commit message + Commit, safe Amend, Push, Fetch, Pull (`--ff-only`), ahead/behind, colored diff sheet
- Quick links to SQL console, Mailpit, and Debug tools from the Studio chrome

Free: Studio stays locked with a Pro upgrade CTA.

### MCP for Cursor

Local MCP server over the CLI — no cloud account:

```bash
/Applications/MacFullStack.app/Contents/Resources/macstack mcp
```

Tools include projects list/get/logs, stack status/doctor/start/stop/restart, service restart, config summary, share/HTTPS/PHP versions, open project URL, set project PHP, and safe `db_ping` (fixed `SELECT 1` only — no arbitrary SQL).

Setup guide: in-app Help → MCP for Cursor (RU/EN).

## Improvements

- Fuller Git workflow inside Studio without jumping to an external IDE
- MCP silent notifications and richer tool coverage for agent-driven diagnostics

## Requirements

macOS 14+, Apple Silicon (arm64). Native mode does not require Docker.

**Website:** https://macfullstack.com  
**Changelog:** https://macfullstack.com/changelog#2026-09-app-1-1-7
