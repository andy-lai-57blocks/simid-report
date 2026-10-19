# SIMID Shoppable Overlay — Test Report & Dark-Release Plan

Static copy of the SIMID test report, originally hosted at:

`https://phoebe.tailb7bc.ts.net/artifacts/00u2r54qoyLs1EEAa697/simid-test-report/index.html`

## Contents

- `index.html` — self-contained single-page report (all CSS/JS inline, no build step)

## Viewing

Open `index.html` directly in a browser, or serve the folder locally:

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

To publish it, enable **GitHub Pages** for this repository
(Settings → Pages → Source: `Deploy from a branch` → `main` / `/ (root)`).

## Notes

- The original page referenced a companion `/comments.js` script that returned
  HTTP 404 on the source host; that dead `<script>` tag was removed.
- Embedded Google Drive previews and outbound links point to their original
  destinations and require the appropriate access.
