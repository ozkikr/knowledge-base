---
url: https://github.com/meta-pytorch/OpenEnv
type: github-repo
languages: [Python, Jupyter Notebook, Shell, Dockerfile]
tags: [reinforcement-learning, environments, agentic-training]
date_saved: 2026-02-15
---
# OpenEnv
## Summary
OpenEnv is a framework for creating and deploying isolated agentic execution environments for reinforcement-learning workflows. It offers Gymnasium-style APIs (`reset`, `step`, `state`) and packaging/deployment tooling for environment builders. The project aims to standardize how RL training loops interact with external environments.

## Key Points
- Defines a typed client/server environment interface for RL-compatible execution.
- Supports containerized deployment and environment scaffolding via CLI.
- Includes async-first clients with synchronous wrappers for ergonomic integration.
- Provides built-in web interfaces and tooling for debugging environment behavior.
- Integrates with partner ecosystems and tutorials for practical RL training use cases.

## Related
- [[Agentic RL]]
- [[Gymnasium API]]
- [[Execution Environments]]
