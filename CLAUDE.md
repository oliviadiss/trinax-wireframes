# Trinax website prototype — handoff

Design prototypes for the new trinax.sg, by Our Little Company (OLC).
13 static HTML pages, self-contained (no build step, no dependencies beyond Google Fonts CDN). Open index.html to start.

## Pages

| File | Page | Status |
|---|---|---|
| index.html | Home | v4, client-reviewed |
| what-we-do.html | What We Do (orientation) | v1 |
| end-to-end.html | End-to-End Projects | v1 |
| systems.html | Deployment-Ready Systems | v1 (implies 7 system child pages, not built) |
| work.html | Work (featured slider + filterable index) | v1 |
| case-study-dreamlab.html | Featured case study template (URA Dream Lab) | v1, separate template from projects |
| project-changi.html | Standard project template (Changi Peanuts) | v1, top banner explains the template |
| about.html | About (merged company + approach) | v1 |
| contact.html | Contact | v1 |
| insights.html | Insights landing | v1 |
| article.html | Article template (real Trinax article as sample) | v1 |
| whitepaper.html | White paper download (Swarm Intelligence) | v1, placeholders |
| creative-lab.html | Creative Lab (experiments) | v1, placeholders |

## Design system ("Instrument grade")

- Dark base: --bg #161614, --panel #1D1D1B, hairlines #2B2B28. Inverted light sections (#E9E7E1) are contrast moments (About certifications, case-study outcome).
- Brand red #E4262F: logo and rare accents only. Never decorative in content. Founder quote border on About is the one editorial use.
- Fonts: Archivo (display), Inter (body), JetBrains Mono (all facts, metadata, labels).
- Container 1512px, 64px gutters. Mono labels: .72rem, letter-spacing .14em, uppercase.
- Nav: dropdowns on What We Do and Work; About and Career flat items; Contact pill. Shared footer with certifications column.
- Copy rules: facts displayed as data, no generic self-praise, no rhetorical-question headings. British English.

## Known technical gaps (priority order)

1. Favicon, OG/meta tags, 404 page, form validation states.
2. Mobile burger menu is implemented (vanilla JS toggle, full-screen panel under 900px) — review UX and refine.
3. Separator convention: " · " in all mono meta labels (em dashes removed site-wide, kept only in browser titles).
4. Sliders (work featured 01/05, about team 01/02, awards 01/03) are chrome only, not functional.
5. Bio overlay (about.html) and filters (work.html, insights.html) are functional vanilla JS.

## Pending content from Trinax

- Leadership: 5 names/roles/bios/portraits (about.html)
- 8 team videos (about.html), 4 more featured case studies (PDF copy exists for CMPB/NKF/ICA/Pepper Lunch/NMS)
- Projects spreadsheet (100+ rows: title, client, industry, type/system, year, metric, visuals)
- HELIX proof point, system deployment timings, FAQ validation (systems.html)
- Dream Lab metrics marked WIP in the MEA deck; 14 locations to harmonise site-wide (some pages still say 10+)
- White paper abstract, page count, author; Creative Lab: 4-6 real experiments with live URLs
- Awards list for sliders; international facts; logo usage permissions

## Not yet built

Career page, 7 system child pages (or phase-1 anchor fallback on systems.html), remaining 4 featured case studies.
