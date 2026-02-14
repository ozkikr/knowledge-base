---
url: https://github.com/zed-industries/codex-acp
type: github-repo
languages: [Rust]
tags: [codex, acp, agent-protocol, zed, coding-agents]
date_saved: 2026-02-14
---
# Codex ACP

## Summary
An Agent Client Protocol (ACP) adapter for OpenAI's Codex CLI, enabling use from ACP-compatible clients like Zed. Supports context mentions, images, tool calls, edit review, TODO lists, and slash commands.

## Key Points
- Bridges OpenAI Codex CLI to ACP-compatible clients (Zed, others)
- Supports @-mentions, images, tool calls with permission requests
- Slash commands: /review, /review-branch, /review-commit, /init, /compact
- Auth via ChatGPT subscription, CODEX_API_KEY, or OPENAI_API_KEY
- Available via npm: npx @zed-industries/codex-acp

## Related
- [[superset]] - multi-agent orchestration
- [[ink]] - React CLI framework
- [[Continuous-Claude-v2]] - Claude Code tooling
