# IMC Dashboard

MLB Hong Kong IMC planning dashboards, published with GitHub Pages.

## Dashboards

| Season | Folder | Live link |
|--------|--------|-----------|
| FW26 | `FW26 IMC Dashboard/` | https://fnf-hongkong.github.io/IMC-Dashboard/FW26%20IMC%20Dashboard/ |

The repository root redirects to the FW26 dashboard, so
https://fnf-hongkong.github.io/IMC-Dashboard/ also opens it.

## Notes

- Each dashboard is a single self-contained `index.html` (images embedded inline),
  so no build step and no external assets are required.
- `.nojekyll` is present at the root and in each dashboard folder so GitHub Pages
  serves the files as-is.
- To publish an update, replace the `index.html` in the season folder and push to `main`.
  GitHub Pages redeploys automatically; add a cache-busting query such as `?v=2`
  when sharing a freshly updated link.
