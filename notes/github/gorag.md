---
url: https://github.com/StacklokLabs/gorag
type: github-repo
languages: [Go]
tags: [rag, vector-database, embeddings, ollama, openai]
date_saved: 2026-02-14
---
# GoRag - Go Library for RAG Development

## Summary
GoRag is a Go library for building Retrieval-Augmented Generation (RAG) applications with multi-vector database support. It provides interfaces for Ollama and OpenAI backends, along with embeddings generation using local or hosted models.

## Key Points
- Supports multiple LLM backends: Ollama and OpenAI
- RAG/embeddings generation with local (mxbai-embed-large) or hosted models (text-embedding-ada-002)
- Multiple vector database support: PostgreSQL with pgvector and Qdrant
- Docker Compose setup for easy database provisioning
- Go-native interface design

## Related
- [[airweave]] - context retrieval for AI agents
- [[llm-sdk]] - unified LLM provider API
