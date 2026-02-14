---
url: https://github.com/airweave-ai/airweave
type: github-repo
languages: [Python, TypeScript]
tags: [rag, context-retrieval, ai-agents, data-sync, search]
date_saved: 2026-02-14
---
# Airweave - Context Retrieval Layer for AI Agents

## Summary
Airweave is an open-source context retrieval layer that connects to apps, tools, and databases, continuously syncs their data, and exposes it through a unified LLM-friendly search interface. AI agents query Airweave to retrieve relevant, grounded, up-to-date context from multiple sources.

## Key Points
- Connects to multiple apps/tools/databases with continuous data syncing
- Unified, LLM-friendly search interface for AI agents and RAG systems
- Docker-based deployment with start.sh automation
- Supports OpenAI and Mistral API keys for embeddings
- Uses Qdrant vector store, PostgreSQL, Redis, and Temporal under the hood

## Related
- [[gorag]] - Go RAG library with vector DB support
- [[essential-graphrag]] - GraphRAG approach to retrieval
- [[llm-sdk]] - unified LLM provider interface
