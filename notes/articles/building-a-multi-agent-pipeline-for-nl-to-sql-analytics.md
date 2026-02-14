---
url: https://techblog.lycorp.co.jp/en/building-a-multi-agent-pipeline-for-nl-to-sql-analytics
type: article
tags: [multi-agent, nl-to-sql, a2a, data-analytics, llm]
date_saved: 2026-02-14
---
# Building a Multi-Agent Pipeline for NL-to-SQL Analytics

## Summary
LINE/LY Corp built a multi-agent (A2A) pipeline to replace their monolithic MCP-based NL-to-SQL system. The new architecture splits natural language interpretation, SQL generation, execution, and result explanation into specialized agents, improving error isolation, maintainability, and scalability.

## Key Points
- Monolithic NL-to-SQL had three key limitations: separate generation/execution, single-point failure cascading errors, and unmaintainable bloated prompts
- A2A (Agent-to-Agent) architecture assigns specialized roles to each agent in the pipeline
- Built a dedicated data mart on top of raw UTS (User Tracking System) event logs for LLM-friendly querying
- Raw events are transformed into semantic "action units" before being exposed to the LLM agents
- Uses UTS behavioral logs (who/when/what/context) as the core data source for granular user behavior analysis

## Related
- [[NL-to-SQL]]
- [[Multi-Agent Systems]]
- [[MCP Servers]]
- [[Data Analytics]]
