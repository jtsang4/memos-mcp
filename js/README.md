# memos-mcp

This package downloads the prebuilt `memos-mcp` binary from GitHub releases and runs it in MCP stdio mode.

## Usage

```bash
npx @jtsang/memos-mcp --base-url http://localhost:5230 --access-token YOUR_TOKEN
```

You can also provide config via environment variables:

- `MEMOS_BASE_URL`
- `MEMOS_ACCESS_TOKEN` or `MEMOS_API_TOKEN`

## MCP client config

```json
{
  "mcpServers": {
    "memos": {
      "command": "npx",
      "args": ["@jtsang/memos-mcp", "--base-url", "http://localhost:5230", "--access-token", "YOUR_TOKEN"]
    }
  }
}
```
