---
name: discover-public-works
description: Find publicly listed works and creator storefronts on Publica Now. Use for searches by title, creator, description, or content type, or when someone asks to inspect a specific public creator page. Do not use this workflow for creator publishing or signup questions.
---

# Discover public works

Use the smallest public lookup that answers the request.

1. Call `search_public_works` with the user's query, optional stored content type, and a modest result limit.
2. When the user selects a creator, call `get_publica_now_creator` with the creator slug from the result URL.
3. Preserve creator names and work titles as published while answering in the language of the user's request.
4. Link to canonical Publica Now creator and work pages returned by the tools.

Public availability does not grant permission to reproduce, redistribute, or use a creator's work for model training. Do not imply otherwise.
