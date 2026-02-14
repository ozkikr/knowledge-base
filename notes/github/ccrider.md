---
url: https://github.com/neilberkman/ccrider
type: github-repo
languages: [Go]
tags: [claude-code, tui, session-management, mcp]
date_saved: 2026-02-14
---
# ccrider

## Summary
ccrider is a Go-based TUI tool for searching, browsing, and resuming Claude Code sessions. It indexes sessions from `~/.claude/projects/` into SQLite with FTS5 for instant full-text search, and includes an MCP server so Claude can search past sessions.

## Key Points
- Interactive TUI browser for Claude Code session history
- Full-text search powered by SQLite FTS5
- Resume sessions directly from the TUI (auto-detects Ghostty, iTerm, Terminal.app)
- MCP server integration so Claude can recall past context
- Installable via Homebrew (`neilberkman/tap/ccrider`)

## Related
- [[claude-code]] [[mcp]] [[tui]] [[session-management]]
