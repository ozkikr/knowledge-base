---
url: https://github.com/louisho5/picobot
type: github-repo
languages: [Go, Dockerfile]
tags: [self-hosted, lightweight, telegram-bot]
date_saved: 2026-02-15
---
# Picobot
## Summary
Picobot is a lightweight self-hosted AI agent packaged as a small Go binary designed for constrained environments. It offers persistent memory, built-in tools, skills, and messaging integration while avoiding heavyweight Python/Node stacks. The project targets “runs anywhere” deployment, from cheap VPS instances to low-power devices.

## Key Points
- Prioritizes low footprint (small binary, low RAM, quick startup) and simple operations.
- Includes built-in tools for filesystem, shell execution, web fetch, messaging, cron, and skill management.
- Provides markdown-based persistent memory with retrieval and ranking commands.
- Supports Telegram gateway workflows and straightforward Docker deployment.
- Designed as an OpenClaw-inspired agent with minimal dependencies.

## Related
- [[self-hosted-agents]]
- [[go-cli]]
- [[agent-memory]]
