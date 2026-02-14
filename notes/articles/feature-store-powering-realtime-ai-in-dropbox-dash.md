---
url: https://dropbox.tech/machine-learning/feature-store-powering-realtime-ai-in-dropbox-dash
type: article
tags: [feature-store, machine-learning, ranking, dropbox, real-time-ml]
date_saved: 2026-02-14
---
# Inside the Feature Store Powering Real-Time AI in Dropbox Dash

## Summary
Dropbox built a custom feature store for Dash's ranking system because off-the-shelf solutions didn't fit their split infrastructure (on-prem low-latency services + Spark-native cloud). The feature store serves ML features quickly, keeps pace with changing user behavior, and enables fast iteration from idea to production.

## Key Points
- Dash uses AI to rank and retrieve relevant documents across all connected work tools
- Custom-built because infrastructure spans on-prem and cloud environments
- Designed for speed, scale, and feature freshness as user behavior changes
- Powers the ranking system that determines document relevance
- Part of broader context engineering approach for smarter AI in Dash

## Related
- [[feature-stores]]
- [[ranking-systems]]
- [[context-engineering]]
