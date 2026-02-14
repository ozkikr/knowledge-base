---
url: https://huggingface.co/blog/Tavily/tavily-deep-research
type: article
tags: [deep-research, agents, context-engineering, search, tavily]
date_saved: 2026-02-14
---
# Building Deep Research: How Tavily Achieved State of the Art

## Summary
Tavily shares lessons from building a state-of-the-art research agent. Key themes: simplifying orchestration and leaning into agent autonomy, context engineering as curation (not accumulation), and productionizing non-deterministic agents. They rebuilt from scratch after their first architecture couldn't absorb next-gen model improvements.

## Key Points
- Agent harness should be simple and absorb future model improvements
- Context engineering = curation, not dumping tokens into the window
- Tools should do context engineering on the tool side, returning only relevant data
- Had to rebuild entire system after first architecture's assumptions became bottlenecks
- Research agents are becoming core subcomponents of broader agentic workflows

## Related
- [[context-engineering]]
- [[research-agents]]
- [[agent-harness]]
