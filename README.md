# JSON Formatter & Log Prettifier — export & deploy

Source: Muse artifact `json-formatter-log-prettifier`, v2 (the version with the
fixed Open-file button, built 2026-11-08). The exported file is a byte-for-byte
copy of that artifact's `index.html` (59,674 bytes, SHA-256
`7277f07bd0a2879c8b0844c2dba782ef4425e42ac0ebb6d5939d22d5805ba64d`).

## What's in the file

- `json-formatter-log-prettifier.html` — the whole tool in one file. No backend,
  no database, nothing pasted is saved or sent anywhere.
- Only external dependency: Google Fonts (IBM Plex Sans / JetBrains Mono).
  Offline it still works; it just falls back to system fonts.

## Use it offline

Double-click `json-formatter-log-prettifier.html`, or open it in any browser.
No install, no server.

## Deploy it (pick one, no build step)

### GitHub Pages (free, you own the URL)
1. Create a new public repo, e.g. `json-formatter`.
2. Upload `json-formatter-log-prettifier.html` as `index.html` in the repo root.
3. Settings → Pages → Deploy from branch → `main` / `/ (root)` → Save.
4. Your link is `https://<username>.github.io/json-formatter/`.

### Netlify Drop (fastest, no account setup first)
1. Go to https://app.netlify.com/drop
2. Drag the `.html` file (renamed to `index.html`, or in a folder with it as
   `index.html`) onto the page.
3. Netlify gives you a live `*.netlify.app` link you can rename.

### Vercel (free)
1. Create a project, import a repo containing the file as `index.html`,
   or drag-and-drop the folder in the Vercel dashboard.
2. Deploy with the defaults — no build command, no framework preset needed.

## Keep in mind

- This export is a snapshot of v2. If the tool is edited in Muse later, the
  public Muse link won't auto-update either — re-export and re-upload to get
  the new version in both places.
- Each visitor runs the tool alone in their own browser; there is no shared
  saved state.
