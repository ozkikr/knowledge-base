---
url: https://github.com/e2b-dev/infra
type: github-repo
languages: [Go, SQL, HCL, YAML, Shell]
tags: [e2b, infrastructure, terraform, cloud]
date_saved: 2026-02-15
---
# infra
## Summary
This repository contains the infrastructure code that powers E2B Cloud, the platform behind E2B’s AI code execution environment. It focuses on deployable platform components and operational tooling rather than end-user SDK usage. It also documents a self-hosting path for teams that want to run the stack themselves.
## Key Points
- Infrastructure is managed primarily with Terraform and supports self-hosting workflows.
- The repo is positioned as the platform layer complementary to e2b-dev/e2b SDK and CLI tooling.
- Includes substantial Go/SQL code alongside infra configuration for control-plane and service behavior.
- Cloud provider support is documented, with GCP presented as the most mature path.
## Related
- [[sandbox-runtime]]
- [[devops]]
- [[terraform-gui]]
