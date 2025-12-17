# Installation steps for this dummy mcp server

To install the `add_tool` MCP server, run the following command:

```json
{
  "mcpServers": {
    "add_tool": {
      "command": "/Users/guenaelvoisin/.local/bin/uvx",
      "args": [
        "--from",
        "git+https://github.com/gvoisin/mcp-server-deepdive-deployment.git",
        "mcp-server"
      ]
    }
  }
}
```

this will fetch and set up the `mcp-server` from the specified github repository