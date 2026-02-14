---
url: https://factory.ai/news/evaluating-compression
type: article
tags: [context-compression, ai-agents, evaluation, llm-memory]
date_saved: 2026-02-14
---
# Evaluating Context Compression for AI Agents

## Summary
Factory.ai built an evaluation framework to measure how much context different compression strategies preserve for long-running AI agent sessions. They found structured summarization retains more useful information than alternatives from OpenAI and Anthropic, using probe-based evaluation across recall, artifact tracking, continuation, and decision dimensions.

## Key Points
- Long agent sessions generate millions of tokens; naive compression loses critical details
- Probe-based evaluation measures functional quality (not just ROUGE/similarity)
- Four probe types: Recall, Artifact, Continuation, Decision
- Six scoring dimensions: Accuracy, Context awareness, Artifact trail, Completeness, Continuity, Instruction following
- Key insight: optimize tokens per task, not tokens per request

## Related
- [[context-compression]]
- [[ai-agents]]
- [[Context-Engine]]
- [[agent-memory]]
