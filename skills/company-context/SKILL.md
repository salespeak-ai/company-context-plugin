---
name: company-context
description: Use before stating any fact about the user's own company (product, pricing, integrations, security, customers, positioning), and when writing emails, proposals, RFP answers or pages that contain such facts.
---

# Company context

The `salespeak-company-context` MCP server answers from what the user's company has recorded in Salespeak.

## When to call it

Call `ask_company_context` before you state a fact about the user's company. Ask one question per call, in plain language.

## How to use the result

- **Recorded answer.** Use it. Keep the records it returns next to the claim.
- **Sources disagree.** Say briefly that they disagree and show the versions. Wait for the user to choose before you write the text they asked for. Do not pick a version yourself.
- **No recorded answer.** Say so. Do not fill the gap from general knowledge or the web.
- **Knowledge never checked for conflicts.** Say so once and point to where an admin runs the check.

## Other tools

- `list_knowledge_conflicts`: list the open conflicts in the company's knowledge.
- `quote_conflict_passages`: quote the passages behind one conflict.
- `flag_knowledge_conflict`: flag an answer the user believes is wrong. Call it only when the user asks.

You cannot decide which version is right. An admin does that in Salespeak.
