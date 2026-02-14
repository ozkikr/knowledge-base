---
url: https://github.com/tensorchord/envd
type: github-repo
languages: [Go, Python]
tags: [dev-environments, containers, ai-ml, reproducibility, docker]
date_saved: 2026-02-14
---
# envd - Development Environment for AI/ML

## Summary
envd is a CLI tool for creating container-based development environments for AI/ML. It uses a simple Python-like DSL (Starlark) to declare dependencies and produces OCI-compatible images, replacing complex Dockerfiles and bash scripts.

## Key Points
- Simple Python-like DSL for declaring environments (base, conda, pip packages, shell, jupyter)
- Builds OCI-compatible images using buildkit
- Supports local and cloud-based development
- Designed specifically for AI/ML workflows with CUDA, Python, conda support
- Eliminates need for complex Dockerfiles and bash scripts

## Related
- [[docker]], [[buildkit]], [[ai-ml-tooling]], [[dev-environments]]
