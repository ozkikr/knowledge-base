---
url: https://github.com/srfrog/goldie-mcp
type: github-repo
languages: [Go, Makefile]
tags: [mcp, rag, local-search]
date_saved: 2026-02-15
---
# Goldie MCP
## Summary
Goldie is a local RAG-oriented MCP server implemented in Go for semantic indexing and retrieval on developer machines. It supports multiple embedding backends, including local MiniLM and Ollama models, and stores vectors in SQLite via sqlite-vec. The project emphasizes practical, local-first memory and recall workflows for agent tools.

## Key Points
- Indexes content, files, and directories with chunking and overlap strategies.
- Uses semantic similarity search and higher-level recall utilities for conversational retrieval.
- Supports backend selection between ONNX-based MiniLM and Ollama embedding models.
- Provides MCP-ready integration patterns for Claude Code, Claude Desktop, and Codex.

## Related
- [[Model Context Protocol]]
- [[Local RAG]]
- [[Semantic search]]
