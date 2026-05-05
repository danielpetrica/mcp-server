# LaraPlugins MCP Server

Connect LLMs to the LaraPlugins.io directory for validated Laravel plugin data.

## About

This MCP server provides AI agents with structured access to Laravel plugin health scores, compatibility information, and vendor reputation data.

## Available Tools

- **SearchPluginTool** - Search packages by keyword, health band, Laravel version
- **GetPluginDetailsTool** - Fetch detailed metrics, readme, version history

## Usage

Add this to your MCP client configuration:

```json
{
  "mcpServers": {
    "laraplugins": {
      "type": "streamable-http",
      "url": "https://laraplugins.io/mcp/plugins"
    }
  }
}
```

## Links

- [LaraPlugins.io](https://laraplugins.io)
- [MCP Registry](https://registry.modelcontextprotocol.io)

## Publishing

This package is published to:
- npm: `@laraplugins/mcp-server`
- Composer: `laraplugins/mcp-server`
- MCP Registry: `laraplugins.io/mcp`