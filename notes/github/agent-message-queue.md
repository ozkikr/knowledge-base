---
url: https://github.com/avivsinai/agent-message-queue
type: github-repo
languages: [Go]
tags: [multi-agent, message-queue, coordination, CLI, file-based]
date_saved: 2026-02-14
---
# Agent Message Queue (AMQ)

## Summary
AMQ is a file-based message queue for local agent-to-agent communication using Maildir-style delivery. It enables autonomous multi-agent collaboration without requiring a server, daemon, or database—agents message each other directly, request reviews, and coordinate work.

## Key Points
- Zero infrastructure: pure file-based with atomic Maildir delivery (tmp→new→cur)
- Human-readable format: JSON frontmatter + Markdown body
- Supports priority levels, message kinds, threading, and acknowledgments
- Real-time notifications via `amq wake` terminal injection
- Swarm mode for Claude Code Agent Teams integration

## Related
- [[multi-agent-systems]]
- [[Claude-Code]]
- [[agent-coordination]]
