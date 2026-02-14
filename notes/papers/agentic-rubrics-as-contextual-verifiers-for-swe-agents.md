---
url: https://arxiv.org/abs/2601.04171
type: paper
tags: [swe-agents, verification, test-time-scaling, code-generation]
date_saved: 2026-02-14
---
# Agentic Rubrics as Contextual Verifiers for SWE Agents

## Summary
Proposes Agentic Rubrics: an expert agent interacts with a repository to create context-grounded rubric checklists, then candidate patches are scored against them without requiring test execution. Achieves 54.2% on SWE-Bench Verified with Qwen3-Coder-30B, outperforming baselines by 3.5+ percentage points.

## Key Points
- Verification is critical for RL reward signals and test-time scaling in SWE agents
- Code execution-based verification is hard to scale due to environment setup overhead
- Agentic Rubrics create codebase-specific checklists by having an agent explore the repo context
- Rubric scores are consistent with ground-truth tests while also flagging issues tests miss
- Agentic context gathering is essential for producing unambiguous, codebase-specific criteria

## Related
- [[swe-bench]]
- [[test-time-scaling]]
- [[code-verification]]
