---
url: https://www.philschmid.de/context-engineering-part-2
type: article
tags: [context-engineering, agents, manus, context-rot, multi-agent]
date_saved: 2026-02-14
---
# Context Engineering for AI Agents: Part 2

## Summary
Expands on Manus's original context engineering post with updates from Peak Ji. Covers Context Rot (performance degrades as context fills, effective window <256k), Context Pollution (irrelevant info distracts LLM), and Context Confusion (conflicting instructions). Introduces compaction vs summarization hierarchy.

## Key Points
- Context Rot: LLM quality degrades well before hitting token limits (~256k effective)
- Prefer raw > Compaction (reversible) > Summarization (lossy) hierarchy
- Multi-agent: "Share memory by communicating, don't communicate by sharing memory" (Go-inspired)
- Discrete tasks get fresh sub-agent contexts; complex reasoning shares full history
- Manus keeps recent tool calls raw when summarizing to preserve model "rhythm"

## Related
- [[context-engineering]]
- [[multi-agent-systems]]
- [[ace]]
- [[tavily-deep-research]]
