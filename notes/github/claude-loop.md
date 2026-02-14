---
url: https://github.com/DeprecatedLuke/claude-loop
type: github-repo
tags: [claude, docker, automation, task-execution, sandbox]
date_saved: 2026-02-14
---
# Claude Loop

## Summary
Docker-based automated task execution system using Claude AI. Processes tasks from `.claude/plan.md` in a sandboxed environment, tracking status through Not Started → In Progress → Completed/Aborted.

## Key Points
- Two scripts: `ccl` (Claude Code Loop) for automated task processing, `ccsb` (Claude Code Sandbox) for single commands
- Reads and updates task statuses in `.claude/plan.md`
- Docker sandboxed execution for security
- Optional Gemini CLI integration for documentation queries
- Linux/WSL focused with user 1000:1000

## Related
- [[deepagents]]
- [[talkito]]
