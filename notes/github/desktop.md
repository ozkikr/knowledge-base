---
url: https://github.com/agentify-sh/desktop
type: github-repo
languages: [JavaScript]
tags: [mcp, ai-agents, browser-automation, codex, chatgpt]
date_saved: 2026-02-14
---
# Agentify Desktop

## Summary
Agentify Desktop is a local-first app that lets AI coding tools (like Codex) drive web AI subscriptions (ChatGPT, Claude, etc.) through real logged-in browser sessions via MCP. It supports parallel tabs, file uploads, and image downloads with a human-in-the-loop CAPTCHA policy.

## Key Points
- Exposes MCP server so tools like Codex can send prompts to ChatGPT web UI
- Supports parallel jobs via separate browser windows with shared login
- Human-in-the-loop CAPTCHA handling (pauses and waits for manual completion)
- Currently supports ChatGPT; Claude, Grok, AI Studio planned
- Local-first architecture with governor safety limits

## Related
- [[mcporter]]
- [[mcp]]
- [[ai-agents]]
