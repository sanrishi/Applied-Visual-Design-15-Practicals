# Design Process — Applied Visual Design 15 Practicals

Documentation of the design principles, decisions and specifications behind each practical composition.

## General Approach

All 15 compositions are **original vector artwork** inspired by the reference PDF (`Applied_Visual_Design_Practical_File.pdf`). They are not raster screenshots or page reproductions. Each practical was authored as code-driven SVG using a shared design helper library (`_build/design_lib.py`), then rendered to PNG via Chrome screenshots and exported to PDF via Chrome print-to-PDF.

## Per-Practical Objectives & Decisions

### P01 — Elements of Design
**Objective:** Compose a single image demonstrating five visual forces: line, shape, form, texture, space.  
**Decision:** Central orange sphere (form/light) over teal plane (shape/plane) within a dark circular field, with radiating lines (line) and a dotted texture inset (texture). Negative space around the sphere creates breath.

### P02 — Asymmetrical Balance
**Objective:** Balance visual weight through asymmetry, not symmetry.  
**Decision:** A heavy dark navy crescent on the left is held in tension by a constellation of lighter forms (circles, square, ring) on the right, organised around a central axis.

### P03 — Contrast & Focal Point
**Objective:** Establish one clear focal point using contrast.  
**Decision:** A large warm orange sphere placed near the rule-of-thirds intersection against a cool dark background, with concentric guide rings and crosshairs marking the focal point.

### P04 — Rhythm & Repetition
**Objective:** Create a visual pulse along a curved path.  
**Decision:** Overlapping circles of varying size and colour placed along a cubic Bézier curve, with repetition creating flow and variation in scale/colour preventing monotony.

### P05 — Visual Hierarchy
**Objective:** Demonstrate three levels of typographic hierarchy.  
**Decision:** "MAKE IT CLEAR." at three sizes/weights/colours (primary 150px Fraunces, secondary 72px Inter Bold, tertiary 28px IBM Plex Mono), each annotated with its specification.

### P06 — 12-Column Grid Layout
**Objective:** Apply a grid system with alignment and spacing.  
**Decision:** 12 columns, 15mm margins, 8pt gutters (computed from physical units). Content snapped to columns: 6-column image block, 3-column text blocks, 4-column modules.

### P07 — Z-Pattern Layout
**Objective:** Guide the eye using the Z-pattern reading path.  
**Decision:** Logo (top-left) → headline (top-right) → hero image → CTA (bottom-right), with numbered markers 01–04 tracing the Z.

### P08 — Print Layout (A4)
**Objective:** Produce a print-ready A4 layout with bleed and crop marks.  
**Decision:** 216 × 303 mm artboard (A4 + 3mm bleed), trim line, crop marks at corners, 3-column grid, CTA panel. True CMYK export generated via Ghostscript.

### P09 — Digital Post (1080 × 1080)
**Objective:** Design for a square digital canvas with an 8px spacing system.  
**Decision:** 64px margins, 8px increment spacing scale shown as a visual key, bold headline, spherical focal element, soft shadow.

### P10 — Typography Study
**Objective:** Compare six typeface classifications using the same two letters ("Aa").  
**Decision:** Six cards — serif, sans-serif, slab serif, script, display, monospace — each showing classification, description, sample and a subtle watermark letter.

### P11 — Expressive Typography
**Objective:** Explore how type + colour convey emotion.  
**Decision:** The word "ENERGY" set in rotated, gradient-filled Archivo Black letters against a dark background with radial rays and halftone dots.

### P12 — Save Water Poster (A3)
**Objective:** Create an A3 awareness poster with bleed and crop marks.  
**Decision:** Large water-drop focal point with ripple rings, cool blue palette, "SAFE WATER IS A RIGHT. PROTECT EVERY DROP." message, true CMYK export via Ghostscript.

### P13 — Visual Narrative
**Objective:** Tell a four-part growth story in one continuous horizon.  
**Decision:** Four panels (seed, sprout, plant, tree) with consistent soil horizon, sun position progression, and a bottom caption band to avoid clipping roots.

### P14 — Concept to Refined Final
**Objective:** Show design process from research to refinement.  
**Decision:** Three left cards (research/moodboard, thumbnail sketch, digital draft) arrowing to a refined final nature poster on the right, with palette swatches and process notes.

### P15 — Brew & Bloom Brand Identity
**Objective:** Present a complete fictional brand identity from concept to application.  
**Decision:** Original cup-and-sprout mark, navy/orange/sand/cream palette, Fraunces + Inter typography, core identity board, business cards (front/back), A5 menu, takeaway cup application, typography and colour boards, social post.

## Export & File Specifications

- All SVGs use relative `@font-face` URLs pointing to `../Fonts/`.
- Fonts are static TTF instances bundled in the repo.
- Combined PDF preserves exact physical page sizes (mm where specified).
- CMYK conversion verified with Ghostscript `inkcov` (DeviceCMYK output confirmed).

## Honest Limitations

- No native `.ai` master exists (Illustrator not installed). SVGs are the editable source.
- CMYK applied only to P08 and P12; other PDFs remain sRGB.
- Written theory answers are handled separately.
