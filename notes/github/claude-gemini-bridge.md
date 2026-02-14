---
url: https://github.com/tkaufmann/claude-gemini-bridge
type: github-repo
tags: [claude-code, gemini, code-analysis, hooks, delegation]
date_saved: 2026-02-14
---

# Claude-Gemini Bridge

## Summary
An intelligent integration that automatically delegates complex code analysis tasks from Claude Code to Google Gemini via hooks. Combines Claude's reasoning with Gemini's large context processing power for large-scale code analysis.

## Key Points
- Uses Claude Code PreToolUse hooks to intercept and delegate tasks
- Decision engine determines when to route to Gemini vs handle locally
- Includes caching layer, path converter, and Gemini CLI integration
- One-command install with automatic hook merging into ~/.claude/settings.json
- Transparent to the user — just use Claude Code normally

## Related
- [[mcphost]] - multi-provider LLM host
- [[claude-code-openai-wrapper]] - Claude Code API compatibility
- [[ab-mcts]] - multi-model cooperation research
