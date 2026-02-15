---
url: https://dspy.ai/learn/programming/adapters/
type: article
tags: [dspy, adapters, prompting, structured-output, llm-integration]
date_saved: 2026-02-15
---
# Adapters - DSPy
## Summary
This guide explains DSPy adapters as the layer that formats signature-driven prompts and parses model outputs into structured predictions. It describes how adapters integrate with `dspy.Predict`, conversation history, and typed fields. The page compares adapter strategies such as ChatAdapter and JSONAdapter for reliability and performance tradeoffs.
## Key Points
- Adapters bridge DSPy signatures and provider-facing message formats.
- `format()` builds prompts; `parse()` turns responses into typed outputs.
- ChatAdapter is default and broadly compatible, with automatic fallback behavior.
- JSONAdapter leverages structured response modes for cleaner parsing.
- Adapter selection can be set globally or scoped via context managers.
## Related
- [[dspy]]
- [[adapter-pattern]]
- [[structured-generation]]
