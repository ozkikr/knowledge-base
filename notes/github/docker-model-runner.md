---
url: https://github.com/theCaptN21/docker-model-runner
type: github-repo
languages: [Python, Dockerfile]
tags: [mlops, docker, cicd]
date_saved: 2026-02-15
---
# Docker Model Runner
## Summary
Docker Model Runner is a containerized inference API example using Hugging Face Transformers (distilgpt2) with automated CI/CD. The repository demonstrates secure build, test, and deployment practices through GitHub Actions. It is structured as a practical MLOps starter with scanning and quality checks built in.

## Key Points
- Exposes a lightweight model-serving API from a Dockerized Python application.
- Uses multi-stage container builds and automated GitHub Actions workflows.
- Integrates security and quality tooling such as Trivy and SonarCloud.
- Documents end-to-end setup for local testing and registry publishing.
- Serves as a reference project for basic ML deployment automation.

## Related
- [[MLOps]]
- [[Containerized Inference]]
- [[CI/CD Pipelines]]
