---
url: https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents
type: article
tags: [ai-agents, evaluations, testing, llm-ops]
date_saved: 2026-02-14
---
# Demystifying Evals for AI Agents

## Summary
Anthropic's guide to building rigorous evaluations for AI agents. Covers the structure of agent evals—tasks, trials, graders, transcripts, and outcomes—and shares practical lessons from internal work and customer deployments at the frontier of agent development.

## Key Points
- Agent evals are harder than single-turn evals because mistakes propagate across multi-turn tool use and state modifications
- Key eval components: tasks, trials (multiple runs for consistency), graders (scoring logic), transcripts (full trace), and outcomes (final environment state)
- Frontier models can find creative solutions that surpass static eval expectations (e.g., Opus 4.5 discovering policy loopholes)
- An evaluation harness runs evals end-to-end; an agent harness/scaffold enables the model to act as an agent
- Good evals make behavioral changes visible before production, and their value compounds over the agent lifecycle

## Related
- [[building-effective-agents]]
- [[test-time-scaling]]
- [[agent-scaffolding]]
