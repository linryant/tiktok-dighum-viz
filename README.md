# TikTok Engagement & Content Evolution — Visualizations

Interactive visualizations for the research question:
**How do TikTok engagement metrics (likes, comments, follower counts) shift the content strategies of top-ranked influencers?**

Built for DIGHUM 100 (UC Berkeley) — Theory and Methods in the Digital Humanities.

## Pages

| File | What it shows | Data source |
|---|---|---|
| `influencer-tiers.html` | How engagement composition shifts as creators scale (the "cost of visibility") | Kaggle: `prasertk/top-1000-tiktok-influencers-ranking` (HypeAuditor, real) |
| `hashtag-strategy.html` | Which hashtags top-tier vs bottom-tier creators actually use | Kaggle: `vbradculbertson/tiktok-trending-metadata` (scraped video metadata, real) |
| `index.html` | Landing page linking both | — |

Each page is self-contained (Chart.js via CDN, data inlined) and embeds in Google Sites via **Insert → Embed → By URL**.

## Hosting on GitHub Pages

1. Push this repo to GitHub.
2. Repo **Settings → Pages → Source: Deploy from branch → `main` → `/(root)` → Save**.
3. After ~1 minute the pages are live at:
   - `https://<username>.github.io/<repo>/influencer-tiers.html`
   - `https://<username>.github.io/<repo>/hashtag-strategy.html`

## Embedding in Google Sites

1. **Insert → Embed → By URL**, paste a page URL.
2. Resize the frame to full width and generous height (~2200px for influencer-tiers, ~1100px for hashtag-strategy).
3. Publish.

## Data notes

Analysis excludes synthetic Kaggle datasets whose engagement was uniform across content categories; only verified-real sources are used. See in-page notes for methodology and caveats.
