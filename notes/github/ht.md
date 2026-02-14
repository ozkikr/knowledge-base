---
url: https://github.com/andyk/ht
type: github-repo
tags: [terminal, headless, rust, ai-agents, pty]
date_saved: 2026-02-14
---

# ht - Headless Terminal

## Summary
A Rust CLI that wraps any binary with a VT100 terminal interface (PTY + terminal server), exposing input/output as JSON over STDIN/STDOUT. Built for programmatic terminal interaction, especially for LLM agents that need to use terminals like humans do.

## Key Points
- Wraps arbitrary binaries (bash, vim, etc.) with a pseudoterminal
- JSON-based I/O over STDIN/STDOUT for easy programmatic access
- Key use case: enabling AI agents to interact with stateful terminal UIs
- Built in Rust, works on MacOS and Linux
- Solves the "headless browser but for terminals" problem

## Related
- [[terminal-automation]] [[ai-agents]] [[rust]] [[libtmux]]
