---
url: https://www.factory.ai/using-linters-to-direct-agents
type: article
tags: [linters, ai-agents, agent-native-development, code-quality, automation]
date_saved: 2026-02-14
---
# Using Linters to Direct Agents

## Summary
Factory.ai argues that linters are the key enforcement mechanism for Agent-Native Development. By encoding architecture, boundaries, and conventions as lint rules, agents get automatic feedback, self-correct, and need fewer human interventions—making "lint green" the definition of done.

## Key Points
- New lint categories for agents: grep-ability, glob-ability, architectural boundaries, security, testability, observability
- Agents generate code → get lint feedback → self-heal until clean, reducing human bottleneck
- AGENTS.md explains the "why"; lint rules provide precise, machine-checkable enforcement
- "Lint passing" becomes a proxy for "conforms to architecture and best practices"
- Human feedback is the new bottleneck—pre-specify standards as lint rules to minimize back-and-forth

## Related
- [[agents-md]]
- [[writing-effective-tools-for-ai-agents]]
- [[claude-code-framework-wars]]
