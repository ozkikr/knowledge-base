---
url: https://www.usetusk.ai/resources/similarity-scores-are-not-enough-for-matching
type: article
tags: [matching-systems, constraints, testing]
date_saved: 2026-02-15
---
# Similarity Scores Are Not Enough For Matching
## Summary
This post argues that robust matching systems should prioritize hard constraints before similarity scoring. Using Tusk Drift as a case study, it demonstrates how semantic and lifecycle guardrails prevent catastrophically wrong matches in replay testing. Similarity is still useful, but mainly as a tiebreaker after constraint-based filtering narrows the candidate set.

## Key Points
- Pure similarity can select invalid matches when method, lifecycle, or usage-state constraints are ignored.
- A priority cascade of constraints improves determinism and reduces false matches.
- Matching logic is structured across two axes: search scope and match granularity.
- Constraint metadata helps interpret whether deviations signal regressions or expected change.
- Most production requests are resolved before any expensive similarity computation is needed.

## Related
- [[constraint-satisfaction]]
- [[similarity-search]]
- [[deterministic-testing]]
