---
name: photo-to-organic-knit
description: Transform a user-provided photograph into a spacious, handcrafted knitted-wool illustration with organic loose fibers, irregular textile edges, preserved source orientation, and optional single-strand yarn lettering. Use for photo-to-knit, plush yarn, crochet landscape, wool editorial illustration, children's picture-book textile art, magazine-cover artwork, or brand-visual conversions from JPG, JPEG, PNG, or other raster images.
---

# Photo to Organic Knit

Convert one source photograph into a new raster illustration using ImageGen. Treat `assets/style-reference.png` as a quality and art-direction reference, never as subject matter to copy.

## Workflow

1. Inspect the source image before generating. Identify its orientation, aspect ratio, main subject, defining silhouette, depth layers, motion, and two to five indispensable visual elements.
2. Read `references/style-spec.md` before shaping the generation prompt.
3. Use the built-in ImageGen editing flow. Supply the source as the subject/composition reference and `assets/style-reference.png` as the style reference.
4. Preserve source orientation:
   - landscape source -> landscape output;
   - portrait source -> portrait output;
   - square source -> square output unless the user requests otherwise.
5. Reinterpret rather than trace. Preserve recognizable subject relationships while simplifying secondary detail into knitted patches and tactile forms.
6. Keep the complete textile vignette around 55–60% of the canvas width and 50–55% of its height. Leave generous warm-ivory negative space on all sides. Do not crop the textile scene.
7. Add restrained handmade irregularities: uneven stitch tension, a few loose ends, wispy fibers, subtle pulled loops, slightly uneven boundaries, and one or two outward-protruding yarn ridges. Avoid both machine-perfect symmetry and exaggerated damage.
8. Include a yarn title only when the user requests text or when a short title is clearly part of the requested design. Ask for the exact wording if it cannot be inferred safely.
9. Inspect the generated result for orientation, subject recognition, scale, negative space, organic edges, material realism, and exact text. Iterate on one failure at a time.
10. Save project-bound outputs non-destructively with a versioned filename and report the final path.

## Invariants

- Preserve the input image's orientation by default.
- Preserve the subject's defining silhouette and key elements.
- Make every visible scene element tactile: knit, crochet, boucle, felt, mohair, braided yarn, or embroidery only where structurally appropriate.
- Maintain editorial restraint and a small collectible-art-object composition.
- Prefer analog craft irregularity over polished 3D-render perfection.
- Never reproduce the reference asset's train, bridge, hills, palette, or caption unless they exist in the new source.
- Avoid watermarks, signatures, unrelated objects, extra text, plastic/clay surfaces, clean vector edges, and edge-to-edge coverage.

## Yarn Lettering

Use a thin single strand of yarn arranged as relaxed, childlike handwriting. Favor mixed-case letters, modest baseline variation, open counters, controlled loops, and immediate readability. Let the strand flow naturally between some letters or words and finish with a short loose tail.

Avoid rigid block capitals, typeset geometry, thick braids, filled letters, embroidery, ornate calligraphy, ambiguous loops, and excessive cursive. Lock spelling character by character in the prompt and verify it visually.

## Prompt Construction

Build a concise production prompt with:

- source role and style-reference role;
- orientation and approximate aspect ratio;
- defining subject elements to preserve;
- vignette scale and negative-space target;
- material and handmade-imperfection requirements;
- irregular-edge requirements;
- exact optional text and lettering constraints;
- explicit avoid list.

Do not add arbitrary characters, slogans, brands, or narrative objects.
