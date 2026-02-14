---
url: https://github.com/ahujasid/blender-mcp
type: github-repo
languages: [Python]
tags: [mcp, blender, 3d-modeling, claude, ai-integration]
date_saved: 2026-02-14
---
# BlenderMCP - Blender Model Context Protocol Integration

## Summary
BlenderMCP connects Blender to Claude AI through the Model Context Protocol (MCP), enabling prompt-assisted 3D modeling, scene creation, and manipulation. It provides two-way communication via a socket-based server, allowing Claude to directly interact with and control Blender.

## Key Points
- Two-way communication between Claude AI and Blender through socket-based server
- Supports object manipulation, material control, scene inspection, and arbitrary Python code execution
- Integrates with Hunyuan3D, Sketchfab models, Poly Haven assets, and Hyper3D Rodin for 3D model generation
- Can capture Blender viewport screenshots for scene understanding
- Consists of a Blender addon (socket server) and an MCP server component

## Related
- [[model-context-protocol]]
- [[claude]]
- [[3d-modeling]]
