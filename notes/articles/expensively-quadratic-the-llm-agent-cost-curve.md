---
url: https://blog.exe.dev/expensively-quadratic
type: article
tags: [llm-agents, prompt-caching, cost-optimization]
date_saved: 2026-02-15
---
# Expensively Quadratic: the LLM Agent Cost Curve
## Summary
This post analyzes why long-running coding-agent loops become expensive, even with prompt caching. The author shows that cache-read costs can dominate total spend as conversation length and call count grow, producing a practical quadratic-like curve. It combines conceptual diagrams, production telemetry, and simulation to argue for better orchestration strategies.

## Key Points
- Agent loops repeatedly resend growing context, causing cumulative cache-read overhead.
- In sample conversations, cache reads became the majority of total cost at moderate context lengths.
- Total cost depends on both token volume and number of LLM calls, not token length alone.
- Fewer turns, selective reset/new sessions, and off-context subagents can reduce spend.
- Cost management, context shaping, and orchestration design are tightly linked in practice.

## Related
- [[Agent Loops]]
- [[Prompt Caching]]
- [[Inference Cost Modeling]]
