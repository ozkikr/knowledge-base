---
url: https://github.com/avocadodb/avocadodb
type: github-repo
languages: [Rust]
tags: [database, rag, deterministic, embeddings, ai-agents]
date_saved: 2026-02-14
---
# AvocadoDB - Deterministic Context Database for AI Agents

## Summary
AvocadoDB is a span-based context compiler that replaces traditional vector databases' non-deterministic "top-k" retrieval with deterministic, citation-backed context generation. It uses pure Rust embeddings for 6x faster performance than OpenAI, works completely offline, and costs nothing.

## Key Points
- 100% deterministic: same query → same context, every time
- Pure Rust embeddings — 6x faster than OpenAI (40-60ms vs 240-360ms), zero API cost
- Works fully offline after initial setup
- Every span has exact line number citations for verifiability
- 95%+ token budget utilization (vs 60-70% with traditional RAG)
- Drop-in replacement for vector databases with any LLM

## Related
- [[WeKnora]] - RAG framework
- [[late-chunking]] - Improved embedding approach
- [[mnemo]] - Context caching for AI assistants
