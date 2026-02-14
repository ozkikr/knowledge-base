---
url: https://github.com/distil-labs/distil-text2sql
type: github-repo
languages: [Python]
tags: [text2sql, nlp, fine-tuning, ollama, local-llm]
date_saved: 2026-02-14
---
# distil-text2sql (Text2SQirreL)

## Summary
A tool for converting natural language questions into SQL queries using small, fine-tuned local models. The tuned Qwen3-4B model matches a 685B teacher model on accuracy while being 170x smaller, requiring no API keys or cloud dependencies.

## Key Points
- Fine-tuned Qwen3-4B (4B params) matches DeepSeek-V3 (685B) on LLM-as-a-Judge accuracy
- Runs locally via Ollama with full privacy
- Load CSV files, ask questions in plain English, get SQL results
- 0.6B model available for edge deployment (74% accuracy)
- Show generated SQL with --show-sql flag

## Related
- [[text2sql]] [[fine-tuning]] [[ollama]] [[local-llm]] [[nlp]]
