---
url: https://github.com/mem0ai/mem0/tree/main/openmemory
type: github-repo
tags: [memory-layer, llm-memory, mcp, local-first, open-source]
date_saved: 2026-02-14
---

# OpenMemory

## Summary
OpenMemory is a local-first, open-source personal memory layer for LLMs from the Mem0 project. It gives you a self-hosted MCP server and UI dashboard for storing, browsing, and managing memories that AI applications can access, keeping all data private and under your control.

## Key Points
- Runs locally via Docker with an MCP server (port 8765) and React UI (port 3000)
- One-command setup to connect to MCP clients (Cursor, Claude, etc.) via SSE
- Memories are portable and private — no data leaves your machine
- Requires only an OpenAI API key for embeddings/LLM interactions
- Part of the broader Mem0 ecosystem for AI memory management

## Related
- [[context-engineering-for-agents]] — memory as a context engineering strategy
- [[archgw]] — filter chains could integrate with memory layers
