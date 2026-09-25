<p align="center">
  <img src="https://raw.githubusercontent.com/mcp-runtime/.github/main/profile/banner.png" alt="MCP Runtime banner" />
</p>

# MCP Runtime

**MCP Runtime is a self-hosted Kubernetes control plane for internal MCP servers.** It deploys and routes servers, authorizes tool calls, expires or revokes access, and audits requests inside your own cluster.

You decide who can call each tool, up to what trust level, and for how long. Servers, grants, and consented sessions are Kubernetes resources, and a gateway in each server pod enforces them on every call and records the decision.

The [documentation](https://docs.mcpruntime.org/) covers setup, operations, and the Kubernetes resources. If you would rather not run it yourself, we can [host or manage it for you](https://mcpruntime.org/#hosting).

**Explore:** [Website](https://mcpruntime.org/) · [Documentation](https://docs.mcpruntime.org/) · [Live platform](https://platform.mcpruntime.org/)

## Vision

Run MCP servers like any other production service: deployed in environments you control, with governed access for agents and people, policy checked on every request, and a record of what happened.

## Projects

- [MCP Runtime](https://github.com/mcp-runtime/mcp-runtime) — Kubernetes native runtime and control plane
- [Python MCP](https://github.com/mcp-runtime/py-mcp) — Python MCP tooling
- [MCP Auth](https://github.com/mcp-runtime/mcp-auth) — authentication and authorization components
- [MCP Server Fuzzer](https://github.com/mcp-runtime/mcp-server-fuzzer) — security testing for MCP servers

Start with the [quickstart](https://docs.mcpruntime.org/quickstart/) to try the platform, or follow the [getting started guide](https://docs.mcpruntime.org/getting-started/) to install it on your own Kubernetes cluster.

Brand assets for organization use: [logo lockup](logo-lockup.png), [dark-background lockup](logo-lockup-dark.png), and [square icon](logo.png).
