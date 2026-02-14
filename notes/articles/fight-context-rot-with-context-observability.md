---
url: https://blog.nilenso.com/blog/2025/10/29/fight-context-rot-with-context-observability/
type: article
tags: [context-engineering, observability, llm, context-window, nilenso]
date_saved: 2026-02-14
---
# Fight Context Rot with Context Observability

## Summary
You can't fix what you can't see. The author built context-viewer, a tool that pulls apart LLM context into meaningful components you can see, measure, and engineer. Existing observability tools focus on system metrics but miss what's actually crowding the context window.

## Key Points
- Context engineering is critical but lacks proper observability tooling
- Existing tools focus on latency/cost/error rates, not context content
- Context rot happens when irrelevant content accumulates in the context window
- Built context-viewer to segment, classify, and visualize context composition
- References Drew Breunig's work on how long contexts fail

## Related
- [[context-viewer]]
- [[context-engineering]]
- [[llm-observability]]
