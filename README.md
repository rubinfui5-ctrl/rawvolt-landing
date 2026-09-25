# RAWVOLT Landing Page — Landing Hub

Landing page + link-in-bio hub for the RAWVOLT brand. Single-file static site (index.html), zero dependencies, free hosting.

## Sections
1. **Hero** — brand hook, tagline, CTAs (Shop the Drop / Free Apps)
2. **The Drop** — RAWVOLT Hoodie Stone + Navy (320gsm Scuba Ponte, YKK Excella Gold)
3. **Free Apps** — The Standard, The Iron, 21-Day Challenge, Home Guard (rawvolt-products.netlify.app)
4. **Protocols** — RAWVOLT discipline programs (from deals-site-data.json)
5. **Footer** — IG links, store link, contact

## Deploy (free, no Lovable)
- Netlify: `netlify deploy --dir .` or drag-drop the folder
- Or GitHub Pages: push this repo, enable Pages on main

## Brand
- Voice: "Locked like your word."
- Colors: black #080808, volt blue #0066FF, gold #FFD700
- Fonts: Cormorant Garamond (display) + Montserrat (body)

## Data sources
- Product specs: C:/Solomon-Empire/data/content/meta-ai-artifacts/ (LUX tech pack)
- Product photos: C:/Solomon-Empire/data/content/meta-ai-rawvolt/ (69 assets)
- Programs: C:/Solomon-Empire/data/deals-site-data.json
- Apps: rawvolt-products.netlify.app

## GoDaddy domain connection
Once deployed to Netlify, in GoDaddy DNS:
- Add CNAME `@` (or A records pointing to Netlify's load balancer 75.2.60.5 / 99.83.190.102)
- Add CNAME `www` → your-site.netlify.app
- Or use Netlify's "Add domain" wizard and it walks you through it
