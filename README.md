# ETP Portal

Monitoring portal for the Emerging Talent Program (ETP) 2026: TPG Index summary, Kirkpatrick L3
funnel, KPI status by department and talent, and an editable talent list.

## Files

- `public/index.html` — the portal (published by Netlify)
- `netlify.toml` — Netlify settings: publishes `public/` only and asks search engines not to index the site
- `dashboard.html` — the original sample monitor dashboard (not published)

## Data

This repository does **not** contain any staff data. On Netlify, click **Choose file…** and pick the
ETP Master List (.xlsx) or a CSV downloaded from the portal. The file is read in the browser only and
kept in that browser (localStorage). Use **Download CSV** to keep changes and **Clear data** to remove
the data from the browser.

## Deploy on Netlify

1. Sign in at https://app.netlify.com → **Add new site** → **Import an existing project** → **GitHub**
2. Authorise Netlify and pick `azizulmohdshariff/Talent-Pool` (the repo can stay private)
3. Leave the build settings as detected from `netlify.toml` (publish directory `public`) → **Deploy**
4. **Site configuration → Change site name** to choose the address, e.g. `etp-portal.netlify.app`

Every push to `master` redeploys the site automatically.
