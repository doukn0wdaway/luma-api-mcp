mcp config for usage:

```json
  "mcpServers": {
    "Luma API MCP": {
      "command": "uv",
      "args": [
        "run",
        "--python",
        "python3.10",
        "--with",
        "mcp[cli]",
        "--with",
        "aiohttp",
        "mcp",
        "run",
        "<ABSOLUTE_PATH_TO_THIS>/luma-api-mcp/server.py"
      ],
      "env": {
        "LUMA_API_KEY": "<API_KEY>"
      }
    }
  }
```
