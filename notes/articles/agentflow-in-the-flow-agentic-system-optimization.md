---
url: https://agentflow.stanford.edu/
type: paper
tags: [agents, reinforcement-learning, tool-use, planning, multi-turn-reasoning]
date_saved: 2026-02-14
---
# AgentFlow: In-the-Flow Agentic System Optimization

## Summary
AgentFlow is a trainable agentic framework from Stanford that coordinates four modules (planner, executor, verifier, generator) through evolving memory. It introduces Flow-GRPO for on-policy training inside multi-turn loops, achieving ICLR 2025 Oral (Top 1.1%).

## Key Points
- Four specialized modules: Planner, Executor, Verifier, Generator coordinated via shared memory
- Flow-GRPO converts multi-turn optimization into tractable single-turn policy updates
- 7B-scale backbone outperforms GPT-4o on multiple benchmarks
- Average accuracy gains: 14.9% search, 14.0% agentic, 14.5% math, 4.1% scientific tasks
- Formalized as multi-turn Markov Decision Process (MDP)

## Related
- [[dspy]]
- [[reinforcement-learning]]
- [[agents-towards-production]]
