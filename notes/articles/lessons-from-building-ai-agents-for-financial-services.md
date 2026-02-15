---
url: https://www.nicolasbustamante.com/p/lessons-from-building-ai-agents-for
type: article
tags: [ai-agents, financial-services, production-systems]
date_saved: 2026-02-15
---
# Lessons from Building AI Agents for Financial Services
## Summary
This post distills production lessons from building high-stakes financial agents where precision and trust are non-negotiable. It argues for sandboxed execution, filesystem-native workflows, and domain-specific data normalization over generic scaffolding. The author also highlights skills-based extensibility, long-running orchestration, and rigorous eval/monitoring as core pillars.

## Key Points
- Treats secure sandboxing and strict isolation as mandatory for agent code execution.
- Emphasizes context engineering via heavy normalization of messy financial source data.
- Details why parsing SEC filings and table-heavy documents is a major hidden challenge.
- Frames markdown “skills” as the practical product interface for domain workflows.
- Encourages architecture that anticipates rapid model improvement and obsolescence of scaffolding.

## Related
- [[financial-ai]]
- [[sandboxed-agents]]
- [[context-engineering]]
