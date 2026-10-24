# ETP Portal

Monitoring portal for the Emerging Talent Program (ETP) 2026: TPG Index summary, Kirkpatrick L3
funnel, KPI status by department and talent, and an editable talent list.

## Files

- `index.html` — the portal (served by GitHub Pages)
- `dashboard.html` — the original sample monitor dashboard

## Data

This repository does **not** contain any staff data.

- **On GitHub Pages / as a local file:** click **Choose file…** and pick the ETP Master List (.xlsx)
  or a CSV downloaded from the portal. The file is read in the browser only and kept in that
  browser (localStorage). Use **Download CSV** to keep changes and **Clear data** to remove the
  data from the browser.
- **On claude.ai:** the portal connects to the team's shared database.

## Enable GitHub Pages

1. Settings → General → Danger Zone → **Change visibility** → Public
2. Settings → **Pages** → Source: *Deploy from a branch* → branch `master`, folder `/ (root)` → Save
3. The portal will be available at `https://azizulmohdshariff.github.io/Talent-Pool/`
