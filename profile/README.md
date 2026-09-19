# Concurrence

Concurrence, formerly Amigo, is an enterprise healthcare AI platform for voice, messaging, operator workflows, and production data systems.

[Website](https://www.concurrence.com) · [Docs](https://docs.concurrence.com) · [Developer Guide](https://docs.concurrence.com/developer-guide) · [Security](https://github.com/concurrence-hq/.github/blob/main/SECURITY.md) · [Support](https://github.com/concurrence-hq/.github/blob/main/SUPPORT.md)

## Public Product Surfaces

| Surface | Best starting point | Notes |
| --- | --- | --- |
| Platform API | [`amigo-platform-typescript-sdk`](https://github.com/concurrence-hq/amigo-platform-typescript-sdk) | Workspace-scoped API at `api.platform.amigo.ai` for new integrations |
| Classic API SDKs | [`amigo-typescript-sdk`](https://github.com/concurrence-hq/amigo-typescript-sdk) and [`amigo-python-sdk`](https://github.com/concurrence-hq/amigo-python-sdk) | Supported org-scoped SDKs for current `api.amigo.ai` deployments |
| Provider Scribe workflows | [`scribe-typescript-sdk`](https://github.com/concurrence-hq/scribe-typescript-sdk) | Separate Scribe REST, streaming, and browser-recording client; provider access must be provisioned |
| Agent engineering workflows | [`forge-mcp`](https://github.com/concurrence-hq/forge-mcp) | Experimental MCP prototype for Agent Forge workflows |

## Public Repositories

| Repository | Role | Status |
| --- | --- | --- |
| [`amigo-platform-typescript-sdk`](https://github.com/concurrence-hq/amigo-platform-typescript-sdk) | Official TypeScript SDK for the Concurrence Platform API | Primary public SDK for new workspace-scoped integrations |
| [`amigo-typescript-sdk`](https://github.com/concurrence-hq/amigo-typescript-sdk) | Official TypeScript SDK for the Classic API | Supported for current classic integrations |
| [`amigo-python-sdk`](https://github.com/concurrence-hq/amigo-python-sdk) | Official Python SDK for the Classic API | Supported for current classic integrations |
| [`scribe-typescript-sdk`](https://github.com/concurrence-hq/scribe-typescript-sdk) | TypeScript client for provider Scribe sessions and recording | ESM-only; backend credentials and browser attach tickets have separate roles |
| [`forge-mcp`](https://github.com/concurrence-hq/forge-mcp) | MCP server for Agent Forge workflows | Prototype, experimental, and not a stable product contract |

## Migration Policy

The Concurrence rebrand does not require changing API base URLs, package names, or credentials. Keep using the endpoints and package identifiers documented for your API family.

- New workspace-scoped capabilities land on the Platform API first.
- The Classic API and SDKs remain supported for current deployments.
- Migration from Classic to Platform will ship with explicit upgrade guidance and a clear customer path before Concurrence recommends a move.

## Security And Contact

- Report security issues privately to `security@amigo.ai`.
- Use `contact@concurrence.com` for support, partnership, and enterprise inquiries. Legacy contact: `contact@amigo.ai`.
- Product and API documentation live at [docs.concurrence.com](https://docs.concurrence.com).
