---
url: https://github.com/superfly/contextwindow
type: github-repo
languages: [Go]
tags: [llm, agents, context-window, sqlite, go]
date_saved: 2026-02-14
---
# ContextWindow

## Summary
A low-level Go library by Fly.io for managing LLM agent conversations. Supports tool calls, token tracking, summary-based compression, and automatic SQLite persistence. Designed for multi-context agents where multiple concurrent conversations are natural.

## Key Points
- Manages LLM conversation sessions with automatic SQLite persistence
- Supports tool/function calling with simple function definitions
- Summary-based compression for long conversations
- Designed for multi-context agents (2, 10, or 100 concurrent conversations)
- Under the hood, a "context window" is just a list of strings — no session drama

## Related
- [[llm-tooling]]
- [[go]]
- [[ai-agents]]
- [[context-engineering]]
