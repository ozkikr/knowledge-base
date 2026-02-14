---
url: https://www.philschmid.de/agents-2.0-deep-agents
type: article
tags: [agents, deep-agents, sub-agents, planning, memory, context-engineering]
date_saved: 2026-02-14
---
# Agents 2.0: From Shallow Loops to Deep Agents

## Summary
An article by Philipp Schmid describing the architectural shift from shallow agents (simple while-loop tool-calling) to deep agents that combine explicit planning, hierarchical delegation via sub-agents, persistent memory, and extreme context engineering to solve complex multi-step problems.

## Key Points
- Shallow agents (1.0): single context window, stateless loop — fail at 50+ step tasks
- Four pillars of Deep Agents: explicit planning, hierarchical delegation, persistent memory, context engineering
- Explicit planning: maintain a plan document updated between every step
- Hierarchical delegation: orchestrator → specialized sub-agents with clean contexts
- Persistent memory: filesystem/vector DB as source of truth instead of context window
- Context engineering: better models need better context, not less prompting

## Related
- [[AI Agents]]
- [[Sub-Agents]]
- [[Agent Memory]]
- [[Context Engineering]]
