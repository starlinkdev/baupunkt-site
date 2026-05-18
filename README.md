# Baupunkt Site

Public support and privacy pages for Baupunkt.

This repository contains a small static website for App Store and TestFlight
preparation. It uses no JavaScript, no analytics, no cookies, no external
fonts and no CDN assets.

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

## Before App Store Submission

- Replace `support@example.com` with the final support contact.
- Review the Privacy Policy draft.
- Add a final support URL and Privacy Policy URL to App Store Connect.
- Optionally configure a custom domain later.
