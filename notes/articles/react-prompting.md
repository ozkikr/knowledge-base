---
url: https://www.promptingguide.ai/techniques/react
type: article
tags: [react-prompting, llm, prompt-engineering, reasoning, tool-use]
date_saved: 2026-02-14
---
# ReAct Prompting

## Summary
ReAct (Reasoning + Acting) is a prompting framework from Yao et al. (2022) where LLMs generate interleaved reasoning traces and task-specific actions. This enables models to interact with external tools (e.g., search engines, knowledge bases) for more reliable and factual responses.

## Key Points
- Combines chain-of-thought reasoning with action steps that interface with external environments
- Reasoning traces allow the model to plan, track progress, and handle exceptions; actions gather external information
- Outperforms baselines on knowledge-intensive tasks (HotPotQA, Fever) and decision-making tasks
- Best results come from combining ReAct with chain-of-thought (CoT) — leveraging both internal knowledge and external information
- Trajectories follow Thought → Action → Observation loops as few-shot exemplars

## Related
- [[chain-of-thought]]
- [[prompt-engineering]]
- [[tool-use]]
- [[llm-agents]]
