<p align="center">
  <img src="logo.svg" width="96" alt="Stashy">
</p>

<h3 align="center">File storage for AI agents</h3>

<p align="center">
  Self-hosted, open-source storage your agents can use over MCP or a plain API key.<br>
  They upload, manage, and share files — you stay in control.
</p>

<p align="center">
  <a href="https://stashy.sh">Website</a> ·
  <a href="https://docs.stashy.sh">Docs</a> ·
  <a href="https://docs.stashy.sh/mcp-server">MCP server</a> ·
  <a href="https://docs.stashy.sh/api-reference/overview">API reference</a>
</p>

---

- **Agent-native** — built-in MCP server, plus REST, gRPC, gRPC-Web, and Connect on a single endpoint
- **Any storage backend** — local disk, Amazon S3, Cloudflare R2, MinIO, or Google Cloud Storage
- **Sharing on your terms** — keep each file private, share it with your team, or make it public
- **Clean URLs** — readable slugs, served from your own domain or CDN
- **Self-hosted** — SQLite or PostgreSQL, Google sign-in, optionally limited to your company's domain

## Quick start

```bash
brew install stashysh/tap/stashy
```

Then connect your agent through [Stashy Desktop](https://github.com/stashysh/desktop), which keeps your API key in the system keychain:

```bash
claude mcp add --transport http stashy http://127.0.0.1:7487/mcp
```

## Repositories

| | |
|---|---|
| [stashy](https://github.com/stashysh/stashy) | Server: API, MCP, web dashboard |
| [desktop](https://github.com/stashysh/desktop) | Desktop app: local API proxy and MCP for files on your computer |

Licensed under Apache 2.0. Questions and ideas are welcome in [Discussions](https://github.com/stashysh/.github/discussions).
