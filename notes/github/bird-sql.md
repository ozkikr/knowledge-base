---
url: https://github.com/ContextualAI/bird-sql
type: github-repo
languages: [Python]
tags: [text-to-sql, benchmark, llm, reward-model, sql]
date_saved: 2026-02-14
---
# bird-sql

## Summary
ContextualAI's text-to-SQL pipeline for the BIRD benchmark. Uses a multi-stage approach with candidate generation (Qwen2.5-Coder-32B), SQL execution, reward-based scoring, and analysis to achieve high accuracy on natural language to SQL translation.

## Key Points
- Four-stage pipeline: candidate generation, SQL execution, reward scoring, analysis
- Uses Qwen2.5-Coder-32B-Instruct as the generator model
- Custom reward model for scoring SQL candidates
- Requires 2+ GPUs with 80GB RAM each
- Supports parallel execution of generation and SQL running

## Related
- [[bleve]] - Search and indexing
- [[context-engineering-for-ai-agents]] - AI engineering
