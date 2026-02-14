---
url: https://github.com/SDGLBL/mcp-claude-code
type: github-repo
tags: [mcp, claude-code, code-editing, agent-tools]
date_saved: 2026-02-14
---
# MCP Claude Code

## Summary
An MCP server implementing Claude Code-like capabilities, allowing Claude to execute file modifications, run commands, and manage code through the Model Context Protocol. Supports agent delegation, multi-LLM providers via LiteLLM, and Jupyter notebook editing.

## Key Points
- Provides tools: read, write, edit, grep, run_command, directory_tree, notebook support
- Agent delegation for concurrent sub-tasks
- Multiple LLM provider support via LiteLLM
- Security controls with permission prompts and restricted directory access
- Batch tool execution (parallel or serial)

## Related
- [[Model Context Protocol]]
- [[Claude Code]]
- [[coding-agents]]
- [[browser-use]]
