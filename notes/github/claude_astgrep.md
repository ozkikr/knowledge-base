---
url: https://github.com/appdotbuild/claude_astgrep
type: github-repo
languages: [Markdown, TOML, YAML]
tags: [ast-grep, static-analysis, claude-code, code-quality]
date_saved: 2026-02-15
---
# claude_astgrep
## Summary
A workflow for turning coding guidelines and recurring assistant mistakes into enforceable ast-grep rules. It uses Claude Code to generate deterministic pattern checks that can be validated and reused. The project focuses on shifting style guidance from advisory text into automated guardrails.

## Key Points
- Exposes a command-driven flow for generating ast-grep rules from examples or policy docs.
- Targets common issues like unsafe patterns and inconsistent team conventions.
- Supports validating generated rules before broader enforcement.
- Designed to pair with Claude Code hooks and CI pipelines for continuous enforcement.
- Bridges natural-language standards and machine-checkable static rules.

## Related
- [[ast-grep]]
- [[static-analysis]]
- [[claude-code]]
