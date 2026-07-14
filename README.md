# BlueSky Building Maintenance, Website Redesign (Light Theme)

A premium, single-page marketing site for BlueSky Building Maintenance (a member of the H&S Group of Companies), built with HTML + Tailwind CSS + vanilla JS. Light luxury aesthetic in the brand navy (#03244d) with refined gold accents on white and ice backgrounds.

## Package Contents
| File | Purpose |
|---|---|
| index.html | Full site (hero, services, about, pledge, promotion, stats, team, interactive map, careers, quote form, footer) |
| 404.html | Branded not-found page (GitHub Pages picks this up automatically) |
| sitemap.xml | Search engine sitemap |
| robots.txt | Crawler rules plus sitemap pointer |
| site.webmanifest | PWA / install metadata |
| favicon.ico plus assets/favicon-16/32.png, apple-touch-icon.png, icon-192/512.png | Full favicon set generated from the brand mark |
| assets/icon-brand.png, icon-white.png, logo-white.png | Brand mark variants extracted from the supplied logo |
| assets/hs-group-navy.png, hs-group-white.png | H&S Group lockup, trimmed and prepared for light and dark backgrounds |

## Logo
The header and footer logos are rebuilt as the brand chevron mark (embedded inline as base64, so it can never 404) paired with live "BLUESKY BM / Building Maintenance" text. This renders crisp at any size and works on both light and cobalt surfaces.

## Key Features
- Editorial split hero: staggered two-line statement headline with word-rise animation, arched signature image, rotating "Free Quote, 24/7 Service" badge and a floating satisfaction card
- Service imagery: every service card now shows the actual work or equipment (stone polishing machine, floor grinder, carpet extraction, pressure washer, squeegee work, room attendant), pulled from the client's own photo library
- H&S Group attribution: "A proud member of the H&S Group of Companies" appears in the top bar, hero eyebrow, about copy and footer. "H&S Group" is styled in gold and hyperlinked to the H&S Group website, and the H&S Group logo sits in the footer
- Interactive locations map: light Leaflet map with pulsing cobalt markers for all 5 offices; clicking an office card flies the map to it
- Advanced team section: portrait cards with hover bio reveals and gold framing
- Promotion section: animated rotating gold ring around the new client offer (free on-site assessment plus 10% off first 90 days; edit copy as needed)
- Lead capture everywhere: sticky nav CTA, floating Free Quote pill, per-service quote links that pre-select the service in the form
- SEO: full meta/OG/Twitter tags, JSON-LD ProfessionalService schema with all 5 locations and the service catalog, semantic headings, descriptive alt text
- Animated stat counters, scroll progress bar, marquee ribbon, scroll reveals, reduced-motion support, fully responsive (mobile / laptop / desktop)

## Forms to info@blueskybm.com
The quote form posts via FormSubmit to info@blueskybm.com.
One-time activation: the first submission triggers a confirmation email to info@blueskybm.com. Click the link in it once and all future submissions deliver normally.
Optional: add a hidden field _next with value https://www.blueskybm.com/#quote once the final domain is live to redirect after submit.

## Deploy to GitHub Pages
1. Create a repo (for example blueskybm) and upload all files to the root.
2. Settings, Pages, Deploy from branch, main / root.
3. For the custom domain, add www.blueskybm.com in Pages settings (creates a CNAME file) and point DNS accordingly.

## Brand colour
Primary navy: #03244d. Accents: gold #B8923F, deep gold #9A7728, light gold #D9BC7A. Ink text #13163A on white / ice (#F2F5FE) backgrounds.

## H&S Group link
All H&S Group links currently point to https://www.hsholdings.ca/ (the live site at time of build). When the H&S Group domain goes live, find-and-replace that URL across index.html and 404.html.

## Notes
- Team photography is the only imagery linked from the current Wix media library (the actual leadership portraits). All service and atmosphere photography is Unsplash (license-free); swap any image by replacing its URL.
- Map office pins use approximate street-level coordinates; fine-tune data-lat / data-lng on the location cards if needed.
