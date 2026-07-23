# CERVR.ai — Marketing Website

A simple, self-contained static marketing website for **CERVR.ai** (AI-powered
commercial property solutions). Built to establish a verifiable web presence for
the `cervr.ai` domain — no backend required.

## Files
- `index.html` — single-page marketing site (hero, services, AI intelligence, method, coverage, about, contact)
- `privacy.html` — privacy policy
- `styles.css` — all styling (no external dependencies)
- `assets/logo.svg`, `assets/favicon.svg` — brand marks

## Preview locally
Just open `index.html` in a browser, or serve the folder:

```sh
cd cervr-ai
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Deploy to the cervr.ai domain
The site is fully static, so it can be hosted anywhere:
- **Cloudflare Pages / Netlify / Vercel** — drag-and-drop this folder, then point the `cervr.ai` domain at the deployment.
- **GitHub Pages** — push to a repo, enable Pages, add `cervr.ai` as the custom domain.
- **Any static host / S3** — upload the folder contents to the web root.

Once live at `https://cervr.ai`, the site presents company name, services, coverage,
a privacy policy, and working contact details — the kind of legitimate web presence
used to verify an organization during Apple Developer Program enrollment.

## Notes
- Contact phone numbers are CERV Property Solutions' published lines. The email
  `cervappdeveloper@cervr.ai` is a placeholder — set up that mailbox (or update it) before verification.
- Update the physical/legal address in the footer if Apple requires an address matching
  your D-U-N-S / legal entity record.
