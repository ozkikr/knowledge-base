---
url: https://tech.instacart.com/simplifying-large-scale-llm-processing-across-instacart-with-maple-63df4508d5be
type: article
tags: [llm, batch-processing, infrastructure, instacart, mlops]
date_saved: 2026-02-14
---
# Simplifying Large-Scale LLM Processing across Instacart with Maple

## Summary
Instacart built Maple, an internal service for large-scale LLM batch processing that saves up to 50% on LLM costs compared to real-time API calls. It handles batching, encoding, file management, retries, and cost tracking so teams don't reinvent infrastructure.

## Key Points
- Maple abstracts LLM batch API complexity (50K prompt / 200MB batch limits)
- Saves up to 50% on costs vs real-time LLM calls
- Accepts CSV/Parquet input with a prompt, outputs merged results
- Automates batching, encoding/decoding, file management, retries, and cost tracking
- Used across Catalog (data cleaning), Fulfillment (perishable routing), and Search teams

## Related
- [[batch-processing]] [[LLM-infrastructure]] [[cost-optimization]] [[RAG]]
