# Applied Visual Design Project

Fifteen original, editable vector designs created as practical exercises based on
`Applied_Visual_Design_Practical_File.pdf` (Practicals P01–P15).

## What was delivered

| Folder | Contents |
|--------|----------|
| `SVG_Source/` | 15 editable SVG source files (P01–P15) plus 4 P15 sub-assets (logo, business card, menu, social post). All text is live `<text>`; colour fills are swatch-referenced. |
| `PNG_Previews/` | 2× screenshot previews of every design. P09 and P15 social are also saved at 1080×1080 px. |
| `Final_PDF/Individual_PDF/` | One standalone PDF per design (P01–P15), fonts embedded, exact page sizes. |
| `Final_PDF/CMYK_Print/` | True CMYK PDF exports for the two print practicals: P08 (A4, 3 mm bleed) and P12 (A3, 3 mm bleed). Produced with Ghostscript 10.08 (`/DeviceCMYK`, prepress). |
| `Final_PDF/Sub_Assets/` | PDFs of the four P15 sub-assets: logo, business card, menu, social post. |
| `Final_PDF/Applied_Visual_Design_15_Practicals.pdf` | Combined 15-page PDF in design order, with bookmarks (TOC) and embedded fonts. |
| `Fonts/` | Static-instance TTF fonts bundled with the project. SVGs reference them with relative `@font-face` URLs (`../Fonts/…`). |
| `Illustrator_Source/` | Empty. No native `.ai` files. See below. |

## Design specifications honoured

- **P08 Print Layout**: A4 (210 × 297 mm), 3 mm bleed → 216 × 303 mm SVG/PDF artboard, CMYK-spec colours, crop marks, 3-column grid, trim line.
- **P09 Digital Post**: 1080 × 1080 px, RGB, 8 px spacing system, 64 px margins.
- **P12 Save Water Poster**: A3 (297 × 420 mm), 3 mm bleed → 303 × 426 mm artboard, CMYK-spec colours, bleed, crop marks, large water-drop focal point.
- **P15 Brand Identity**: Fictional café "BREW & BLOOM" — original cup-and-sprout mark, navy/orange/sand/cream palette, Fraunces + Inter typography, core identity board, business cards, menu, takeaway cup application, typography and colour boards, plus social post.

## Fonts

Fonts are static instances bundled under `Fonts/`. SVGs use relative `@font-face` URLs, so the files remain editable in Illustrator / any SVG editor **provided the `Fonts/` folder is copied alongside** and installed on that machine for exact appearance. Fonts used: Inter, Space Grotesk, Fraunces, Bebas Neue, IBM Plex Mono, Bitter, Caveat, DM Serif Display, Archivo Black.

## Honest delivery notes / environment limitations

1. **No native `.ai` files.** Adobe Illustrator is not installed in this environment, so no genuine `.ai` source exists. `Illustrator_Source/` is intentionally empty. The editable source format provided is SVG. Do not rename an SVG or PDF to `.ai` — that would not be a native Illustrator file.

2. **CMYK.** Actual CMYK conversion was only possible for P08 and P12 via Ghostscript 10.08 (`/DeviceCMYK`). Ghostscript was installed from the official Artifex build (`gs10080w64.exe`) into `C:\Users\OM\AppData\Local\Temp\opencode\gs_install\gs\bin\gswin64c.exe`. Verified with `gs -o - -sDEVICE=inkcov` that both files emit DeviceCMYK ink values. All other PDFs remain in the RGB/sRGB workspace they were authored in (the designs are screen/print hybrids); converting them would change the intended screen appearance.

3. **Playwright / Chrome rendering.** PNG previews are Chrome screenshots at device scale factor 2. Fonts render from the bundled `Fonts/` folder via relative `@font-face` URLs during rendering.

4. **Theory/written answers.** Out of scope. The user's friend will write the written/theory answers for each practical.

5. **Originality.** All 15 compositions are original vector artwork inspired by the PDF references — not raster screenshots, not page reproductions. No Illustrator-native features (live paint, symbols, etc.) are used because there is no `.ai` master.

## File naming convention

- `P01_Elements_of_Design` … `P14_Concept_to_Final.svg`
- `P15_Brand_Identity.svg` (master board), `P15_Logo.svg`, `P15_Business_Card.svg`, `P15_Menu.svg`, `P15_Social_Post.svg`
- PNG previews share the same stem with `.png`.
- Individual PDFs share the same stem with `.pdf` in `Final_PDF/Individual_PDF/`.
- CMYK prints: `P08_Print_Layout_CMYK.pdf`, `P12_Save_Water_Poster_CMYK.pdf` in `Final_PDF/CMYK_Print/`.

## How to use

- Open any `*.svg` in Illustrator, Inkscape, Figma, or a browser to edit text, colours, and shapes.
- Install the project fonts from `Fonts/` for exact type appearance.
- Print P08 / P12 from the `CMYK_Print/` files (true DeviceCMYK, 3 mm bleed, crop marks).
- Use `Applied_Visual_Design_15_Practicals.pdf` for a single combined deliverable in order P01–P15.
