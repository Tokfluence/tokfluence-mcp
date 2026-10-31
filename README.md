# Tokfluence MCP Server

Remote MCP server for TikTok creator discovery and analytics, powered by the Tokfluence API.

- Endpoint: `https://developers.tokfluence.com/mcp` (Streamable HTTP)
- Auth: OAuth sign-in or a Bearer API key from your Tokfluence dashboard (any plan, including Free; calls use your plan's API credits)
- Tools: 15 (creator search, profiles, audience, engagement, and more)

## Connect

Claude / Cursor / any MCP client:

```json
{
  "mcpServers": {
    "tokfluence": {
      "url": "https://developers.tokfluence.com/mcp",
      "headers": { "Authorization": "Bearer YOUR_TOKFLUENCE_API_KEY" }
    }
  }
}
```

Or add the URL as a custom connector and sign in with OAuth.

## Docs and support

- Docs: https://developers.tokfluence.com/docs
- Support: support@tokfluence.com

Source: https://github.com/Tokfluence/tokfluence-mcp
