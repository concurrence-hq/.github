# Amigo

Enterprise healthcare AI platform for voice, messaging, operator workflows, and production data systems.

[Website](https://amigo.ai) · [Docs](https://docs.amigo.ai) · [Developer Guide](https://docs.amigo.ai/developer-guide) · [Security](https://github.com/amigo-ai/.github/blob/main/SECURITY.md) · [Support](https://github.com/amigo-ai/.github/blob/main/SUPPORT.md)

## Public Product Surfaces

| Surface | Best starting point | Notes |
| --- | --- | --- |
| Platform API | [`amigo-platform-typescript-sdk`](https://github.com/amigo-ai/amigo-platform-typescript-sdk) | Workspace-scoped API at `api.platform.amigo.ai` for new integrations |
| Classic API SDKs | [`amigo-typescript-sdk`](https://github.com/amigo-ai/amigo-typescript-sdk) and [`amigo-python-sdk`](https://github.com/amigo-ai/amigo-python-sdk) | Supported org-scoped SDKs for current `api.amigo.ai` deployments |
| Provider Scribe workflows | [`scribe-typescript-sdk`](https://github.com/amigo-ai/scribe-typescript-sdk) | Separate Scribe REST, streaming, and browser-recording client; provider access must be provisioned |
| Agent engineering workflows | [`forge-mcp`](https://github.com/amigo-ai/forge-mcp) | Experimental MCP prototype for Agent Forge workflows |

## Public Repositories

| Repository | Role | Status |
| --- | --- | --- |
| [`amigo-platform-typescript-sdk`](https://github.com/amigo-ai/amigo-platform-typescript-sdk) | Official TypeScript SDK for the Amigo Platform API | Primary public SDK for new workspace-scoped integrations |
| [`amigo-typescript-sdk`](https://github.com/amigo-ai/amigo-typescript-sdk) | Official TypeScript SDK for the Classic Amigo API | Supported for current classic integrations |
| [`amigo-python-sdk`](https://github.com/amigo-ai/amigo-python-sdk) | Official Python SDK for the Classic Amigo API | Supported for current classic integrations |
| [`scribe-typescript-sdk`](https://github.com/amigo-ai/scribe-typescript-sdk) | TypeScript client for provider Scribe sessions and recording | ESM-only; backend credentials and browser attach tickets have separate roles |
| [`forge-mcp`](https://github.com/amigo-ai/forge-mcp) | MCP server for Agent Forge workflows | Prototype, experimental, and not a stable product contract |

## Migration Policy

- New workspace-scoped capabilities land on the Platform API first.
- The Classic API and SDKs remain supported for current deployments.
- Migration from Classic to Platform will ship with explicit upgrade guidance and a clear customer path before Amigo recommends a move.

## Security And Contact

- Report security issues privately to `security@amigo.ai`.
- Use `contact@amigo.ai` for support, partnership, and enterprise inquiries.
- Product and API documentation live at [docs.amigo.ai](https://docs.amigo.ai).
