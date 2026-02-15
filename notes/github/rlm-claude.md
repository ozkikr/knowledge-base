---
url: https://github.com/EncrEor/rlm-claude
type: github-repo
languages: [Python, Shell, Dockerfile]
tags: [memory, claude-code, mcp]
date_saved: 2026-02-15
---
# RLM Claude
## Summary
RLM Claude is an MCP memory server that adds persistent, cross-session memory to Claude Code workflows. It stores both distilled insights and chunked conversation history, then exposes search and retention tools for recall. The project is designed to reduce context loss after compaction and improve long-running development continuity.

## Key Points
- Provides memory primitives for remember/recall/forget and chunk-level history navigation.
- Adds hooks that auto-save snapshots before compact operations remove active context.
- Includes hybrid retrieval options (BM25 + optional semantic embeddings) for richer search.
- Supports multi-project organization and lifecycle retention (active/archive/purge).

## Related
- [[Agent memory]]
- [[Claude Code]]
- [[Context compaction]]
