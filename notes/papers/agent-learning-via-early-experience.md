---
url: https://arxiv.org/abs/2510.08558
type: paper
tags: [agents, reinforcement-learning, llm, self-improvement, world-models]
date_saved: 2026-02-14
---
# Agent Learning via Early Experience

## Summary
This paper proposes "early experience" as a middle-ground paradigm between imitation learning and full RL for training language agents. Instead of relying on expert demonstrations or reward signals, agents learn from their own interaction data where future states serve as supervision. Two strategies are studied: implicit world modeling and self-reflection.

## Key Points
- Addresses the gap between supervised fine-tuning on expert data and full RL with rewards
- Implicit world modeling: uses collected states to ground the policy in environment dynamics
- Self-reflection: agent learns from its suboptimal actions to improve reasoning
- Evaluated across 8 environments and multiple model families
- Early experience provides a strong foundation for subsequent RL, bridging imitation and experience-driven learning

## Related
- [[Reinforcement Learning from Human Feedback]]
- [[Language Agents]]
- [[Self-Reflection in AI]]
- [[World Models]]
