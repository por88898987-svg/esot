# BreachSignal

Privacy-first static site for GitHub Pages. It helps users validate an email address or phone number locally in the browser, then opens trusted official breach-check services.

## What it is

- Single-file frontend with no build step
- Safe default for GitHub Pages or Netlify
- No backend and no analytics by default
- Honest about limitations: real direct breach APIs usually need keys or verified ownership

## Files

- `index.html` - app UI, styles, and browser-only logic
- `manifest.webmanifest` - optional install metadata

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload the contents of this folder.
3. Open repository `Settings > Pages`.
4. Set the source to your main branch root.
5. Save and wait for the public URL.

## Good next upgrades

- Add a serverless proxy only for authenticated APIs you trust.
- Add a custom domain and a tiny privacy policy page.
- Add translated text if you want both Turkish and English.
