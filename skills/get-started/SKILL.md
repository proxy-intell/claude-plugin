---
name: get-started
description: Onboard a new Proxy user. Use right after install to run a first ad-library lookup.
---

Welcome the user to Proxy in one sentence. Then run a first lookup:

1. Ask which brand they want to research (or suggest a competitor of theirs).
2. Call `get_meta_platform_id` and `get_google_platform_id` for that brand.
3. Pull a modest set of ads with `get_meta_ads` or `get_google_ads` and summarize the angles.
4. Offer `search_competitors` and a weekly re-run to track changes: re-running the same pull a day or more later reports which ads are new and how many stopped.

For a bigger job, point them at a playbook skill: `competitor-ad-teardown`, `ad-script-writing`, `winning-product-research`, `brand-ad-audit` and the rest (https://useproxy.dev/playbooks).

Credits are a daily budget. Never state plan limits; report only what `get_credit_balance` returns.
