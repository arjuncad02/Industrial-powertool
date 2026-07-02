# Industrial Powertool — Website

Sister site to the Ammo Power Tool build: same single-file architecture, steel-blue
industrial brand system, contractor/metalworking positioning. Zero build step, all
artwork embedded SVG, no external images.

## Deploy to GitHub Pages

```bash
git init
git add .
git commit -m "Industrial Powertool website"
git branch -M main
git remote add origin git@github.com:arjuncad02/industrial-powertool.git
git push -u origin main
```

Settings → Pages → Deploy from a branch → main / (root).
Live at `https://arjuncad02.github.io/industrial-powertool/`.

## Before launch — confirm client details

Contact info currently mirrors the Ammo Richmond location (2088 No 5 Rd · 604-270-2666),
on the assumption this is their industrial division. If it's a separate business,
search-replace the address and phone in `index.html` (they appear in the JSON-LD schema,
header, contact page, footer and sticky call bar).

Also swap in the Web3Forms access key in the `contactForm` handler, and update
`robots.txt` / `sitemap.xml` if using a custom domain.

## Pages

`#/` home · `#/shop` · `#/brands` · `#/services` · `#/about` · `#/contact`
