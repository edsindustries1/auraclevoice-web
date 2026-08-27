# auraclevoice.com

Marketing and legal site for **Auracle Voice** (the app is named AURA on device).

Static HTML. No build step, no dependencies, no JavaScript. Typefaces are self-hosted,
so the site makes no third-party requests at all — which is what its own privacy policy
claims.

## Structure

Every page is `<route>/index.html`, so clean URLs work with no rewrite rules.

| URL | Purpose |
|---|---|
| `/` | Landing page |
| `/pricing` | Free tier and AURA Plus |
| `/support` | Help, getting started, troubleshooting, contact |
| `/limitations` | An honest list of what the app cannot do |
| `/legal` | Index |
| `/legal/privacy` | Privacy Policy — the URL filed with Apple |
| `/legal/terms` | Terms of Service |

Also at root: `robots.txt`, `sitemap.xml`, `.well-known/security.txt`, `404.html`.

## Deployment

GitHub Pages from `main`. The custom domain is set by the `CNAME` file.

## Contact

Contact@auraclevoice.com · security reports use the `[Security]` subject prefix,
also published at `/.well-known/security.txt`.

© 2026 Everyday Digital Solutions.
