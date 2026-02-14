---
url: https://github.com/onerun-ai/onerun
type: github-repo
tags: [llm-testing, ai-agents, conversation-simulation, evaluation]
date_saved: 2026-02-14
---
# OneRun AI

## Summary
Open-source platform for stress-testing LLMs and conversational AI. Simulates realistic user conversations at scale to identify hallucinations, policy violations, and edge cases. Also generates evaluation datasets and training data for fine-tuning.

## Key Points
- Simulates diverse personas and scenarios against AI agents for automated QA
- Generates judge-labeled datasets, preference pairs, and critique-and-revise triples
- Uses Temporal for workflow processing, PostgreSQL, FastAPI backend, Next.js frontend
- Docker Compose deployment with UI at localhost:3000
- Surfaces edge cases that manual testing misses through adversarial patterns

## Related
- [[llm-evaluation]]
- [[ai-agent-testing]]
- [[synthetic-data-generation]]
