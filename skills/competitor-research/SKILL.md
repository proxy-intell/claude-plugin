---
name: competitor-research
description: Research a competitor's advertising across Meta, Google, LinkedIn and TikTok. Use when the user names a brand or domain and wants to know what ads they run, how they position, or who else competes with them.
---

Credits are a daily budget. Fetch a modest limit per brand first, widen only if needed. Never state plan limits; report only what `get_credit_balance` or a tool result says.

1. Resolve the brand: `get_meta_platform_id` and `get_google_platform_id`. Pick the top candidate by verified status and followers; if unsure, say which candidates you considered.
2. Pull ads: `get_meta_ads` and `get_google_ads`. Add `search_linkedin_ads` for B2B brands. For TikTok use `search_tiktok_ads` with the exact registered advertiser name (case-sensitive).
3. Summarize what is observed: ad count, formats, offers, hooks, calls to action, landing pages, how long ads have run. Longer-running ads likely signal winners; say so as an inference.
4. Run `search_competitors` and offer to repeat the pull for the top 2-3.
5. Close with 3 takeaways and one angle the competitor is NOT using.

Separate observed data from inference ("likely", "suggests"). Reach and performance data are not available; do not invent them.
