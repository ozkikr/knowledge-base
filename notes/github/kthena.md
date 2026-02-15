---
url: https://github.com/volcano-sh/kthena
type: github-repo
languages: [Go, Python, Shell, Makefile, Dockerfile, Go Template]
tags: [llm-serving, kubernetes, ai-infrastructure]
date_saved: 2026-02-15
---
# Kthena

## Summary
Kthena is a Kubernetes-native platform for deploying and scaling LLM inference workloads in production. It adds CRD-based model lifecycle management and intelligent routing across multiple inference engines. The architecture separates control and data planes to support enterprise-grade scalability and operational policies.

## Key Points
- Supports engines such as vLLM, SGLang, Triton, and TorchServe through unified APIs.
- Implements advanced serving patterns including prefill-decode disaggregation.
- Includes cost-aware autoscaling and traffic controls like canary and weighted routing.
- Integrates with Volcano scheduler features such as gang and topology-aware scheduling.
- Provides quick-start scripts and docs for local and cluster deployments.

## Related
- [[Kubernetes]]
- [[LLM Inference]]
- [[Autoscaling]]
