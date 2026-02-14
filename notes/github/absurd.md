---
url: https://github.com/earendil-works/absurd
type: github-repo
languages: [SQL, Python]
tags: [durable-execution, workflows, postgres, queue]
date_saved: 2026-02-14
---
# Absurd

## Summary
The simplest durable execution workflow system, built entirely on Postgres. Handles scheduling and retries without any additional services. An experiment exploring whether workflow complexity can sit with the database rather than client SDKs.

## Key Points
- Entire system is a single SQL file applied to Postgres
- No additional services needed beyond Postgres
- Handles scheduling, retries, and durable state
- Useful for LLM agents, payments, email scheduling, order processing
- Early experiment, not production-ready; by Armin Ronacher (Lucumr)

## Related
- [[durable-execution]]
- [[temporal]]
- [[postgres]]
- [[workflow-engines]]
