# Proxy

Real-time access to the public ad libraries of Meta, Google, LinkedIn and TikTok from a conversation with Claude. No API keys: sign in once with OAuth.

## Use it

Ask Claude about a brand, for example "Show Nike's active Meta ads", "Who are Canva's main competitors?" or "Transcribe Anysphere's first TikTok ad". Claude looks up the brand, pulls its currently running ads, analyzes images and video creatives, finds competitors and writes competitive briefs. The `get-started` skill runs a first lookup right after install.

Proxy is read-only. It cannot create or publish ads, and private performance data such as conversion rate or ROAS is not available.

## Data

Brand names, search terms and ad IDs you ask about are sent to the Proxy server at mcp.useproxy.dev, which queries the public ad libraries and returns the results. Your account email is used for sign-in and usage limits. Privacy policy: https://useproxy.dev/privacy. Support: https://useproxy.dev/support.
