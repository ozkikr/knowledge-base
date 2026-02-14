---
url: https://github.com/lupantech/AgentFlow
type: github-repo
languages: [Python]
tags: [agents, optimization, rl, tool-use, research, iclr]
date_saved: 2026-02-14
---
# AgentFlow - In-the-Flow Agentic System Optimization

## Summary
AgentFlow is a trainable, tool-integrated agentic framework from Stanford that overcomes scalability and generalization limits of tool-augmented reasoning. It uses a modular architecture with four specialized modules (Planner, Executor, Verifier, Generator) and optimizes the planner agent using Flow-based Group Refined Policy Optimization (Flow-GRPO). Accepted at ICLR 2026.

## Key Points
- Modular architecture: Planner → Executor → Verifier → Generator (vs monolithic interleaved reasoning)
- Uses Flow-GRPO for online optimization of the planner agent
- Outperforms approaches like Search-R1 that train a single LLM for reasoning + tool calls
- Accepted at ICLR 2026 and NeurIPS 2025 Efficient Reasoning Workshop
- Achieves superior performance across diverse domains with improved tool calling

## Related
- [[feedback-loops-background-coding-agents-part-3]] - Verification loops for agents
- [[facilitating-ai-adoption-at-imprint]] - Agent adoption
