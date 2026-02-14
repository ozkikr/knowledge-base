---
url: https://arxiv.org/abs/2411.07763
type: paper
tags: [text-to-sql, benchmarks, enterprise, llm-evaluation, databases]
date_saved: 2026-02-14
---
# Spider 2.0: Evaluating Language Models on Real-World Enterprise Text-to-SQL Workflows

## Summary
Spider 2.0 is an evaluation framework with 632 real-world text-to-SQL workflow problems from enterprise database use cases. Unlike traditional text-to-SQL benchmarks, it involves complex cloud/local databases (often 1,000+ columns), multiple SQL dialects, and diverse operations from data transformation to analytics across systems like BigQuery and Snowflake.

## Key Points
- 632 real-world enterprise text-to-SQL problems with databases sourced from real applications
- Requires understanding database metadata, dialect documentation, and project-level codebases
- Problems often require generating multiple SQL queries exceeding 100 lines
- Covers cloud and local database systems (BigQuery, Snowflake, etc.)
- Goes far beyond traditional text-to-SQL challenges in complexity

## Related
- [[text-to-sql]]
- [[llm-benchmarks]]
- [[enterprise-data]]
- [[spider-benchmark]]
