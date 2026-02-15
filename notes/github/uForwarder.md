---
url: https://github.com/uber/uForwarder
type: github-repo
languages: [Java, HTML]
tags: [kafka, messaging, uber]
date_saved: 2026-02-15
---
# uber/uForwarder
## Summary
uForwarder is Uber’s Kafka consumer proxy that forwards Kafka data to downstream consumers via RPC (gRPC). It is designed to improve reliability and scalability characteristics for async queueing at scale, including partition/consumer decoupling. The project emphasizes operational traits like retries, dead-letter handling, and head-of-line blocking recovery.

## Key Points
- Bridges Kafka and consumers through an RPC-based proxy architecture.
- Supports at-least-once delivery and parallel processing per partition.
- Decouples Kafka partition scaling from consumer service scaling.
- Includes retry queue and dead-letter queue support for failure handling.
- Documents local build/test and dockerized runtime setup workflows.

## Related
- [[Apache Kafka]]
- [[Message Queues]]
- [[gRPC]]
