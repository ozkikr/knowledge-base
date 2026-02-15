---
url: https://github.com/amlalabs/amla-sandbox
type: github-repo
languages: [Python]
tags: [sandboxing, wasm, agent-security]
date_saved: 2026-02-15
---
# amla-sandbox
## Summary
amla-sandbox is a WASM-based execution sandbox for agent-generated code with explicit capability enforcement. It is built to provide code-mode efficiency without exposing the host to arbitrary subprocess or shell execution risks. The system combines virtualized filesystem boundaries, no-network defaults, and policy constraints around tool invocation.

## Key Points
- Runs generated JavaScript or shell-like workloads inside a constrained WASM runtime.
- Uses capability and parameter constraints to control what tools an agent may call.
- Offers LangGraph/LangChain-oriented integration paths through wrapped sandbox tools.
- Designed as a lightweight alternative to Docker/VM isolation for common agent workflows.

## Related
- [[WASM sandbox]]
- [[Capability security]]
- [[Prompt injection mitigation]]
