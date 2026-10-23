# KBFG Starters Program | Tenity Lab Crawl — Online Brochure

Light, Tenity-branded one-page brochure introducing the seven Korean startups at the KBFG Starters Program | Tenity Lab Crawl (16 November 2026, Singapore). English by default, with a Korean toggle.

## Files
- `index.html` — the whole page (layout, styles and content)
- `assets/poster.jpg` — event poster (used as the link-preview image)
- `assets/skyline.jpg` — skyline crop from the poster, used behind the hero
- `assets/logos/` — startup logos

## Editing content
All startup text lives in the `STARTUPS` list inside the `<script>` near the bottom of `index.html` (name, logo, website, funding stage, sector, tagline, description, tags — each in `en` and `ko`). Set `stage: null` to hide a funding-stage badge. Page-level text (hero, countdown, stats, intro, labels) is in the `T` object right below it. The countdown targets 16 Nov 2026 13:00 SGT (`START` / `END` in the script).

## Design
Tenity brand colours sampled from tenity.com: pink `#EB5064`, black, white, green `#71DA96`, blue `#98B7F1` / `#5686E9`. Display font is Inter Tight as a stand-in until the official Tenity font is confirmed. The earlier dark version is in the git history (commit `5b8dd50`).

## Interactions
- Hero: headline (with Tenity's inline pill) switches (with a decode effect) when the language button is pressed, ICN → SIN route animation, live countdown (switches to "Live now" during the event), add-to-calendar and copy-link buttons.
- Sector marquee, count-up stats, lineup list that jumps to each card.
- Startup deck: swipe / arrow buttons / ← → keys / pager. Each startup has its own colour (`c`, `c2` in `STARTUPS`) and an illustrative canvas animation (`viz`: radar, face, graph, chart, globe, cctv, qr). Funding ladder uses `rung` (0 Pre-A, 1 Series A, 2 Series B, 3 Pre-IPO).
- ★ Save: visitors can shortlist startups; the list is kept on their own device only and can be copied as text.
- All motion is turned off for visitors with "reduce motion" enabled.

## Open items
- Logos: taken from each company's official materials and upscaled with an AI tool; compare against the originals before publishing.
- Venue spelling "OGBC, Plus, Singapore": confirm.
- Korean translation: needs review.
