# TrueTech CNC Website

Static site for GitHub Pages. All editable content lives in `data.js`, which is edited with `admin.html`.

| File | Purpose |
|------|---------|
| `index.html` | Home page. Equipment, CNC counts and team render from `data.js`. |
| `store.html` | Shop page. Clubs and markers render from `data.js`. |
| `data.js` | Content: `groups`, `machines`, `team`, `clubs`, `markers`. |
| `admin.html` | Editor. Loads live content from GitHub, publishes changes as one commit. |
| `assets/` | Logos and images. New photos go to `assets/images/machines/` or `assets/images/products/`. |

`data.js` is loaded with a script tag, not `fetch`, so the pages also work when opened straight from disk.

See `SETUP-GUIDE.txt` for publishing and the one-time GitHub token setup.
