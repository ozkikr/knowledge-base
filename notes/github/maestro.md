---
url: https://github.com/uprockcom/maestro
type: github-repo
languages: [Go, Shell]
tags: [claude-code, docker, multi-agent, container-isolation]
date_saved: 2026-02-14
---
# Maestro

## Summary
A multi-container runtime for running multiple isolated Claude Code instances in parallel. Each task runs in its own Docker container with automatic git branch management, network firewalls, and persistent state for caches and history.

## Key Points
- Runs multiple Claude Code instances in isolated Docker containers
- Automatic git branch creation per task
- Network firewall with domain whitelisting
- Background daemon for token expiration monitoring and notifications
- Persistent npm/UV caches and command history across restarts

## Related
- [[Claude Code]]
- [[Docker]]
- [[CodeMachine-CLI]]
