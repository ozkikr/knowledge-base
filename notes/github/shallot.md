---
url: https://github.com/dylanebert/shallot
type: github-repo
tags: [claude-code, context-management, developer-tools]
date_saved: 2026-02-14
---
# Shallot

## Summary
A lightweight, unopinionated context management system for Claude Code. Organizes project context in tiered layers (global, project, folder, implementation) to keep the context window focused and maintain important decisions across conversations.

## Key Points
- Four-tier context: CLAUDE.md → structure.md → context.md → code
- `/peel` command loads relevant context at conversation start
- `/nourish` updates context after completing work
- Encourages small, focused conversations targeting single tasks
- Persists architecture decisions and coding patterns between sessions

## Related
- [[Claude Code]]
- [[context-engineering]]
- [[AGENTS.md]]
