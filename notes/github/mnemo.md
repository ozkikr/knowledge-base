---
url: https://github.com/Logos-Flux/mnemo
type: github-repo
languages: [TypeScript]
tags: [mcp, gemini, context-caching, rag, ai-memory]
date_saved: 2026-02-14
---
# Mnemo - Extended Memory for AI Assistants

## Summary
Mnemo is an MCP server that leverages Gemini's 1M token context window and context caching to give AI assistants like Claude access to large codebases, documentation, PDFs, and URLs. Instead of complex RAG pipelines, it loads entire codebases into Gemini's cache for perfect recall at lower cost.

## Key Points
- Uses Gemini context caching instead of RAG — no chunking, embeddings, or vector databases needed
- Supports GitHub repos (public/private), URLs, PDFs, JSON APIs, and local files
- Cached tokens cost 75-90% less than regular input tokens
- Can be deployed locally, as a self-hosted Cloudflare Worker, or via hosted service
- Claude orchestrates while Gemini holds the context

## Related
- [[WeKnora]] - RAG framework for document understanding
- [[late-chunking]] - Alternative approach to embedding long documents
- [[avocadodb]] - Deterministic context database for AI agents
