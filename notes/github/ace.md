---
url: https://github.com/ace-agent/ace
type: github-repo
languages: [Python]
tags: [context-engineering, self-improving-llm, agentic, framework]
date_saved: 2026-02-14
---
# ACE - Agentic Context Engineering

## Summary
ACE is a framework that enables LLMs to self-improve by treating contexts as evolving playbooks. It uses a three-role architecture (Generator, Reflector, Curator) to accumulate, refine, and organize strategies through generation, reflection, and curation. Achieves +10.6% on agent tasks and +8.6% on domain benchmarks with 86.9% lower adaptation latency.

## Key Points
- Three-role agentic architecture: Generator, Reflector, Curator
- Incremental delta updates preserve prior knowledge while adding new insights
- Self-supervised learning without labeled data
- 86.9% lower adaptation latency vs existing methods
- Matches GPT-4.1 on AppWorld using smaller open-source models

## Related
- [[context-engineering]]
- [[self-improving-agents]]
- [[prompt-optimization]]
