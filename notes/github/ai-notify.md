---
url: https://github.com/PaulRBerg/ai-notify
type: github-repo
languages: [Python]
tags: [macos, notifications, claude-code, codex-cli, developer-tools]
date_saved: 2026-02-14
---
# ai-notify

## Summary
A desktop notification system for Claude Code and Codex CLI on macOS. It tracks session activity via SQLite and sends macOS notifications for key events like completed long-running jobs. Features smart filtering by duration threshold and prompt patterns, with YAML-based configuration.

## Key Points
- Smart notifications only for jobs exceeding configurable duration threshold (default 10s)
- Prompt pattern filtering to exclude specific commands (e.g., /commit, /update-pr)
- SQLite-based session tracking with prompts, durations, and job numbers
- YAML configuration with sensible defaults; supports notification modes (all/permission_only/disabled)
- Requires Python 3.12+, uv package manager, and terminal-notifier on macOS

## Related
- [[claude-code-history-viewer]]
- [[claude-squad]]
