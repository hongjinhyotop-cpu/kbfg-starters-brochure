# KBFG Starters Program | Tenity Lab Crawl — Online Brochure

One-page brochure introducing the seven Korean startups at the KBFG Starters Program | Tenity Lab Crawl (16 November 2026, Singapore). English by default, with a Korean toggle.

## Files
- `index.html` — the whole page (layout, styles and content)
- `assets/poster.jpg` — event poster used as the top banner
- `assets/logos/` — startup logos

## Editing content
All startup text lives in the `STARTUPS` list inside the `<script>` near the bottom of `index.html` (name, logo, website, funding stage, sector, tagline, description, tags — each in `en` and `ko`). Set `stage: null` to hide a funding-stage badge. Page-level text (intro, date, labels) is in the `TEXT` object right below it.

## Open items
- Logos: taken from each company's official materials and upscaled with an AI tool; compare against the originals before publishing.
- Venue spelling "OGBC, Plus, Singapore": confirm.
- Korean translation: needs review.
