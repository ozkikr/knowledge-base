---
url: https://hex.tech/blog/why-analytics-agents-break-differently/
type: article
tags: [ai-agents, analytics, context-engineering, data-analysis]
date_saved: 2026-02-14
---
# Why Analytics Agents Break Differently

## Summary
Hex's engineering team shares lessons from building their Notebook Agent for data analysts. The core insight: analytics agents break differently than coding agents because data requires discovered structure (not predetermined abstractions), and you can't compress actual data values without losing the ability to reason about them.

## Key Points
- Code compresses naturally via abstractions (functions, classes); data does not — "quarterly sales data" loses all analytical value
- A single cell output can consume 30,000+ tokens, making context windows a critical bottleneck
- Analysis requires judgment with no unit tests — questions are open-ended explorations, not binary outcomes
- Context compression that works for code fails for data: summarizing what code does preserves meaning, summarizing data values destroys it
- Large context windows alone don't solve the problem; they tried 1-2M token windows first
- Enterprise data environments with 200-column tables make the challenge worse

## Related
- [[context-engineering]]
- [[ai-agents]]
- [[data-analysis]]
