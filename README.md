# KBFG Starters Program | Tenity Lab Crawl — Online Brochure

One-page brochure introducing the seven Korean startups at the KBFG Starters Program | Tenity Lab Crawl (16 November 2026, Singapore). English by default, with a Korean toggle.

## Files
- `index.html` — the whole page (layout, styles and content)
- `assets/poster.jpg` — event poster (used as the link-preview image)
- `assets/skyline.jpg` — skyline crop from the poster, used behind the hero
- `assets/logos/` — startup logos

## Editing content
All startup text lives in the `STARTUPS` list inside the `<script>` near the bottom of `index.html` (name, logo, website, funding stage, sector, tagline, description, tags — each in `en` and `ko`). Set `stage: null` to hide a funding-stage badge. Page-level text (hero, countdown, stats, intro, labels) is in the `T` object right below it. The countdown targets 16 Nov 2026 13:00 SGT (`START` / `END` in the script).

## Interactions
Hero headline decodes between English and Korean, ICN → SIN route animation, live countdown (switches to "Live now" during the event), sector marquee, count-up stats, swipeable startup deck (swipe, arrow buttons, ← → keys, pager), chapter label + progress bar in the top bar. All motion is turned off for visitors with "reduce motion" enabled.

## Open items
- Logos: taken from each company's official materials and upscaled with an AI tool; compare against the originals before publishing.
- Venue spelling "OGBC, Plus, Singapore": confirm.
- Korean translation: needs review.
