# Organic knit style specification

## Visual character

- A concept-driven art poster or brand visual with the warmth of a children's picture book.
- A real tabletop fiber artwork photographed in soft daylight, not a glossy synthetic 3D render.
- Layered crochet, chunky knit, boucle, needle-felt, soft mohair fuzz, braided cords, and visible stitch construction.
- Warm ivory handmade felt or paper backdrop with subtle surface variation.
- Visible design intelligence: selection, omission, exaggeration, abstraction, rhythm, hierarchy, and a memorable silhouette.

## Creative transformation

- Treat the photograph as raw material, not a layout template.
- Retain two to five recognition anchors. Delete or abstract secondary scenery, texture, and perspective detail.
- Form one concise visual idea from the source: a gate, embrace, ascent, orbit, shelter, crossing, echo, current, or another image-specific metaphor.
- Change at least three structural qualities from the source: hierarchy, scale, spacing, silhouette, viewpoint, continuity, layering, negative space, or visual path.
- Prefer a new emblematic arrangement over a one-to-one knitted reconstruction.
- Use detail selectively around the focal idea; let broad simplified textile shapes carry the rest.

Choose one primary device and at most two supporting devices:

- **Negative-space symbol:** make an important gap form a gate, keyhole, sun, path, face, or other source-derived symbol.
- **Asymmetric monuments:** exaggerate paired or repeated subjects into unequal visual pillars with deliberate tension.
- **Textile islands:** break continuous scenery into five to nine separated knitted patches with visible backdrop between them.
- **Path or ribbon:** turn water, roads, smoke, light, or movement into sweeping yarn lines that guide the eye.
- **Scale contrast:** enlarge one meaningful feature and reduce secondary figures or objects to stitches, beads, or icons.
- **Layered collage:** overlap simplified felt and crochet silhouettes like cut-paper editorial art rather than rebuilding realistic depth.

Do not apply a device when it is unrelated to the source. Do not combine so many devices that the poster loses one clear idea.

## Composition

- Follow the source image's orientation.
- Compress the scene into an iconic textile vignette occupying roughly 55–60% of canvas width and 50–55% of height.
- Leave generous negative space on all sides for editorial or brand use.
- Use asymmetry and off-center visual rhythm while keeping the subject readable at thumbnail size.
- Keep all elements inside the frame; never crop the vignette merely to create drama.
- Avoid recreating the source's complete continuous background. Use omission, gaps, separated patches, and altered scale to signal deliberate authorship.

## Handmade irregularity

- Vary stitch tension and loop size slightly.
- Use a few loose yarn ends, wispy fibers, small pulled loops, and relaxed or subtly dropped stitches.
- Give the textile base an uneven organic silhouette: a small protruding patch, a lifted ridge, a receding notch, or a loose loop outside the main boundary.
- Keep imperfections sparse and believable. The work is handmade, not torn or distressed.
- Avoid repeated procedural motifs, perfect arches, radial symmetry, smooth oval bases, uniform scallops, or machine-cut borders.

## Yarn title

- Include a thematic title by default unless the user requests no text.
- Keep the title between two and four words. Use the user's exact wording when supplied; otherwise infer an evocative phrase from the selected concept.
- Form the exact phrase from one thin yarn strand.
- Use friendly, relaxed mixed-case handwriting that is clearer than ornate cursive.
- Allow mild baseline drift, varied character size, a few natural joins, and a loose finishing tail.
- Keep counters open and ambiguous letters separated.
- Do not use block type, filled yarn letters, thick braid, embroidery, conventional fonts, or highly calligraphic loops.

## Prompt skeleton

```text
Use case: style-transfer
Asset type: editorial textile illustration / adaptable brand visual
Input images: Image 1 is the subject and composition source. Image 2 is a style-quality reference only; do not copy its subject or caption.
Orientation: preserve Image 1's [landscape/portrait/square] orientation and approximate aspect ratio.
Retain: [two to five recognition anchors].
Transform: [elements to turn into symbols, textile islands, ribbons, exaggerated forms, or negative space].
Discard: [secondary photographic detail and continuous background information].
Concept: [one-sentence visual metaphor and focal hierarchy].
Design devices: [one primary device; optionally one or two supporting devices].
Recomposition: change at least three of hierarchy, scale, spacing, silhouette, viewpoint, continuity, layering, negative space, or visual path. Do not trace Image 1's staging.
Composition: complete vignette at 55–60% canvas width and 50–55% height; generous warm-ivory negative space; no cropping.
Materials: crochet, chunky knit, boucle, felt, mohair fuzz, visible stitches and braided cords.
Imperfection: restrained loose ends, wispy fibers, varied tension, pulled loops, and an asymmetric irregular textile edge.
Text (verbatim): "[exact or inferred 2–4 word title]" [omit only when the user requests no text].
Typography: one thin yarn strand, relaxed clear childlike mixed-case handwriting, natural joins, open counters, short loose tail.
Avoid: literal photo reconstruction, wool-filter appearance, copied style-reference subjects, continuous realistic background, edge-to-edge coverage, machine-perfect symmetry, plastic/clay render, smooth oval base, excessive damage, illegible cursive, extra text, watermark, signature.
```
