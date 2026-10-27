# NJ Underwater District Toolkit

Fact sheets and ready-to-share graphics for all 40 New Jersey legislative districts: how many public assets sit in flood zones today and by 2050, and who represents each district. Static site, no build step.

## Live site

Deploy via GitHub Pages from the `main` branch root.

District deep link: `#<district number>`

Example: `https://rebuildbydesign.github.io/nj-flood-risk-districts/#32`

## Files

| Path | Purpose |
|---|---|
| `index.html` | District Toolkit: district finder, fact sheet preview, downloadable graphics (square post, story, wide post, letter poster) |
| `maps/<N>.svg` | District map for the graphics, loaded when a district is picked |
| `sheets/district-<N>.html` | Fact sheet for each district |
| `styles.css`, `district.css` | Fact sheet styles |
| `RBD-logo.png`, `nj-banner.png` | Header assets |

## Data

Source: Rebuild by Design, NJ Underwater. Data as of October 2026. A public asset counts as at risk when it sits within 100 feet of the floodplain. The full method is at the end of each fact sheet.

Questions or the full data workbook: info@rebuildbydesign.org
