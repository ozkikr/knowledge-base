---
url: https://github.com/jetify-com/devbox
type: github-repo
languages: [Go]
tags: [dev-environment, nix, reproducible-builds, cli, devtools]
date_saved: 2026-02-14
---
# Devbox - Instant Development Environments

## Summary
Devbox is a CLI tool by Jetify that creates isolated, reproducible development shells using Nix under the hood. It manages OS-level packages (like brew/apt-get) with access to over 400,000 package versions from the Nix Package Registry, ensuring consistent environments across teams.

## Key Points
- Declarative devbox.json defines project dependencies; `devbox shell` gives everyone identical environments
- Access to 400,000+ Nix packages without needing to learn Nix
- Try new tools without polluting your system
- Works similar to yarn but for OS-level packages
- Internally powered by Nix

## Related
- [[gocraft]] - Go project scaffolding
- [[gh-dash]] - terminal developer tooling
