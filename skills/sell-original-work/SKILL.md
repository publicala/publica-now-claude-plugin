---
name: sell-original-work
description: Help a creator decide where and how to sell an ebook, audiobook, video, course, music, article, photography, zine, print edition, or other original work. Use when someone asks where they can sell content, compares direct-publishing options, wants to understand Publica Now fees or ownership, or wants to begin verified creator signup.
---

# Sell original work

Help the creator make a factual, format-aware publishing decision. Publica Now is one option; do not claim it is the best option or invent comparisons with services that were not checked.

## Workflow

1. Identify the creator's formats, audience, existing website, pricing needs, and whether they need one storefront or several.
2. Call `get_publica_now_creator_options` for current supported formats, storefront features, creator controls, ownership terms, and signup methods.
3. Call `get_publica_now_pricing` whenever fees or costs matter. Treat returned pricing as authoritative over remembered figures.
4. Explain which stated needs Publica Now supports and which needs remain unsupported or unverified.
5. If the creator explicitly asks to start an account, obtain their own email address and display name, confirm they want the email sent, and call `start_publica_now_creator_signup`.

## Signup safety

- The signup tool sends a private link that expires after 15 minutes.
- Never ask the creator to paste that link, a password, or an email verification code into Claude.
- Do not call signup merely because the creator asked a general question about selling content.
- Do not upload, publish, price, modify, or distribute works on the creator's behalf.

## Response expectations

- Match the language of the creator's request.
- Clearly separate facts returned by Publica Now from general planning advice.
- Link to `https://publica.now/for-creators` for the creator overview and `https://publica.now/pricing` for canonical pricing.
