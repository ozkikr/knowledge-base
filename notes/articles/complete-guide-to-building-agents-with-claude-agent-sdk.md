---
url: https://nader.substack.com/p/the-complete-guide-to-building-agents
type: article
tags: [claude-agent-sdk, ai-agents, typescript, anthropic, tutorial]
date_saved: 2026-02-14
---
# The Complete Guide to Building Agents with the Claude Agent SDK

## Summary
A hands-on tutorial for building AI agents using Anthropic's Claude Agent SDK. Walks through creating a code review agent that analyzes codebases for bugs and security issues, demonstrating the SDK's agent loop, built-in tools, and structured output capabilities.

## Key Points
- Claude Agent SDK is the infrastructure behind Claude Code, exposed as a library — handles the agent loop, tools, and context management
- Built-in tools: Read, Write, Edit, Bash, Glob, Grep, WebSearch, WebFetch — no implementation needed
- `query()` returns an async generator streaming messages (system/assistant/result) as the agent works
- Supports structured JSON Schema output for programmatic consumption of agent results
- Code review agent example: finds bugs, security issues, performance problems with file/line specificity
- Uses `permissionMode: "bypassPermissions"` for auto-approving read operations

## Related
- [[Claude Agent SDK]]
- [[AI Agents]]
- [[Claude Code]]
- [[Code Review]]
