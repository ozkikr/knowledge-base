---
url: https://www.anthropic.com/engineering/writing-tools-for-agents
type: article
tags: [anthropic, mcp, tool-design, agents, evaluation]
date_saved: 2026-02-14
---
# Writing Effective Tools for AI Agents—Using AI Agents

## Summary
Anthropic's engineering guide on building high-quality tools for AI agents via MCP. Covers prototyping, evaluation-driven development, and collaborating with Claude Code to optimize tool performance. Tools are a new kind of software—contracts between deterministic systems and non-deterministic agents.

## Key Points
- Tools are contracts between deterministic systems and non-deterministic agents—design for agents, not APIs
- Build prototypes quickly, wrap in MCP servers, test with Claude Code or Desktop
- Create comprehensive evaluations to systematically measure tool performance
- Key principles: right tools, namespacing, meaningful context, token efficiency, prompt-engineered descriptions
- Tools most ergonomic for agents end up surprisingly intuitive for humans too

## Related
- [[using-linters-to-direct-agents]]
- [[agents-md]]
- [[claude-code-framework-wars]]
