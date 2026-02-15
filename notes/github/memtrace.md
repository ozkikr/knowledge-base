---
url: https://github.com/Basekick-Labs/memtrace
type: github-repo
languages: [Go, Python, TypeScript]
tags: [agent-memory, time-series, mcp]
date_saved: 2026-02-15
---
# memtrace
## Summary
Memtrace provides an LLM-agnostic operational memory layer for agents, built around temporal events rather than embeddings-first storage. It stores memories in a time-series database and returns session context as LLM-ready markdown. The system also ships with SDKs and MCP tooling for integration with coding assistants and agent frameworks.
## Key Points
- Captures episodic/decision/entity/session memories with tags, metadata, and importance.
- Uses time-windowed queries as a first-class retrieval primitive (e.g., last 2h).
- Offers REST API plus Python, TypeScript, and Go SDKs.
- Includes an MCP server exposing memory tools for Claude Code, Cursor, and related clients.
## Related
- [[Agent Memory]]
- [[Temporal Databases]]
- [[Model Context Protocol]]
