# MarketFlow — Demand Radar

MarketFlow helps product builders discover public conversations that may reveal customer demand, understand why a discussion is relevant, and prepare thoughtful responses for human review.

## Current working scope
- Responsive browser-based Demand Radar.
- Live Hacker News search through the public Algolia API.
- Transparent keyword and intent relevance scoring.
- Evidence links to original public discussions.
- Editable response drafts and approve/dismiss review workflow.
- Browser-local persistence.

## Run locally
Open `index.html` in a modern browser. An internet connection is required for Hacker News search.

## Important limitations
This is an early browser MVP, not yet a production multi-user SaaS. Reddit, X, LinkedIn, and automated public-web discovery are not connected. No AI model, account system, cloud database, scheduled scans, notifications, billing, or automatic outreach is enabled. All public interactions remain manual and require human review. Never treat a relevance score as proof of buying intent.

## Deploy
Import this repository into Vercel as a static site. The root `index.html` is the entry point; no build command is required.
