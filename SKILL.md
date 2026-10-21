---
name: vintage-folk-woodcut
description: Make 4:5 travel posters with an unchanged photograph above and an airy minimal folk woodcut below, limited to eight colors including paper and postmark.
---

# Vintage Folk Woodcut v1.2 | 清新极简复古木刻

## Non-negotiable source fidelity
- The uploaded target photograph is the ONLY source of scene objects, silhouettes and arrangement. Style reference images inform aesthetics ONLY. Never draw objects from reference images into the source scene.
- Keep recognizable primary subject(s), pose, size relationships, and distinctive architecture. Delete secondary clutter; do not add scenery, buildings, mountains, lakes, pagodas, suns, props or figures absent from the source.
- Upper photograph remains the actual input photo, not an AI recreation. Only necessary proportional cropping to the upper panel is allowed. For pixel-level fidelity, composite the original pixels after generating the bottom illustration.

## Geometry | fixed 4:5 50/50 layout
Reference grid: 1200 × 1500 px, scale proportionally.
- Top photo = x 0..1200, y 0..750 (exactly 50% height); no recoloring, re-rendering or texture.
- Lower ivory paper = x 0..1200, y 750..1500 (exactly 50%).
- Bottom printed illustration is a single clean-edged rectangle x 132..1068 (78% canvas width), y 810..1280 (470 px), with perfectly clear horizontal/vertical edges; image content clipped to all four sides. Side margins precisely 11% of whole width each; top paper margin 60 px.
- Center a restrained monochrome postmark at x 600, y approximately 1305..1410, 150–200 px wide, no overlap with illustration and at least 90 px paper under the stamp. Stamp only gives verified Chinese/English location; otherwise generic place mark or request location. Do not guess.
- No extra outline, headline, second panel, collage, watermark or typography other than necessary in-scene lettering and stamp.

## Core art direction | LESS before texture
**Order of artistic priorities for lower half: shape simplification > inner-picture negative space > carved-mark rhythm > minor subject detail.** Top fidelity and fixed layout always precede these.
1. Before rendering any lines, rewrite the scene as approximately **4–7 coherent large silhouettes/color regions**, plus a few essential small motifs. These are guidelines, not a rigid cap if subject legibility needs more. Group trees, tea leaves, windows, people, rocks and skyline fragments into larger masses, not thousands of outlined objects.
2. Preserve only the subject's identifying silhouette and a few compositional anchors. Remove tiny lines, window patterns, loose foliage, tiny clutter. Silhouette recognition at thumbnail scale is a success criterion.
3. Prefer just **foreground / middle ground / background** layers through overlap, relative size, vertical placement and color. Flat elevation/front/side views or very restrained axonometric geometry only. No one-, two- or three-point perspective, photoreal shadows or depth of field.
4. Ensure **quiet paper-white regions INSIDE the printed rectangle** (sky, highlights, shape separations) as well as blank cream margins OUTSIDE it. A large sky can remain near-blank. Do not fill every colored area with patterns or turn the entire sky into thick horizontal bars.
5. Patterns are **carved-out negative-space marks inside large flat color masses**, never extra outlines around every leaf. For tea fields, group hundreds of leaves into 2–5 large green masses with short seed-shaped cuts; preserve workers as simple shapes. For architecture, render main mass and iconic roof/tower silhouette, simplify nearly all windows.

## Palette | eight total colors MAX for lower half
- Preferred **4–6 colors** including paper, ink and postmark; **8 is a ceiling, not a target**. The upper real photograph does not count.
- Palette starts from ivory paper, warm charcoal/deep evergreen, one lighter field color, one muted cool or warm supporting color, one accent, and optional single ink for stamp; the stamp MUST reuse a palette color.
- Example six colors: ivory #F3E6C9, deep pine #304C42, charcoal #2B3330, olive #9DAB6C, muted ochre #CBA257, brick #CB6550. Adjust colors based on the actual scene BEFORE rendering, never add accidental shades/transparent gradients.
- Prefer large solid areas and striking negative-space contrast rather than color diversity. No photographic lighting, gradients, smooth digital shading or fine color dithering.

## Engraving language | simple, readable, restrained
- Every object class can use a distinctive direction, **but only one dominant motif per large region**. Prioritize repetition and rhythm, not texture coverage.
- Water: compact orderly horizontal dashes, consistent spacing, enough untouched flat color.
- Foliage and tree canopies: short leaf-shaped dashes **carved out of one solid group**; do not draw leaf contours.
- Buildings: solid silhouettes; a few purposeful upright slits or interrupted horizontal cuts, never miniature grids of windows.
- Stone, ground: sparse vertical stout gouges; fur and textiles: a limited set of curved/diagonal cuts following form.
- Sky: often plain ivory/one flat color, perhaps a few short horizontal cuts ONLY if needed; sky is vital breathing space.
- Coarse marks must read at thumbnail size but stay proportionate. Former 'mandatory 7–18 px long, 2–5 px thick everywhere' is **not a global quota**; scale by subject. Fewer marks is often better than larger/more marks.
- Slightly uneven hand-cut edges and ink dropout within printed regions, subtle paper tooth. Never add random noise/grunge overlays, micro-hatching, botanical contour outlines, dense decor or full-field texture.

## Postmark
Small centered vintage monocolor postal seal on lower paper BELOW the artwork, accurate known place in English/Chinese. Restrained circle/oval and 3–4 cancellation waves; may include tiny relevant silhouette. Stamp does not invade illustration.

## Quality gate before delivering
- Is source photo actually unchanged, not recreated?
- Is poster 4:5, exactly equal halves, printed rectangle exactly 78% wide with 11% margins?
- Is the scene faithful, without invented mountains, lakes, towers or sunsets?
- At thumbnail scale, do strong simple silhouettes dominate before engraved texture?
- Are there distinct calm blank areas, especially in sky, rather than full-frame linework?
- Does each color region have at most one rhythmic carve motif, and are leaves/windows not individually outlined?
- Are there only 4–6 preferred or at most 8 flat lower-half colors including postmark and paper?
- Is the legible, accurate postmark BELOW the rectangle and centered?

If no: regenerate ONLY the illustrated lower half. Do not change original top photo or reduce outer margins.
