# Trinax website prototype — handoff

Design prototypes for the new trinax.sg, by Our Little Company (OLC).
14 static HTML pages, self-contained (no build step, no dependencies beyond Google Fonts CDN). Open index.html to start.

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
| career.html | Career (8 sections per client brief, not an open-roles page) | v1, media placeholders |
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

7 system child pages (or phase-1 anchor fallback on systems.html), remaining 4 featured case studies.

## Career page — pending from Trinax

Per the client brief (Google Doc, "CAREER PAGE"). career.html carries a temporary production banner listing these; remove it before launch.

- Hero showreel: YouTube links (Joel — deferred until Career content/visuals are done)
- How We Think + What Good Looks Like: photography and descriptions, incl. Vince's staged shots (Siewhua, Google Slide — progress 4 Sep, completion 18 Sep 2026)
- Faces of Trinax: 6+ interviews, new filming (Irfan — format, participants, questions, edits; completion 16 Oct 2026)
- A Project in the Life: documentary-style project follow, new filming (completion 16 Oct 2026)
- How We Celebrate: curation of existing footage/photos + ongoing capture (Irfan)
- It May Not Be For You If: v1 video ready 27 Aug 2026, link it in place of the placeholder
- Real project examples for each of the eight behaviours

### Career copy — deliberate exceptions

- "Different Minds. Bold Ideas. Real Impact." (This is Trinax h2) is client-specified. Title case and "impact" both depart from the guidelines' sentence-case rule and abstract-noun avoid list. Leave as written; do not normalise.

### Career copy — claims to validate with Trinax

Sourced from the brand narrative where possible. These four describe internal process and are not in the brief or the narrative — confirm or replace before launch:

- "Projects here are expected to spend real time in the first diamond." (how-we-think, Double Diamond)
- "These are the behaviours that come up in reviews and in promotion decisions." (what-good-looks-like lede)
- "Reviews examine decisions rather than individuals." (accountability behaviour)
