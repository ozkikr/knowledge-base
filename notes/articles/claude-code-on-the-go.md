---
url: https://granda.org/en/2026/01/02/claude-code-on-the-go/
type: article
tags: [claude-code, mobile-dev, tmux, mosh, remote-workflows]
date_saved: 2026-02-15
---
# Claude Code On-The-Go
## Summary
A field report on running multiple Claude Code agents entirely from a phone using Termius, mosh, tmux, and a cloud VM, with webhook-triggered push notifications for async interaction.

## Key Points
- Uses mobile-first remote development with resilient shell sessions via mosh + tmux.
- Adds automation hooks (`PreToolUse`) to notify the user when agent input is required.
- Combines VM lifecycle scripts, Tailscale networking, and worktrees for parallel task execution.
- Shows a practical pattern for asynchronous, interruption-friendly coding workflows.

## Related
- [[how-to-use-claude-code-to-wield-coding-agent-clusters]]
- [[feedback-loops-background-coding-agents-part-3]]
