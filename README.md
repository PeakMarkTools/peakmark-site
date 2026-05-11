# PeakMark Website

Marketing landing page for [peakmarktools.com](https://peakmarktools.com) — hosted on GitHub Pages.

## Setup

1. Push this repo to GitHub under `PeakMarkTools/peakmark-site`
2. Go to repo **Settings → Pages**
3. Source: **Deploy from a branch** → Branch: `main` → Folder: `/ (root)`
4. Click **Save**
5. Point your GoDaddy domain to GitHub Pages (see below)

## Connecting GoDaddy Domain

In GoDaddy DNS settings, add these records:

| Type | Name | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | peakmarktools.github.io |

Then in GitHub repo Settings → Pages → Custom domain → enter `peakmarktools.com`

Check "Enforce HTTPS" once the domain verifies (takes up to 24 hours).

## Updating the Site

Just edit `index.html` and push to `main` — GitHub Pages deploys automatically within ~2 minutes.
