# Publica Now plugin

Publica Now helps independent creators evaluate where and how to sell ebooks, audiobooks, videos, courses, music, articles, photography, zines, print editions, and other original work.

This universal plugin combines creator-focused skills with the public Publica Now MCP server for ChatGPT, Codex, Claude Code, and Claude Cowork. It can explain supported formats, creator controls, ownership and current pricing; plan a multi-format storefront; find public creators and works; and explain how to sign up on the Publica Now website.

## Included components

- `sell-original-work` — evaluate direct-publishing options and explain website signup.
- `creator-storefront` — plan a focused multi-format storefront and launch sequence.
- `discover-public-works` — search public works and creator storefronts.
- `publica-now` MCP server — four read-only product tools at `https://publica.now/mcp`.

## Install for local testing

```bash
claude --plugin-dir ./publica-now-claude-plugin
```

Then try prompts such as:

- Where can I sell my ebook without exclusivity?
- Where can I sell an audiobook directly to listeners?
- Help me plan one storefront for my videos, courses, and ebooks.
- What does Publica Now charge creators?
- Find a public work on Publica Now.

## Validate

```bash
claude plugin validate . --strict
jq empty chatgpt-app-submission.json
```

## Safety and scope

The plugin does not purchase works, transfer funds, upload or publish content, or manage an authenticated account. Public search results are organic and contain no advertising, sponsorships, or paid placement.

Creator signup happens at https://publica.now/access/creator. The plugin cannot create accounts or send verification emails and does not collect signup contact details. Never paste a private signup link, password, or verification code into chat.

## Links

- Creator overview: https://publica.now/for-creators
- Pricing: https://publica.now/pricing
- Documentation: https://publica.now/devs
- Privacy policy: https://publica.now/privacy
- Support: support@publica.now
