# viraledge-data

Public feed data for the [ViralEdge](https://github.com/Jflores37/viral-edge) dashboard.

The scraper publishes one JSON file per niche here every ~10 minutes; the site
reads them over `raw.githubusercontent.com`'s CDN. This is free storage that
replaced Vercel Blob (which suspends on the free tier).

Contents (`viraledge/`):
- `feed-<niche>.json` — recent public tweets per niche
- `posthours.json` — hour-of-day engagement buckets
- `growthlog.json` — the tracked account's public profile + follower history + posts

All data here is already-public tweet data. No secrets.
