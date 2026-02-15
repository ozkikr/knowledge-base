---
url: https://research.google/blog/towards-a-science-of-scaling-agent-systems-when-and-why-agent-systems-work
type: article
tags: [multi-agent-systems, evaluation, ai-research]
date_saved: 2026-02-15
---
# Towards a science of scaling agent systems: When and why agent systems work
## Summary
Google Research presents evidence that “more agents” is not universally better for agentic tasks. Across a broad benchmark sweep, performance depended on alignment between task structure and coordination architecture. The article argues for principled design choices based on measurable task properties rather than heuristic multi-agent scaling.

## Key Points
- The study evaluated 180 configurations across single-agent and four multi-agent coordination styles.
- Parallelizable tasks benefited from coordination, while sequential reasoning tasks often degraded under multi-agent overhead.
- Tool-heavy tasks showed a coordination tax, where extra agents increased overhead disproportionately.
- Centralized orchestration reduced error amplification compared with independent agents.
- A predictive model using task properties selected near-optimal architectures on most unseen configurations.

## Related
- [[multi-agent-coordination]]
- [[benchmarking]]
- [[error-amplification]]
