---
url: https://arxiv.org/abs/2510.04618
type: paper
tags: [context-engineering, agent-systems, self-improving-llms]
date_saved: 2026-02-15
---
# Agentic Context Engineering: Evolving Contexts for Self-Improving Language Models
## Summary
The paper presents ACE (Agentic Context Engineering), a framework for iteratively improving prompts and memory-like contexts without weight updates. ACE treats context as an evolving playbook and uses generation, reflection, and curation to avoid brevity bias and context collapse. Across agentic and domain benchmarks, it reports stronger performance with lower adaptation overhead.

## Key Points
- Reframes adaptation as context evolution rather than model fine-tuning.
- Uses modular update stages to preserve detailed knowledge over repeated edits.
- Supports both offline context optimization (e.g., system prompts) and online memory updates.
- Reports notable benchmark improvements, including gains in agent and finance settings.
- Demonstrates adaptation from natural execution feedback, reducing dependence on labeled supervision.

## Related
- [[context-engineering]]
- [[agent-memory]]
- [[adaptive-prompting]]
