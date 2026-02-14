---
url: https://github.com/sidequery/duckdb-acp
type: github-repo
languages: [C++, JavaScript]
tags: [duckdb, acp, natural-language-sql, claude-code, ai-agents]
date_saved: 2026-02-14
---
# DuckDB ACP - Agent Client Protocol Extension for DuckDB

## Summary
A DuckDB extension that enables natural language to SQL queries using the Agent Client Protocol (ACP). Users can write queries in plain English via statement syntax (`CLAUDE show me...`) or table functions (`SELECT * FROM claude('...')`), and the agent generates accurate SQL by exploring database schema.

## Key Points
- Supports both statement syntax and table function syntax for natural language queries
- Schema-aware: agent explores database schema to generate accurate SQL
- Safe mode blocks mutation queries (INSERT, UPDATE, DELETE) by default
- Supports multiple agents: Claude Code, Codex, Gemini
- Configurable debug output, SQL preview, and analysis summaries

## Related
- [[duckdb]]
- [[agent-client-protocol]]
- [[natural-language-to-sql]]
- [[claude-code]]
