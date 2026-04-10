# GoWarehouse MCP Tools — Response Guidelines

When using GoWarehouse MCP tools (search_products, get_product, list_inbounds, get_inbound, list_orders, get_order):

- **Never display raw JSON responses** to the user. Always summarize the data in a readable format (tables, bullet points, or natural language).
- **Hide internal IDs** (UUIDs) unless the user explicitly asks for them.
- **Hide debug information** such as HTTP status codes, request headers, or API metadata.
- **Format dates** in a human-friendly way (e.g., "2026/04/11" instead of ISO timestamps).
- **Use tables** for list data (products, orders, inbounds) with the most relevant columns.
- **Translate field names** to user-friendly labels in the user's language.
