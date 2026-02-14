---
url: https://github.com/coder/envbuilder
type: github-repo
languages: [Go]
tags: [devcontainer, docker, kubernetes, developer-environments, containers]
date_saved: 2026-02-14
---
# Envbuilder

## Summary
A tool by Coder that builds development environments from a Dockerfile on Docker, Kubernetes, and OpenShift. Supports devcontainer.json and Dockerfile, with registry-based image layer caching for fast builds.

## Key Points
- Supports devcontainer.json and Dockerfile specifications
- Runs on Docker, Kubernetes, and OpenShift
- Cache image layers with container registries for speedy rebuilds
- Tight feedback loop for developers modifying their environment
- Clones repos via ENVBUILDER_GIT_URL and runs init scripts in freshly built containers

## Related
- [[guts]] - another Coder project
- [[catnip]] - containerized coding environments
