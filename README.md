# ignaciodiazpacce.com.ar

Personal portfolio of Ignacio Diaz Pacce — Product Engineer · Operations · Founding Engineer.

Single-page site, no build step. Plain HTML/CSS/JS with inline i18n (EN default, ES, PT).

## Stack

- Static HTML/CSS/JS (no framework, no build).
- Hosted on Vercel.
- Domain: `ignaciodiazpacce.com.ar`.

## Structure

```
index.html       # whole site (markup, styles, i18n, scripts inline)
robots.txt       # search engine directives
sitemap.xml      # URL map + hreflang for EN/ES/PT
```

## Local preview

Open `index.html` in any browser. No server required.

For a proper local server (recommended to test hash routing and fetch behavior):

```bash
python -m http.server 8000
# or
npx serve .
```

Then open http://localhost:8000.

## Before deploying

- [ ] Place `CV_Ignacio_Diaz_Pacce.pdf` at the project root (referenced by the hero "Download CV" button).
- [ ] Add `og-image.png` (1200×630) at the project root for social previews (LinkedIn, WhatsApp, Twitter).
- [ ] Confirm `ignaciodiazpacce.com.ar` points to this project in Vercel.
- [ ] Submit `sitemap.xml` to Google Search Console after first deploy.

## Content ownership

Copy, positioning and structural decisions live in the `/memory` profile outside this repo. Update memory first, then propagate to `index.html`.
