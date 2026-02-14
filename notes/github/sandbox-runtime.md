---
url: https://github.com/anthropic-experimental/sandbox-runtime
type: github-repo
languages: [TypeScript, JavaScript]
tags: [sandboxing, security, ai-agents, claude-code]
date_saved: 2026-02-14
---
# Anthropic Sandbox Runtime (srt)

## Summary
A lightweight sandboxing tool from Anthropic that enforces filesystem and network restrictions on arbitrary processes at the OS level, without requiring containers. Uses native OS primitives (sandbox-exec on macOS, bubblewrap on Linux) and proxy-based network filtering, designed to sandbox AI agents, MCP servers, and bash commands.

## Key Points
- Secure-by-default: processes start with minimal access, you explicitly allow what's needed
- Network restrictions control which hosts/domains can be accessed
- Filesystem restrictions limit directory and file access
- Built for Claude Code to enable safer AI agents
- Installable via npm: `npm install -g @anthropic-ai/sandbox-runtime`

## Related
- [[claude-code]]
- [[mcp]]
- [[ai-safety]]
