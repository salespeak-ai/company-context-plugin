# Salespeak Company Context

Ask about your own company from your agent: product, pricing, integrations, security, customers, positioning. Answers come from what your company has recorded in Salespeak, with the records attached. When your sources disagree, the agent shows both versions and waits for you to choose.

## What is in this plugin

- `mcp.json`: the remote MCP server `https://platform.salespeak.ai/company/mcp`.
- `skills/company-context`: tells the agent when to ask and how to handle disagreement and missing answers.

## Requirements

A Salespeak account. Sign-up and docs: https://platform.salespeak.ai/docs#company-connector

## Setup

1. Install the plugin.
2. On first use the agent opens a Salespeak sign-in (OAuth). Sign in with your Salespeak account.
3. Ask: "What do we say about SSO?"

No API key or environment variable is needed.

## Tools

| Tool | What it does | Writes? |
|---|---|---|
| `ask_company_context` | Answers one question from recorded company knowledge | No |
| `list_knowledge_conflicts` | Lists open conflicts | No |
| `quote_conflict_passages` | Quotes the passages behind a conflict | No |
| `flag_knowledge_conflict` | Flags an answer for an admin to review | Yes, a flag only |

## Support

support@salespeak.ai · Privacy: https://salespeak.ai/privacy-policy/company-context/

## License

MIT
