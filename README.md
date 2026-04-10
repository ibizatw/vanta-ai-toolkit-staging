# GoWarehouse AI Toolkit

Connect your AI tools to the [GoWarehouse](https://www.gowarehouse.asia) WMS platform.

## Available Tools

| Tool | Description |
|------|-------------|
| `search_products` | Search products by keyword |
| `get_product` | Get product details by ID |
| `list_inbounds` | List inbound shipments |
| `get_inbound` | Get inbound shipment details |
| `list_orders` | List orders with filters |
| `get_order` | Get order details |

## Installation

### Gemini CLI

```bash
gemini extensions install https://github.com/vantawms/gowarehouse-ai-toolkit
```

### Claude Code

```bash
claude plugins install https://github.com/vantawms/gowarehouse-ai-toolkit
```

### Cursor / VS Code

Add to your MCP settings or install via the plugin marketplace.

## Authentication

This toolkit uses **OAuth 2.0** to securely connect to your GoWarehouse account. On first use, your AI tool will open a browser window for you to authorize access. You'll select which merchant's data the AI can access.

- Access tokens expire after 1 hour and refresh automatically
- You can revoke access at any time from GoWarehouse settings

## Requirements

- A GoWarehouse account with at least one merchant
- A supported AI tool (Gemini CLI, Claude Code, Cursor, VS Code, Codex CLI)

## License

MIT
