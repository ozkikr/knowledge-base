---
url: https://github.com/veil-services/veil-go
type: github-repo
languages: [Go]
tags: [pii-detection, data-masking, llm-security, privacy, compliance]
date_saved: 2026-02-14
---
# Veil-Go - Sensitive Data Firewall for LLMs

## Summary
Veil is a high-performance Go library that prevents PII from leaking into LLMs, logs, and vector databases. It detects sensitive data locally, masks it deterministically before it leaves your infrastructure, and restores it seamlessly in responses—preserving LLM context while protecting privacy.

## Key Points
- Detects and masks PII (emails, credit cards, national IDs) locally with zero latency
- Deterministic masking with tokens like `<<EMAIL_1>>` that LLMs can reason about
- Restore original values after LLM response for seamless user experience
- Blazing fast: 10,000 requests in ~40ms in benchmarks
- Thread-safe and production-ready for API gateways and stream processors

## Related
- [[pii-detection]]
- [[llm-security]]
- [[data-masking]]
- [[compliance]]
