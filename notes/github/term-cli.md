---
url: https://github.com/EliasOenal/term-cli
type: github-repo
languages: [Python, Shell]
tags: [ai-agents, terminal, tmux]
date_saved: 2026-02-15
---
# term-cli
## Summary
term-cli is a tmux-backed CLI that lets AI agents run and control interactive terminal programs without blocking their workflow. It pairs with term-assist so humans can step in for sensitive prompts like passwords or MFA, then hand control back. The project emphasizes reliability, low dependencies, and agent-friendly command ergonomics.

## Key Points
- Runs interactive tools (debuggers, SSH, TUIs, installers) in detached sessions agents can inspect and control.
- Provides primitives for sending text/keys, waiting for prompts, capturing output, scrolling, and logging.
- Includes a human-collaboration flow (`request` / `request-wait`) via `term-assist` for secure handoffs.
- Ships as single-file Python tools with minimal runtime requirements (Python + tmux).
- Designed for “TTY-first” workflows that cannot be fully automated with non-interactive flags.

## Related
- [[ai-agents]]
- [[terminal-automation]]
- [[human-in-the-loop]]
