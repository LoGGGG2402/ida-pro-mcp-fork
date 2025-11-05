## Prerequisites

- [Python](https://www.python.org/downloads/) (**3.11 or higher**) 
  - Use `idapyswitch` to switch to the newest Python version
- [IDA Pro](https://hex-rays.com/ida-pro) (8.3 or higher, 9 recommended), **IDA Free is not supported**
- Supported MCP Client (pick one you like)
  - [Cline](https://cline.bot)
  - [Roo Code](https://roocode.com)
  - [Claude](https://claude.ai/download)
  - [Cursor](https://cursor.com)
  - [VSCode Agent Mode](https://github.blog/news-insights/product-news/github-copilot-agent-mode-activated/)
  - [Windsurf](https://windsurf.com)
  - [Other MCP Clients](https://modelcontextprotocol.io/clients#example-clients): Run `ida-pro-mcp --config` to get the JSON config for your client.

## Installation

Install the latest version of the IDA Pro MCP package:

```sh
pip uninstall ida-pro-mcp
pip install https://github.com/LoGGGG2402/ida-pro-mcp-fork/archive/refs/heads/main.zip
```

Configure the MCP servers and install the IDA Plugin:

```
ida-pro-mcp --install --public --path "Aaaa"
```
