---
url: https://github.com/Agent-on-the-Fly/Memento
type: github-repo
tags: [llm-agents, continual-learning, case-based-reasoning, mcp, memory]
date_saved: 2026-02-14
---
# Memento: Fine-tuning LLM Agents without Fine-tuning LLMs

## Summary
A memory-based continual learning framework that improves LLM agents from experience without updating model weights. Uses a planner-executor architecture with case-based reasoning (CBR) to store and retrieve successful trajectories from a Case Bank.

## Key Points
- No weight updates — reframes continual learning as memory-based online RL over a memory-augmented MDP
- Two-stage planner-executor loop: CBR-driven Planner decomposes tasks; Executor runs subtasks via MCP tools
- Comprehensive tool ecosystem (web search, doc processing, code execution, media analysis) through unified MCP interface
- Competitive results on GAIA, DeepResearcher, SimpleQA, and HLE benchmarks
- Supports both parametric and non-parametric case-based reasoning

## Related
- [[mcp]]
- [[agent-memory]]
- [[case-based-reasoning]]
- [[llm-agents]]
