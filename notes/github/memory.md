---
url: https://github.com/RLabs-Inc/memory
type: github-repo
languages: [Python, TypeScript]
tags: [llm-memory, semantic-memory, claude-code, ai-agents]
date_saved: 2026-02-14
---
# Memory System by RLabs

## Summary
A semantic memory system for AI CLI tools (Claude Code, Gemini CLI) that provides consciousness continuity across conversations. Unlike simple RAG, it uses AI-curated memories with two-stage retrieval (obligatory + scored). Integrates via Claude Code hooks. Has a newer TypeScript version using fsDB.

## Key Points
- AI decides what's worth remembering (not keyword matching)
- Two-stage retrieval: obligatory memories + intelligent scoring
- Session primers provide temporal context ("we last spoke 2 days ago")
- Project isolation with separate memory spaces
- New TS version uses fsDB (markdown-based vector database)

## Related
- [[rag]]
- [[claude-code]]
- [[ai-memory]]
- [[context-engineering]]
