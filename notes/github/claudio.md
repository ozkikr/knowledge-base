---
url: https://github.com/Iron-Ham/claudio
type: github-repo
languages: [Go]
tags: [orchestration, git-worktree, terminal-ui]
date_saved: 2026-02-15
---
# Claudio
## Summary
Claudio orchestrates multiple AI coding agents in parallel by assigning each one an isolated git worktree. It combines CLI and TUI controls so teams can monitor, coordinate, and recover multi-agent sessions. The tool is aimed at reducing conflicts while speeding up concurrent implementation.

## Key Points
- Runs multiple Claude Code or Codex instances against the same repository.
- Uses git worktrees and per-instance branches for isolation and cleanup.
- Provides a real-time Bubble Tea TUI with output streaming and controls.
- Adds planning workflows like ultraplan, multi-pass planning, and task dependencies.
- Includes cost tracking, conflict detection, and PR automation options.

## Related
- [[Git Worktrees]]
- [[Claude Code]]
- [[Multi-Agent Orchestration]]
