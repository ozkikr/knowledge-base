---
url: https://github.com/lechgu/tichy
type: github-repo
languages: [Go, Python, Dockerfile]
tags: [rag, local-ai, privacy, llm]
date_saved: 2026-02-15
---
# tichy
## Summary
Tichy is a self-hosted, privacy-focused RAG system written primarily in Go. It keeps data local and is designed to run with Dockerized services for LLM inference, embeddings, and Postgres-backed retrieval. The project includes ingestion, chat, testing, and evaluation workflows.
## Key Points
- End-to-end local RAG pipeline with no required external hosted LLM dependency.
- Includes document ingest, interactive chat, test generation, and evaluation commands.
- Uses Docker Compose for service orchestration and supports GPU-backed inference setups.
- Organized as a practical CLI-first system for reproducible local experiments.
## Related
- [[RAG]]
- [[Local LLM]]
- [[Vector Search]]
