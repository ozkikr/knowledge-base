---
url: https://allenai.org/blog/open-coding-agents
type: article
tags: [coding-agents, open-source, fine-tuning, swe-bench, ai2, sera]
date_saved: 2026-02-14
---
# Open Coding Agents: Fast, Accessible Coding Agents (Ai2 SERA)

## Summary
Ai2 released SERA (Soft-verified Efficient Repository Agents), a family of open coding agent models that can be adapted to private codebases at low cost. SERA-32B solves 54.2% of SWE-Bench Verified problems, matching prior state-of-the-art at 57× lower cost than SWE-smith and 26× lower than SkyRL. They also released SERA-14B.

## Key Points
- SERA models are optimized and compatible with Claude Code out of the box
- Training requires only ~40 GPU days on 2 NVIDIA Hopper GPUs, costing ~$400-$12,000
- Can be specialized to private/internal codebases including full engineering stack and conventions
- All components are open: models, Claude Code integration, training recipes, and training data
- Achieves ~1,950-8,600 peak output tokens/sec depending on precision and hardware

## Related
- [[swe-bench]]
- [[coding-agents]]
- [[fine-tuning]]
- [[claude-code]]
