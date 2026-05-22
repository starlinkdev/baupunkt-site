# Baupunkt Site

Public support, privacy and product-overview pages for Baupunkt.

This repository contains a small static website. It uses no JavaScript, no
analytics, no cookies, no external fonts and no CDN assets.

## Public Positioning

Baupunkt is presented as a local-first renovation cockpit for owners and small
project teams. Public claims must stay conservative:

- no Baupunkt cloud sync claim
- no shared multi-user service claim
- no macOS or iOS App Store availability claim
- no internal implementation or operations details
- no legal, tax or construction-advice promise

## Pages

- `/`
- `/privacy.html`
- `/support.html`

## Expected URLs

- `https://starlinkdev.github.io/baupunkt-site/`
- `https://starlinkdev.github.io/baupunkt-site/privacy.html`
- `https://starlinkdev.github.io/baupunkt-site/support.html`

## Enable GitHub Pages

1. Open the GitHub repository `baupunkt-site`.
2. Go to `Settings`.
3. Open `Pages`.
4. Under `Build and deployment`, choose `Source: Deploy from a branch`.
5. Select `Branch: main`.
6. Select `Folder: /root`.
7. Save.

GitHub Pages can publish static files from a branch and either the repository
root or `/docs` folder. This site is prepared for `main` and `/root`.
