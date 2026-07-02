# Industrial Power Tool Maintenance (Alberta) Ltd — Website

Repair-shop site for a real Calgary business (8-4115 64 Ave SE · 403-261-0780,
family-owned 50+ years, no website currently listed on their Google profile).
Same single-file architecture as the other Vector Studio tool-store builds:
zero build step, embedded SVG artwork, hash-routed pages.

## Pages
`#/` home · `#/shop` (What We Fix + parts) · `#/brands` (brands serviced) ·
`#/services` (repair process timeline) · `#/about` (50-year family story) · `#/contact`

## Deploy to GitHub Pages
```bash
git init && git add . && git commit -m "IPTM Calgary website"
git branch -M main
git remote add origin git@github.com:arjuncad02/iptm-calgary.git
git push -u origin main
```
Settings → Pages → main / (root). Live at https://arjuncad02.github.io/iptm-calgary/

## Before pitching / launch
- Hours are set to Mon–Fri 8:00–5:00 (their Google profile shows both 4pm and 5pm
  closes in different places — confirm with the owner and adjust in index.html:
  hours card, visit banner, footer, and JSON-LD `openingHours`).
- Confirm the brands-serviced list and the "free estimate" wording with the owner.
- Wire the contact form to Web3Forms (access key in the contactForm handler).
- Swap the map placeholder for a Google Maps embed of 8-4115 64 Ave SE.
- If they buy a domain, add a CNAME file and update robots.txt / sitemap.xml / og:url.
