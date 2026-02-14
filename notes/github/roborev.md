---
url: https://github.com/wesm/roborev
type: github-repo
languages: [Go]
tags: [code-review, ai-agents, continuous-review, cli, tui]
date_saved: 2026-02-14
---
# roborev

## Summary
roborev provides continuous, non-invasive background code review for AI coding agents. It reviews every git commit automatically via hooks, surfaces issues in seconds, and can auto-fix findings by feeding them back to agents.

## Key Points
- Background reviews via git post-commit hooks — no workflow changes needed
- `roborev fix` feeds findings to an agent that applies fixes; `roborev refine` loops until reviews pass
- Built-in code analysis: duplication, complexity, refactoring, dead code, test fixtures
- Works with Codex, Claude Code, Gemini, Copilot, Cursor, and more
- Interactive TUI with vim-style navigation; runs fully locally

## Related
- [[rwx]] - autonomous agent feedback loops
- [[codex-container]] - containerized Codex environment
- [[memex]] - agent session search and history
