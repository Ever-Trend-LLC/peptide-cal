# Peptide Calculator Pro

Static site for [peptidecalculatorpro.org](https://peptidecalculatorpro.org): free, browser-based peptide calculators with supporting copy.

Everything runs client-side. No accounts, no uploaded data, no backend.

## Pages

| Page | Path | Source |
|---|---|---|
| Peptide Calculator (home) | `/` | `src/home.html` |
| Peptide Reconstitution Calculator | `/peptide-reconstitution-calculator/` | `src/reconstitution.html` |
| Peptide Dosage Calculator | `/peptide-dosage-calculator/` | `src/dosage.html` |
| Peptide Blend Calculator | `/peptide-blend-calculator/` | `src/blend.html` |
| Peptide Dilution Calculator | `/peptide-dilution-calculator/` | `src/dilution.html` |
| Peptide Concentration Calculator | `/peptide-concentration-calculator/` | `src/concentration.html` |
| mg to mL Calculator | `/mg-to-ml-calculator/` | `src/mg-to-ml.html` |
| BAC Water Calculator | `/bac-water-calculator/` | `src/bac-water.html` |
| Molarity Calculator | `/molarity-calculator/` | `src/molarity.html` |
| Peptide Property Calculator | `/peptide-property-calculator/` | `src/peptide-property.html` |
| Peptide Molecular Weight Calculator | `/peptide-molecular-weight-calculator/` | `src/molecular-weight.html` |
| Peptide Net Charge Calculator | `/peptide-net-charge-calculator/` | `src/net-charge.html` |
| Retatrutide Peptide Calculator | `/retatrutide-peptide-calculator/` | `src/retatrutide.html` |
| KLOW Peptide Calculator | `/klow-peptide-calculator/` | `src/klow.html` |
| TDEE Calculator | `/tdee-calculator/` | `src/tdee.html` |
| Blog index | `/blog/` | `src/blog.html` |
| What is a peptide | `/blog/what-is-a-peptide/` | `src/blog-what-is-a-peptide.html` |
| What are peptides used for | `/blog/what-are-peptides-used-for/` | `src/blog-what-are-peptides-used-for.html` |
| BAC water guide | `/blog/bac-water/` | `src/blog-bac-water.html` |
| How much BAC water to add | `/blog/how-much-bac-water-to-add/` | `src/blog-how-much-bac-water.html` |
| Doses per vial guide | `/blog/how-many-doses-per-vial/` | `src/blog-how-many-doses-per-vial.html` |
| Partners | `/partners/` | `src/partners.html` |
| About | `/about/` | `src/about.html` |
| Medical disclaimer | `/disclaimer/` | `src/disclaimer.html` |
| Privacy policy | `/privacy/` | `src/privacy.html` |

`src/hgh.html` is not built: `/hgh-peptide-dose-calculator/` was retired (404) and every internal link to it was removed.

Every page is registered in `PAGES` in [build.py](build.py), which also generates the sitemap, canonical tags, Open Graph tags, breadcrumbs and JSON-LD. Adding a page means adding a `src/*.html` body plus a `PAGES` entry.

## Structure

```text
build.py        page table, layout template, SEO/JSON-LD, sitemap
server.js       zero-dependency static server for dist/
src/            page bodies (HTML fragments)
assets/         shared CSS, JS, images
dist/           generated output, committed to the repo
ts/             TypeScript source for the BAC water calculator
tests/          node --test specs for shared calculation logic
docs/           backlink plan and outreach notes
app/            Capacitor wrapper for the Android build (not part of the site)
```

## Build

```bash
npm install
npm run build
```

`npm run build` runs `tsc`, copies `assets/bac-water.mjs`, then runs `python3 build.py`, which writes the site into `dist/`.

`SITE_URL` in `build.py` sets the canonical domain and sitemap URLs.

## Test

```bash
npm test        # node --test tests/*.test.mjs
npm run typecheck
```

## Deploy

`dist/` is committed, so no build step is needed on the host.

- AnySites (Node): `npm start` runs `server.js` on `$PORT` (default 3000).
- Any static host: publish the `dist/` directory.
- After editing `src/` or `assets/`, run `python3 build.py` locally and commit the regenerated `dist/`.

Redirect `www` to the apex domain with a 301 and keep trailing slashes on URLs.

## SEO notes

- [docs/backlink-plan.md](docs/backlink-plan.md) tracks the off-site plan: target lists, executed outreach, anchor-text matrix and acceptance criteria.
- Each calculator page owns one primary keyword. The home page targets `peptide calculator`, the dosage page `peptide dosage calculator`, the reconstitution page `peptide reconstitution calculator`; the BAC water and mg-to-mL pages stay narrow so they do not compete with them.
- Health content is YMYL: copy explains measurement and conversion, not dosing advice, and carries the disclaimer.
