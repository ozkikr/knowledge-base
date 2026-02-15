---
url: https://github.com/typedef-ai/fenic
type: github-repo
languages: [Python, Rust, Just, Shell]
tags: [context-engineering, agent-frameworks, mcp]
date_saved: 2026-02-15
---
# fenic
## Summary
fenic is a declarative context-engineering layer for agent systems that works across frameworks instead of replacing runtime stacks. It combines deterministic and semantic transforms (extract, summarize, embed, retrieve) and exposes typed, bounded outputs as tools. The project emphasizes inference offloading so agents keep smaller, cleaner reasoning contexts.

## Key Points
- Provides composable context operations in Python/SQL-style workflows.
- Supports memory, retrieval, and structured context pipelines with typed schemas.
- Can expose generated capabilities as MCP tools or direct Python functions.
- Focuses on reducing context bloat by doing heavy semantic work outside the agent prompt.
- Designed for framework interoperability rather than lock-in.

## Related
- [[Context Engineering]]
- [[MCP Tools]]
- [[Agent Memory]]
