# lightarc.app

The website for Lightarc, a weight trend tracker for Android by OMS (Open Mindset Group LLC). Plain HTML and CSS, published with GitHub Pages from the `main` branch root. No build step.

## Pages

| Path | Page |
| --- | --- |
| `/` | Home: the app pitch and the Google Play link |
| `/guides/` | Guides index |
| `/guides/move-weight-history-to-android/` | Moving your weight history from Libra or Happy Scale |
| `/guides/trend-vs-daily-number/` | Why the trend beats the daily number |
| `/guides/new-year-tracking-start/` | Starting to track in the new year |
| `/guides/glp1-doses-and-weight-one-chart/` | GLP-1 doses and weight on one chart |
| `/press/` | Press kit |
| `404.html` | Not-found page |

The privacy policy stays at https://openmindsetgroup.com/lightarc_terms.html (it is generated from the app's strings and must match Play Console and the app), so this site links to it rather than copying it.

## Where the words come from

Guide and press-kit text comes from `lightarc/copy/launch/` in `openmindsetgroup/marketing`, and every claim from `lightarc/store-listing/FACTS.md` there. Copy rules: no medical claims, never "offline" (say "No account. Your data stays on your phone."), no tap counts, "small independent studio" (never "tiny"), and no medication brand names on this site.

## Other files

- `CNAME`: the custom domain, `lightarc.app`.
- `.nojekyll`: serve the files as they are.
- `robots.txt` and `sitemap.xml`: for search engines. Add new pages to `sitemap.xml`.
