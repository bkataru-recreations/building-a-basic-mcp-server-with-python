# building-a-basic-mcp-server-with-python

following [Building a Basic MCP Server with Python](https://medium.com/data-engineering-with-dremio/building-a-basic-mcp-server-with-python-4c34c41031ed)

## setup

```bash
$ uv run main.py
```

or in your MCP config:

```json
{
  "mcpServers": {
    "mix_server": {
      "command": "uv",
      "args": [
        "--directory",
        "/ABSOLUTE/PATH/TO/mix_server",
        "run",
        "main.py"
      ]
    }
  }
}
```
