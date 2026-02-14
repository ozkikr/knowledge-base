---
url: https://blog.langchain.com/context-engineering-for-agents/
type: article
tags: [context-engineering, agents, langgraph, llm-architecture, memory]
date_saved: 2026-02-14
---

# Context Engineering for Agents

## Summary
LangChain's deep dive into context engineering — the art of filling an LLM's context window with the right information at each step. The post categorizes strategies into four buckets (write, select, compress, isolate) with examples from Claude Code, ChatGPT, Cursor, and research papers.

## Key Points
- Context window is like RAM; context engineering is the OS managing what fits — coined/popularized by Karpathy
- Four strategy buckets: **Write** (scratchpads, memories), **Select** (retrieve relevant context), **Compress** (summarize), **Isolate** (sub-agents with separate contexts)
- Long contexts cause poisoning, distraction, confusion, and clash — problems outlined by Drew Breunig
- Scratchpads persist info within a session; memories persist across sessions (episodic, procedural, semantic)
- LangGraph designed around these patterns with state management and persistence primitives

## Related
- [[openmemory]] — implementation of the "write/select memories" pattern
- [[plandex]] — uses context management for large codebases
