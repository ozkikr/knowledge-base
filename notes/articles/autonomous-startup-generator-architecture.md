---
url: https://gammavibe.com/updates/autonomous-startup-generator-architecture/
type: article
tags: [agentic-systems, automation, llm, architecture, pipeline]
date_saved: 2026-02-15
---
# Architecture of an autonomous startup-idea generator (Python, Pydantic AI, Gemini, Postgres)
## Summary
A detailed architecture breakdown of a fully automated newsletter pipeline that ingests news, extracts business signals, synthesizes opportunities, drafts content, QA-checks output, and publishes to Ghost.

## Key Points
- The system evolved from JSON artifact chaining to database-backed, state-driven orchestration.
- Each step is resumable and idempotent by querying pending work from Postgres.
- The pipeline uses model tiering: cheap/fast models for triage, stronger models for synthesis and writing.
- A ten-step flow handles ingestion, extraction, candidate selection, deep-dive generation, visuals, QA, and publishing.

## Related
- [[building-production-ready-agentic-systems-shopify]]
- [[towards-a-science-of-scaling-agent-systems-when-and-why-agent-systems-work]]
