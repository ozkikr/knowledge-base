---
url: https://github.com/mstsirkin/interminai
type: github-repo
languages: [JavaScript]
tags: [ai-agents, terminal, pty, automation, tui]
date_saved: 2026-02-14
---
# interminai - Interactive Terminal for AI

## Summary
interminai is a PTY proxy that enables AI agents to interact with interactive CLI applications like vim, git rebase -i, gdb, and other TUI programs. It wraps interactive programs in a pseudo-terminal, captures screen output as text, and provides an API for sending input.

## Key Points
- Screen capture reads terminal display as ASCII text; input control sends keystrokes and control sequences
- Supports daemon mode for long-lived interactive sessions
- Use cases: AI agents editing files in vim, automated git operations, debugging with gdb, TUI apps
- Works with Claude Code, Cursor, Codex, Gemini CLI, and other skills-compatible agents
- Installable via `npx skills add mstsirkin/interminai`

## Related
- [[claude-code]]
- [[pty]]
- [[terminal-automation]]
