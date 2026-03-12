# Michael Marino — Digital Ecosystem Landing Page

A premium, dark, mobile-first standalone landing page built for GitHub Pages.

## Overview

This repo contains a single-page founder hub that centralizes Michael Marino's brand ecosystem in one polished destination.

## Brand Links Included

- Avédon Collection — https://avedonco.com
- MT Mug — https://mtmug.com
- Bobby Black NYC — https://bobbyblacknyc.com
- Staten News — https://statennews.com
- By MAM Studio — https://bymamstudio.com

## Social Links Included

- LinkedIn — https://www.linkedin.com/in/michael-anthony-marino-40aba999/
- Instagram — https://instagram.com/avedonco_

## Tech Stack

- `index.html`
- `style.css`
- `script.js`

No framework or build tooling is required.

## Local Preview

Open `index.html` directly, or run:

```bash
python3 -m http.server 4173
```

Then visit: `http://localhost:4173`

## Deployment (GitHub Pages)

1. Push the repository to GitHub.
2. Open **Settings → Pages** in the repository.
3. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or your default branch), `/ (root)`
4. Save changes.
5. Wait for the Pages deployment to complete and open the generated URL.

## Editing Brand Cards

In `index.html`, each brand card is a single `<a class="brand-card">` block with:

- `href` for the destination URL
- `.logo-wrap img` for logo path
- `.brand-name` for title
- `.brand-meta` for descriptor

This makes updates easy without touching JavaScript.
