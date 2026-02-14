---
url: https://github.com/r2d4/rwx
type: github-repo
languages: [TypeScript]
tags: [ai-agents, feedback-loop, cli, automation, testing]
date_saved: 2026-02-14
---
# rwx (ralph, wiggum, execute)

## Summary
rwx is a CLI tool that runs AI agents (Claude Code, Codex) in an autonomous feedback loop against user-defined verification criteria. It iterates until tests pass or quality standards are met, checkpointing each attempt as a git commit.

## Key Points
- Define a task + success criteria, agent loops until verification passes
- Supports command-based verification (`npm test`) or agent-based verification (subjective quality checks)
- Git checkpoints every iteration for full audit trail and rollback
- Works with Claude Code and Codex, with passthrough args support
- Configurable limits: max iterations, max runtime, verification timeout

## Related
- [[roborev]] - continuous code review for agents
- [[agents-council]] - multi-agent collaboration
- [[codex-container]] - containerized Codex automation
