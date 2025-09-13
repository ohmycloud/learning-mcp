# learning mcp

This is a course on learning MCP. please refer to https://huggingface.co/learn/mcp-course

```bash
uv init mcp-cource
cd mcp-course

uv add "huggingface_hub[mcp]"
uv run huggingface-cli login

# run with TUN mode if you use VPN client like Clash Verge
uv run tiny-agents run agent.json
```
