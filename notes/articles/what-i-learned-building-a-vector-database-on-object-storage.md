---
url: https://blog.karanjanthe.me/posts/vecpuff/
type: article
tags: [vector-database, s3, object-storage, turbopuffer, database-internals]
date_saved: 2026-02-14
---
# What I Learned Building a Vector Database on Object Storage

## Summary
A hands-on learning exercise building a naive vector database on S3, inspired by Turbopuffer's architecture. The author explores write-ahead logs on S3, centroid-based indexes, stateless query nodes, and the tradeoffs of using object storage for database operations where every extra roundtrip costs ~200ms.

## Key Points
- Traditional vector DBs (Pinecone, Qdrant) can cost ~$20k/month for 100M vectors; S3-based approach targets ~$1500/month for 1B vectors
- Write path: upsert → WAL → async compaction → indexed clusters
- Query path is hybrid: fast cluster lookup (~10ms) + scanning recent WAL (~200ms)
- S3 conditional writes (if_non_match) prevent accidental overwrites
- S3 lacks folder listing — requires tracking WAL file sequence numbers manually

## Related
- [[vector-database]] [[s3]] [[turbopuffer]] [[wal]] [[database-architecture]]
