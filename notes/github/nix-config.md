---
url: https://github.com/Veraticus/nix-config
type: github-repo
languages: [Nix, Shell, Jsonnet, Lua, HCL, Python]
tags: [nix, dotfiles, nixos, nix-darwin, home-manager]
date_saved: 2026-02-15
---
# nix-config
## Summary
A unified personal Nix flake configuration for managing both a macOS laptop and Linux home servers. The repo emphasizes reproducibility, modular configuration, and consistent developer ergonomics across environments. It also includes practical operational workflows like dev context session management and remote link opening over SSH.

## Key Points
- Single-repo approach for nix-darwin and NixOS hosts with shared modules.
- Modular layout separates host config, user config (Home Manager), overlays, and custom packages.
- Includes opinionated dev tooling and terminal UX conventions for multi-host workflows.
- Documents rebuild/update flows, testing patterns, and image/USB build utilities.
- Extends beyond dotfiles into operational tooling (contexts, notifications, remote browser links).

## Related
- [[nix]]
- [[home-manager]]
- [[dotfiles]]
