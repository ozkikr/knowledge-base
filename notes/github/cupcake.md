---
url: https://github.com/eqtylab/cupcake
type: github-repo
languages: [Go, Rego]
tags: [ai-agents, policy-enforcement, opa, security, claude-code]
date_saved: 2026-02-14
---
# Cupcake

## Summary
Cupcake is a native policy enforcement layer for AI coding agents built on OPA/Rego. It intercepts agent events and evaluates them against user-defined rules, enabling deterministic rule-following without consuming model context.

## Key Points
- Policy-as-code using Open Policy Agent (OPA) Rego language
- Supports Claude Code, Cursor, Factory AI, OpenCode, and AMP
- Can block, modify, and auto-correct agent actions with structured feedback
- Triggers alerts and timeouts for repeated rule violations
- Enables reactive automation (e.g., auto-linting after file edits)

## Related
- [[claude-code]]
- [[plannotator]]
- [[ai-agent-safety]]
- [[open-policy-agent]]
