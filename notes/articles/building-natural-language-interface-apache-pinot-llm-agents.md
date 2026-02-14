---
url: https://medium.com/miq-tech-and-analytics/building-a-natural-language-interface-for-apache-pinot-with-llm-agents-6cb2fa96cb66
type: article
tags: [llm-agents, text-to-sql, apache-pinot, google-adk, agentic-ai]
date_saved: 2026-02-14
---
# Building a Natural Language Interface for Apache Pinot with LLM Agents

## Summary
MiQ built a conversational AI agent using Google's Agent Development Kit (ADK) that translates natural language questions into Apache Pinot SQL queries. The system uses an agentic pipeline with NL2SQL generation, query verification, and error recovery to help account managers get campaign insights without writing SQL.

## Key Points
- Uses an LLM agent framework with Google ADK for orchestration, memory management, and tool use
- Pipeline: User query → NL2SQL tool (Gemini) → Verification tool (sql-rail) → Query execution → Response
- Handles follow-up questions, query refinement, and graceful error recovery
- Solves the challenge of mapping ambiguous business terms (e.g., "active campaigns") to precise SQL
- Built for digital advertising use case where speed of insight is critical

## Related
- [[text-to-sql]]
- [[llm-agents]]
- [[apache-pinot]]
- [[google-adk]]
