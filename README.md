# Feedbaq

[Feedbaq](https://feedbaq.to) turns your AI agent into a customer researcher. Hear what customers need, watch where they get stuck and understand why they leave, without arranging a call with every participant.

Use the live [Feedbaq connector in Claude](https://claude.ai/directory/connectors/feedbaq), or connect your own AI agent through the free MCP server.

Share a study link and collect voice, narrated screen recording, text or choice answers. AI follow-ups dig into what each person actually said. Use it to test concepts, walk through prototypes, improve onboarding and explore the reasons behind churn.

Connect your own AI agent to draft studies using your product context, compare responses and pull out quotes linked to the evidence. You can also review and refine your questions in Feedbaq's web builder. Participants do not need a Feedbaq account or an installed app.

## Connect in Claude

Feedbaq is live in [Claude's connector directory](https://claude.ai/directory/connectors/feedbaq). Connect your Feedbaq account and choose a workspace. Claude can then build studies and analyze customer responses using the context from your conversation.

## Connect over MCP

Feedbaq runs a free, hosted MCP server:

```text
https://feedbaq.to/mcp
```

The server uses Streamable HTTP and OAuth with PKCE. Add the server in your MCP client, sign in to Feedbaq in the browser, and choose the workspace the agent may access. There is no API key to copy and no server to install locally.

For the current setup steps for Claude, ChatGPT, Codex, Cursor, Grok and other clients, use the [MCP setup guide](https://feedbaq.to/help/mcp). Client availability and administrator permissions vary.

The connection works within the workspace you choose and your existing role. Agents can create and edit study drafts, publish a draft as a new version, and read responses with transcripts and links back to the source answers. Share the participant link yourself; the MCP server does not recruit participants or send study links to them.

## Try these prompts

### Draft a customer feedback study

> Create a short Feedbaq study for people who have used our product in the last month. Ask what they use it for, what gets in their way, and the one change they would make. Use voice answers with one relevant follow-up each. Do not publish it; give me the builder link so I can review it.

### Test a concept

> Draft a Feedbaq concept test for this landing page: [URL]. Ask people to share their screen and say what they think the product does, then what would stop them from signing up. Turn on AI follow-up questions. Do not publish it until I approve the draft.

### Analyze responses

> Read the responses to my "[study name]" study in Feedbaq. Identify the three most common themes. Support each theme with two short quotes and links to their source answers. If there are too few responses to support a conclusion, say so.

## Pricing

The MCP server is free to use. For other Feedbaq plans, see [pricing](https://feedbaq.to/pricing).

## Learn more

- [Feedbaq website](https://feedbaq.to)
- [Help center](https://feedbaq.to/help)
- [MCP setup and access](https://feedbaq.to/help/mcp)
- [Customer research guides](https://feedbaq.to/guides)
- Support: [peter@feedbaq.to](mailto:peter@feedbaq.to)

This repository contains documentation and examples for the hosted service.
