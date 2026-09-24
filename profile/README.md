<p align="center">
  <img src="https://raw.githubusercontent.com/mcp-runtime/.github/main/profile/banner.png" alt="MCP Runtime banner" />
</p>

# MCP Runtime

**MCP Runtime is a self-hosted Kubernetes control plane for internal MCP servers.** It helps companies deploy and route servers, authorize tool calls, expire or revoke access, and audit requests in their own clusters.

It is not a public directory for discovering MCP servers. Connecting an agent is the easy part: point the client at an endpoint. The hard part is controlling who can call each tool, recording what a person consented to, cutting off access when needed, and reviewing what happened. MCP Runtime makes servers, grants, and consented sessions inspectable Kubernetes state, then enforces policy on the live gateway request path.

The [website](https://mcpruntime.org/) explains the product, and the [documentation](https://docs.mcpruntime.org/) covers setup, operations, and the Kubernetes resources behind it.

**Explore:** [Website](https://mcpruntime.org/) · [Documentation](https://docs.mcpruntime.org/) · [Live platform](https://platform.mcpruntime.org/)

## Vision

Make MCP servers practical to run as trusted infrastructure. Teams should be able to deploy MCP services in the environments they control, give agents and people governed access, enforce policy on every request, and inspect what happened afterward.

MCP Runtime is built around that idea: a Kubernetes native control plane that helps organizations operate MCP servers with the deployment, governance, and audit practices they already expect from production services.

## Projects

- [MCP Runtime](https://github.com/mcp-runtime/mcp-runtime) — Kubernetes native runtime and control plane
- [Python MCP](https://github.com/mcp-runtime/py-mcp) — Python MCP tooling
- [MCP Auth](https://github.com/mcp-runtime/mcp-auth) — authentication and authorization components
- [MCP Server Fuzzer](https://github.com/mcp-runtime/mcp-server-fuzzer) — security testing for MCP servers

Start with the [quickstart](https://docs.mcpruntime.org/quickstart/) to try the platform, or follow the [getting started guide](https://docs.mcpruntime.org/getting-started/) to install it on your own Kubernetes cluster.
