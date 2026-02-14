---
url: https://github.com/Dicklesworthstone/claude_code_agent_farm
type: github-repo
tags: [claude-code, parallel-agents, orchestration, tmux]
date_saved: 2026-02-14
---
# Claude Code Agent Farm

## Summary
Orchestration framework for running 20+ Claude Code agents in parallel for automated bug fixing and best-practices sweeps. Uses lock-based coordination and real-time tmux monitoring with support for 34 technology stacks.

## Key Points
- Run up to 50 parallel Claude Code agents with lock-based conflict prevention
- Supports bug fixing, best practices, and coordinated multi-agent workflows
- Real-time tmux dashboard with context warnings and heartbeat tracking
- Auto-recovery with adaptive idle timeout; agents auto-clear context near limits
- Rich HTML run reports with git commit diff summaries

## Related
- [[multi-agent-coding-system]]
- [[claude-squad]]
- [[claudebox]]
