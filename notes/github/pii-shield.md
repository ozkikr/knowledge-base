---
url: https://github.com/aragossa/pii-shield
type: github-repo
languages: [Go, Shell, Dockerfile]
tags: [pii, kubernetes, log-sanitization]
date_saved: 2026-02-15
---
# PII-Shield

## Summary
PII-Shield is a Kubernetes sidecar for sanitizing logs before they leave application pods. It combines deterministic regex redaction with entropy-based secret detection to reduce sensitive-data leakage risk. The tool is designed for high-throughput environments with low-allocation parsing and operational simplicity.

## Key Points
- Runs as a drop-in sidecar or pipe wrapper without requiring app code changes.
- Redacts sensitive values while preserving log structure and JSON integrity.
- Uses deterministic hashed placeholders to keep debugging correlation possible.
- Supports allowlists and custom regex rules to manage false positives and compliance cases.
- Includes fuzzing/smoke validation and production-oriented configuration controls.

## Related
- [[PII Redaction]]
- [[Kubernetes Sidecar]]
- [[Log Processing]]
