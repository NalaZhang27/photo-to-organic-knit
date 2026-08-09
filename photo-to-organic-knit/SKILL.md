---
name: photo-to-organic-knit
description: Reimagine a user-provided photograph as a concept-driven knitted-wool art poster rather than a literal textile filter. Select only defining source elements, discard or abstract secondary detail, invent a new graphic composition, preserve source orientation, and add an optional or inferred 2–4 word single-yarn title. Use for photo-to-knit, plush yarn, crochet landscape, editorial poster, children's picture-book textile art, magazine-cover artwork, or brand-visual conversions from JPG, JPEG, PNG, or other raster images.
---

# Photo to Organic Knit

Convert one source photograph into a new raster art poster using ImageGen. Treat `assets/style-reference.png` as a quality and art-direction reference, never as subject matter to copy. Create a genuine second interpretation: retain recognition, but redesign hierarchy, shapes, spacing, scale, and visual metaphor.

## Workflow

1. Inspect the source image before generating. Identify its orientation, aspect ratio, main subject, defining silhouette, motion, emotional theme, and two to five indispensable visual elements.
2. Separate elements into three groups:
   - **retain**: essential for recognition;
   - **transform**: useful but should become symbols, textile blocks, ribbons, gaps, or exaggerated forms;
   - **discard**: realistic background detail that weakens the poster concept.
3. Read `references/style-spec.md`. Choose one primary concept and one or two design devices that fit the source; do not mechanically use every device.
4. Write a one-sentence art direction before prompting, such as “turn the raised hands and canyon gap into a symbolic gate.” If the direction merely restates the photo, strengthen it.
5. Use the built-in ImageGen editing flow. Supply the source as the subject reference and `assets/style-reference.png` as the tactile quality reference. Explicitly state that neither image's literal composition should be copied.
6. Preserve source orientation:
   - landscape source -> landscape output;
   - portrait source -> portrait output;
   - square source -> square output unless the user requests otherwise.
7. Recompose rather than trace. Change at least three of these from the photograph: hierarchy, scale, spacing, silhouette, viewpoint, continuity, layering, negative space, or visual path. Preserve subject identity without preserving photographic staging.
8. Keep the complete textile emblem around 55–60% of the canvas width and 50–55% of its height. Leave generous warm-ivory negative space on all sides. Use separated textile islands or irregular gaps when they strengthen the concept.
9. Add restrained handmade irregularities: uneven stitch tension, a few loose ends, wispy fibers, subtle pulled loops, mismatched boundaries, and one or two outward-protruding yarn ridges. Avoid both machine-perfect symmetry and exaggerated damage.
10. Include a 2–4 word thematic yarn title by default unless the user asks for no text. Use exact wording when provided; otherwise infer a short evocative title from the image's theme. Verify both word count and spelling.
11. Inspect the result for conceptual transformation, orientation, subject recognition, hierarchy, negative space, organic edges, material realism, title accuracy, and absence of copied reference content. Reject results that read as the original photo with a wool filter.
12. Iterate on one failure at a time, then save project-bound outputs non-destructively with a versioned filename and report the final path.

## Invariants

- Preserve the input image's orientation by default.
- Preserve only the subject's defining silhouette, relationships, and key elements; freely redesign everything secondary.
- Produce an art poster or brand-mark composition, not a knitted replica of the photograph.
- Establish a clear concept, focal hierarchy, and visual path before adding surface detail.
- Make every visible scene element tactile: knit, crochet, boucle, felt, mohair, braided yarn, or embroidery only where structurally appropriate.
- Maintain editorial restraint and a small collectible-art-object composition.
- Prefer analog craft irregularity over polished 3D-render perfection.
- Never reproduce the reference asset's train, bridge, hills, palette, or caption unless they exist in the new source.
- Avoid literal photographic staging, continuous realistic backgrounds, watermarks, signatures, unrelated objects, extra text, plastic/clay surfaces, clean vector edges, and edge-to-edge coverage.

## Yarn Lettering

Use a thin single strand of yarn arranged as relaxed, childlike handwriting. Favor mixed-case letters, modest baseline variation, open counters, controlled loops, and immediate readability. Let the strand flow naturally between some letters or words and finish with a short loose tail.

Avoid rigid block capitals, typeset geometry, thick braids, filled letters, embroidery, ornate calligraphy, ambiguous loops, and excessive cursive. Lock spelling character by character in the prompt and verify it visually.

## Prompt Construction

Build a concise production prompt with:

- source role and style-reference role;
- orientation and approximate aspect ratio;
- retain / transform / discard decisions;
- one-sentence concept and selected design devices;
- defining subject elements to preserve and photographic staging to avoid;
- vignette scale and negative-space target;
- material and handmade-imperfection requirements;
- irregular-edge requirements;
- exact or inferred 2–4 word title and lettering constraints;
- explicit avoid list.

Do not add arbitrary characters, slogans, brands, or narrative objects.
