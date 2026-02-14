---
url: https://www.dbreunig.com/2025/06/26/how-to-fix-your-context.html
type: article
tags: [llm, context-management, rag, prompt-engineering]
date_saved: 2026-02-14
---
# How to Fix Your Context

## Summary
A practical guide to mitigating long-context failures in LLMs, covering tactics like RAG, tool loadout, context quarantine, pruning, summarization, and offloading. Follows up on the author's earlier piece "How Long Contexts Fail."

## Key Points
- Context failures include poisoning, distraction, confusion, and clash — all stem from poor information management
- RAG remains relevant even with huge context windows; treating context like a junk drawer degrades responses
- Tool loadout (selecting only relevant tools) becomes critical above 30 tools; RAG on tool descriptions yields 3x better accuracy
- Context quarantine isolates tasks into dedicated threads to prevent cross-contamination
- Context pruning, summarization, and offloading help keep working context lean and focused

## Related
- [[rag]]
- [[prompt-engineering]]
- [[context-window]]
- [[tool-use]]
