---
url: https://github.com/aperturerobotics/goscript
type: github-repo
languages: [TypeScript, Go, HTML, JavaScript, CSS, Shell]
tags: [transpiler, golang, typescript]
date_saved: 2026-02-15
---
# goscript
## Summary
GoScript is an experimental compiler that transpiles Go to TypeScript at the AST level. Its goal is sharing backend Go logic with JavaScript/TypeScript runtimes while preserving familiar semantics. The repository documents coverage status, constraints, and integration patterns for generated code.

## Key Points
- Translates many core Go constructs, including structs, methods, generics, and concurrency primitives.
- Targets practical logic sharing between Go services and frontend runtimes.
- Provides CLI and programmatic APIs for package compilation.
- Documents TypeScript project settings required to consume generated outputs.
- Maintains compliance tests and architecture/design references for contributors.

## Related
- [[Language Transpilation]]
- [[Go Tooling]]
- [[Cross-Runtime Code Reuse]]
