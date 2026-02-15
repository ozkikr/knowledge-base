---
url: https://openai.com/index/inside-our-in-house-data-agent/
type: article
tags: [data-agent, analytics, enterprise-ai]
date_saved: 2026-02-15
---
# Inside OpenAI’s in-house data agent
## Summary
OpenAI describes an internal AI data agent built to help employees move from question to insight in minutes across a very large data platform. The system is designed around layered context (metadata, code-level table definitions, docs, and memory) so it can produce more reliable analyses than naive SQL generation. The writeup emphasizes that agent quality depends on continuous learning loops and strong grounding in institutional knowledge.

## Key Points
- The agent serves a large internal data ecosystem and reduces time spent on table discovery, SQL debugging, and repeated manual analysis.
- It uses multiple context layers: schema/lineage metadata, historical query patterns, expert annotations, code-derived table semantics, and internal documents.
- A memory system captures corrections and non-obvious constraints so future answers start from better priors.
- The runtime can query live systems when context is missing or stale, improving freshness and reducing brittle assumptions.
- Reusable workflows package recurring analyses for consistency and speed across teams.

## Related
- [[agentic-analytics]]
- [[retrieval-augmented-generation]]
- [[organizational-memory]]
