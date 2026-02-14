---
url: https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents
type: article
tags: [ai-agents, claude, context-management, long-running-tasks, anthropic]
date_saved: 2026-02-14
---
# Effective Harnesses for Long-Running Agents

## Summary
Anthropic engineering blog post describing how to enable agents to work effectively across many context windows on complex, multi-day tasks. They developed a two-fold solution: an initializer agent for first-run setup, and a coding agent that makes incremental progress while leaving clear artifacts for the next session.

## Key Points
- Core challenge: agents work in discrete sessions with no memory between context windows
- Without structure, even frontier models try to "one-shot" complex tasks and get derailed
- Solution uses an initializer agent + incremental coding agent pattern with the Claude Agent SDK
- Compaction alone isn't sufficient — agents need structured handoff artifacts between sessions
- Provides a quickstart repo with code examples for autonomous coding across multiple context windows

## Related
- [[claude-code]]
- [[context-engineering-for-agents]]
- [[ai-agents]]
- [[claude-agent-sdk-container]]
