# CCC Intelligence Hub

A coded front door for the Cross-Catchment Collective's coordination and intelligence system.

## Design direction

A command space rather than a reading space: deep forest greens, dark slate, signal amber, and an observatory-at-night atmosphere.

## Files

- `index.html` — page structure
- `css/style.css` — visual design
- `js/dashboard.js` — renders the page from JSON
- `data/dashboard.json` — the only file normally edited
- `README.md` — setup notes

## Publish on GitHub Pages

1. Create a public repository called `ccc-intelligence-hub`.
2. Upload all files and folders while preserving the folder structure.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**.
5. Select `main` and `/root`, then save.

Live URL:

`https://YOUR-USERNAME.github.io/ccc-intelligence-hub/`

## Configure the dashboard

Edit `data/dashboard.json`.

Replace the placeholder links under `links` with the real Notion forms/databases and Google Drive root folder. Replace the partnership placeholders with real partnership names and URLs. The headline metrics are manual in version one.

## Embed in Notion

1. Copy the GitHub Pages URL.
2. In Notion, type `/embed`.
3. Paste the URL.
4. Make the embed full width and tall enough to feel like a dashboard.

## Architecture

- GitHub Pages = experience and navigation
- Notion = records, relationships and workflow
- Google Drive = source evidence and large files
- AI = synthesis and pattern detection
- Human reviewers = validation and authority

## Security

Do not place private Notion API tokens in this public website. A future live-data version should use a secure backend or serverless function.
