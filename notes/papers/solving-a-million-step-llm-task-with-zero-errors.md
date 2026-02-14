---
url: https://arxiv.org/abs/2511.09030
type: paper
tags: [llm-agents, multi-agent, error-correction, scalability, decomposition]
date_saved: 2026-02-14
---
# Solving a Million-Step LLM Task with Zero Errors

## Summary
This paper introduces MAKER, the first system to successfully solve a task with over one million LLM steps with zero errors. It relies on extreme decomposition into subtasks handled by focused microagents, combined with multi-agent voting for error correction at each step.

## Key Points
- LLMs have persistent error rates that prevent scaling beyond a few hundred dependent steps
- MAKER uses Massively Decomposed Agentic Processes (MDAPs) to break tasks into microagent-sized subtasks
- Error correction via efficient multi-agent voting scheme at each step
- Demonstrated on Towers of Hanoi benchmark domain at million-step scale
- Suggests MDAPs may solve organization/society-level problems without relying solely on improving individual LLMs

## Related
- [[multi-agent-systems]]
- [[llm-reasoning]]
- [[error-correction]]
- [[scalability]]
