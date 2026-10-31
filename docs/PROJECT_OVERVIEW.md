# Project Overview — Applied Visual Design: 15 Practicals

A curated portfolio of **15 original, editable vector design compositions** created as applied visual design practical exercises. Each piece demonstrates a specific design principle — from elements of design and colour theory to grid systems, print layout, typography, visual narrative and complete brand identity.

## What This Repository Contains

| Category | Count | Location |
|----------|-------|----------|
| Editable SVG sources | 19 | `SVG_Source/` |
| Individual PDFs | 15 | `Final_PDF/Individual_PDF/` |
| Combined 15-page PDF | 1 | `Final_PDF/Applied_Visual_Design_15_Practicals.pdf` |
| CMYK print PDFs | 2 | `Final_PDF/CMYK_Print/` |
| PNG previews | 21 | `PNG_Previews/` |
| Brand sub-asset PDFs | 4 | `Final_PDF/Sub_Assets/` |
| Font files | 20 | `Fonts/` |
| Documentation | — | `docs/` |

## The 15 Practicals

| No. | Title | Focus | Artboard |
|-----|-------|-------|----------|
| P01 | Elements of Design | Line, shape, form, texture, space | 1440 × 960 px |
| P02 | Asymmetrical Balance | Proportion & visual weight | 1440 × 960 px |
| P03 | Contrast & Focal Point | Rule of thirds, single focal element | 1440 × 960 px |
| P04 | Rhythm & Repetition | Visual pulse along a curved path | 1440 × 960 px |
| P05 | Visual Hierarchy | Primary / secondary / tertiary type | 1440 × 960 px |
| P06 | Grid Layout | 12-column grid, 15mm margins, 8pt gutters | 1440 × 960 px |
| P07 | Z-Pattern Layout | Eye-flow study for a landing page | 1440 × 960 px |
| P08 | Print Layout | A4, 3mm bleed, crop marks, CMYK | 216 × 303 mm |
| P09 | Digital Post | 8px spacing system, 64px margins | 1080 × 1080 px |
| P10 | Typography Study | Six typeface classifications | 1440 × 960 px |
| P11 | Expressive Typography | Type + colour = emotion | 1440 × 960 px |
| P12 | Save Water Poster | A3, 3mm bleed, water-drop focal | 303 × 426 mm |
| P13 | Visual Narrative | Seed → sprout → plant → tree | 1600 × 900 px |
| P14 | Concept to Final | Research → sketch → draft → final | 1440 × 960 px |
| P15 | Brew & Bloom Brand Identity | Logo, palette, type, cards, menu, social | 1600 × 1000 px |

## Colour System

A warm neutral system used across the portfolio:

| Colour | Hex | Usage |
|--------|-----|-------|
| Navy | `#152238` | Structure, deep backgrounds, primary text |
| Orange | `#EE7F2D` | Energy, accents, CTAs, highlights |
| Sand | `#E7C27A` | Warm mid-tones, secondary elements |
| Cream | `#F7F1E5` | Backgrounds, breathing room, off-white |

## Typography

| Role | Font | Style |
|------|------|-------|
| Display | Fraunces | SemiBold / Bold |
| Display | Space Grotesk | Bold |
| Display | Bebas Neue | Regular |
| Body | Inter | Regular / Medium / SemiBold / Bold |
| Mono | IBM Plex Mono | Regular / Medium / Bold |
| Accent | Bitter | Regular / Bold |
| Script | Caveat | Regular / Bold |

Fonts are bundled in `Fonts/` as static instances. SVGs reference them with relative `@font-face` URLs (`../Fonts/…`). Install the project fonts on your machine for exact type appearance when opening SVGs in Illustrator.

## Export Formats

- **SVG** — Editable vector source (live `<text>`, shapes, gradients, clipping paths). Open in Illustrator, Inkscape, Figma or any SVG editor.
- **PDF** — Font-embedded, exact page sizes. Individual PDFs per practical plus a combined 15-page PDF with bookmarks.
- **PNG** — 2× screenshot previews for quick visual review. P09 and P15 social also saved at native 1080 × 1080 px.
- **CMYK PDF** — True DeviceCMYK conversion (via Ghostscript) for P08 (A4, 3mm bleed) and P12 (A3, 3mm bleed).

## Honest Technical Notes

- **No native `.ai` files.** Adobe Illustrator is not installed in this environment, so no genuine Illustrator document exists. SVGs are the editable source format and open natively in Illustrator. `Illustrator_Source/` contains an explanatory note only.
- **CMYK** was produced only for the two print practicals (P08, P12) via Ghostscript. Other PDFs remain in the sRGB workspace they were authored in.
- **Theory / written answers** are out of scope — those are handled separately.

## Fictional Brand Notice

P15 features **Brew & Bloom**, a fictional neighbourhood coffee house and botanical bakery. All names, contact details, addresses and menu items are placeholder content created for the portfolio.

---

*Generated with OpenCode / Chrome PDF + Ghostscript + PyMuPDF.*
