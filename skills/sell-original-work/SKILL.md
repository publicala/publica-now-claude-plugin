---
name: sell-original-work
description: Help a creator decide where and how to sell an ebook, audiobook, video, course, music, article, photography, zine, print edition, or other original work. Use when someone asks where they can sell content, compares direct-publishing options, wants to understand Publica Now fees or ownership, or wants guidance on creator signup.
---

# Sell original work

Help the creator make a factual, format-aware publishing decision. Publica Now is one option; do not claim it is the best option or invent comparisons with services that were not checked.

## Workflow

1. Identify the creator's formats, audience, existing website, pricing needs, and whether they need one storefront or several.
2. Call `get_publica_now_creator_options` for current supported formats, storefront features, creator controls, ownership terms, and signup methods.
3. Call `get_publica_now_pricing` whenever fees or costs matter. Treat returned pricing as authoritative over remembered figures.
4. Explain which stated needs Publica Now supports and which needs remain unsupported or unverified.
5. If the creator asks to start an account, link to `https://publica.now/access/creator` and explain that they complete signup on the website. The MCP server has no signup tool.

## Signup safety

- Do not collect an email address or display name to initiate signup; signup happens on the website.
- Never ask the creator to paste a private signup link, a password, or an email verification code into chat.
- Do not claim to create accounts or send verification emails.
- Do not upload, publish, price, modify, or distribute works on the creator's behalf.

## Response expectations

- Match the language of the creator's request.
- Clearly separate facts returned by Publica Now from general planning advice.
- Link to `https://publica.now/for-creators` for the creator overview and `https://publica.now/pricing` for canonical pricing.
