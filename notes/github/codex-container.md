---
url: https://github.com/DeepBlueDynamics/codex-container
type: github-repo
languages: [PowerShell, Bash]
tags: [docker, codex, automation, mcp, ai-agents]
date_saved: 2026-02-14
---
# Gnosis Container (codex-container)

## Summary
Gnosis Container launches a Docker container where OpenAI Codex has access to 275+ tools, cron scheduling, sub-agents, web crawling, file watchers, and shell commands. It provides sandboxed, one-shot, or API modes with configurable power levels.

## Key Points
- One script launches a fully-equipped Codex Docker environment with MCP tools
- Three modes: one-shot CLI, HTTP API server, and full-power interactive
- Sandboxed by default; `-Danger` and `-Privileged` flags for escalated access
- Session recording/playback via asciinema integration
- Supports session resumption by ID

## Related
- [[rwx]] - autonomous agent loops
- [[roborev]] - continuous code review for agents
- [[mcp-agent-mail]] - multi-agent coordination
