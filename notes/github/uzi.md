---
url: https://github.com/devflowinc/uzi
type: github-repo
languages: [Go]
tags: [ai-coding, parallel-agents, git-worktrees, tmux, developer-tools]
date_saved: 2026-02-14
---
# Uzi

## Summary
Uzi is a CLI tool for running large numbers of coding agents (Claude, Codex, etc.) in parallel using Git worktrees for isolation. It manages tmux sessions, development server ports, and provides monitoring, broadcasting, and checkpoint/merge workflows.

## Key Points
- Run multiple AI coding agents in parallel with isolated Git worktrees
- Automatic tmux session and development server port management
- `uzi auto` mode for auto-confirming all tool calls
- `uzi broadcast` to send instructions to all running agents simultaneously
- `uzi checkpoint` for easy merging of completed agent work back to main branch

## Related
- [[claude-squad]]
- [[claude-code]]
- [[git-worktrees]]
- [[parallel-agents]]
