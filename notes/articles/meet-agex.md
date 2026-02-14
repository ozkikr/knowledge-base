---
url: https://ashenfad.github.io/agex/announce/
type: article
tags: [agentic-framework, python, code-agents]
date_saved: 2026-02-14
---
# Meet Agex

## Summary
Agex is a Python-native agentic framework where agents work directly with existing libraries and runtime, avoiding JSON serialization and tool abstractions. Agents think in code (like smol-agents) but focus on interoperability, passing complex Python objects like DataFrames and Plotly figures between agent and user code.

## Key Points
- Code-as-Action: AST-style Python sandbox for agent actions
- Library integration via modules rather than tool wrappers (skip the JSON)
- Agents live in a persistent Python REPL, building helpers over time
- Workspace persistence with git-like versioning and time-travel debugging
- Multi-agent orchestration support

## Related
- [[ai-agents]]
- [[smol-agents]]
- [[python-frameworks]]
