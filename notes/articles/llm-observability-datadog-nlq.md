---
url: https://www.datadoghq.com/blog/llm-observability-at-datadog-nlq/
type: article
tags: [llm-observability, evaluations, nlq, datadog, debugging, agent-testing]
date_saved: 2026-02-14
---
# How We Cut Our NLQ Agent Debugging Time from Hours to Minutes with LLM Observability

## Summary
Datadog's Cloud Cost Management team shares how they built and evaluated a natural language query (NLQ) agent that generates Datadog metrics queries from plain English. They decomposed correctness into independent evaluators (parsing, metric selection, roll-up, group-bys, filters) and used LLM Observability to speed up debugging.

## Key Points
- NLQ agent outputs a metrics query string, not conversational text — correctness is critical
- String comparison for evaluation gave misleadingly low success rates (2%) despite good performance
- Decomposed correctness into 5 independent evaluators: parsing, metric selection, roll-up, group-bys, filters
- Built ground truth dataset from real internal user testing sessions, not synthetic prompts
- LLM Observability traces capture full agent execution: prompts, tool calls, arguments, responses

## Related
- [[llm-observability]]
- [[ai-agent-evaluations]]
- [[natural-language-to-sql]]
- [[datadog]]
