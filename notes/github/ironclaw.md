---
url: https://github.com/nearai/ironclaw
type: github-repo
languages: [Rust, JavaScript, CSS, PLpgSQL, HTML, Shell]
tags: [security, personal-assistant, rust]
date_saved: 2026-02-15
---
# ironclaw
## Summary
IronClaw is a Rust-based personal assistant platform inspired by OpenClaw with a strong focus on privacy and defense-in-depth security. It combines multi-channel interaction, persistent memory, and extensible tooling with sandboxed execution. The project emphasizes local control, auditability, and prompt-injection resilience.

## Key Points
- Uses WASM sandboxing and capability-based permissions for untrusted tool execution.
- Provides multi-channel access patterns including REPL, webhooks, and web gateway.
- Includes routines/heartbeat systems for background automation.
- Implements local data storage with encrypted secrets and audit-friendly architecture.
- Supports dynamic tool extension via MCP and plugin mechanisms.

## Related
- [[OpenClaw]]
- [[WASM Sandbox]]
- [[Prompt Injection Defense]]
