---
url: https://github.com/agno-agi/dash
type: github-repo
languages: [Python, Shell, Dockerfile]
tags: [data-agent, text-to-sql, self-learning]
date_saved: 2026-02-15
---
# Dash

## Summary
Dash is a self-learning data agent that answers natural-language analytics questions using grounded SQL generation. It combines six context layers (schema, business annotations, query patterns, docs, learnings, and runtime context) to improve correctness. The project emphasizes continuous learning from failures without model fine-tuning.

## Key Points
- Grounds SQL generation in curated knowledge plus dynamically retrieved context.
- Uses a learning loop to store and reuse error fixes so mistakes are less likely to repeat.
- Returns interpreted insights, not only raw query rows.
- Provides local Docker setup and deployment scripts for Railway.
- Supports knowledge ingestion via table metadata, business rules, and validated query templates.

## Related
- [[Text-to-SQL]]
- [[Retrieval-Augmented Generation]]
- [[Data Analytics Agents]]
