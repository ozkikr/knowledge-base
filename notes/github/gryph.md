---
url: https://github.com/safedep/gryph
type: github-repo
languages: [Go, JavaScript, TypeScript, Makefile]
tags: [audit-trail, security, agent-governance]
date_saved: 2026-02-15
---
# Gryph

## Summary
Gryph is a local-first audit trail tool for AI coding agents. It installs hooks into supported agents, captures events in SQLite, and exposes query and replay capabilities for debugging and governance. The project emphasizes transparency, privacy, and operational safety for agent-assisted development.

## Key Points
- Logs reads, writes, command executions, and session metadata for post-run analysis.
- Supports multiple agent ecosystems including Claude Code, Cursor, Gemini CLI, and others.
- Provides CLI commands for logs, filtered queries, exports, and retention management.
- Keeps data local by default with redaction and sensitive-file handling controls.
- Includes install/uninstall backup behavior for safer hook configuration changes.

## Related
- [[Audit Logging]]
- [[AI Agent Governance]]
- [[SQLite]]
