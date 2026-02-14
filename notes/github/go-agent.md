---
url: https://github.com/Protocol-Lattice/go-agent
type: github-repo
languages: [Go]
tags: [agents, framework, multi-agent, rag, tool-calling]
date_saved: 2026-02-14
---
# Lattice go-agent - AI Agent Framework for Go

## Summary
Lattice is a Go agent framework with clean abstractions for LLMs, tool calling, RAG-powered memory, and multi-agent coordination. It provides pluggable LLM providers, UTCP support, and production-optimized performance with LRU caching and pre-allocated buffers.

## Key Points
- Modular architecture with declarative agent configuration
- Multi-agent support with shared catalog and delegation system
- RAG-powered memory with importance scoring and MMR retrieval
- Model agnostic: adapters for Gemini, Anthropic, Ollama
- High performance: 10-50x faster MIME normalization, LRU caching (184 ns/op)

## Related
- [[go-libraries]]
- [[ai-agents]]
- [[multi-agent-orchestration]]
