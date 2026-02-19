# alexjser-mcp-demo

MCP demo project (Python 3.13+, mcp[cli]).

## 包链接

- PyPI: https://pypi.org/project/alexjser-mcp-demo/

## Cursor MCP 配置

在 Cursor 中配置 MCP 服务器，将以下内容加入 MCP 配置（如 `~/.cursor/mcp.json` 或项目中的 MCP 设置）：

```json
{
  "mcpServers": {
    "mcp-demo": {
      "command": "uvx",
      "args": [
        "alexjser-mcp-demo"
      ]
    }
  }
}
```
