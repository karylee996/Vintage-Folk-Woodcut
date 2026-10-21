---
name: vintage-folk-woodcut
description: Transform a source photograph into a 4:5, 50/50 original-photo plus eight-color vintage folk woodcut travel poster with fixed rectangular margins and location postmark.
---

# Vintage Folk Woodcut | 复古民间木刻旅行海报

## Input and hierarchy
- User-supplied PHOTO is the only source of scene content. Other images are style references, NEVER substitute them as scene input.
- Identify principal subject, secondary structures, actions, object count, geographic relationship, and distinctive shapes. Preserve recognition while simplifying details.
- Use the accurate user-provided location for the stamp. If unknown, omit the specific place name or ask; do not fabricate it.

## Absolutely fixed composition
- Vertical 4:5 output, reference grid **1200×1500**.
- Top panel: `x=0..1200, y=0..750` exactly 50%. The actual source photo must remain photorealistic and unmodified. Crop/scale-to-cover is permitted ONLY to fit 1200×750, with subject-safe cropping; do not regenerate it, recolor it, add a texture, or change existing text. For pixel-accurate preservation, composite the original photo programmatically as a last step.
- Lower panel: `x=0..1200, y=750..1500`, warm matte paper background.
- Printed illustration is **one perfectly bounded rectangular print** at `x=132..1068` (78% canvas width), `y=810..1280` (470 px / 62.7% of lower panel height). Left and right paper margins exactly 132 px; top lower-panel paper margin 60 px. The rectangle must be complete and visually straight on all four sides, no feathering, broken edges bleeding past boundary, gradients, false frame, or decorative outline. Entire scene including ground, mountains, buildings, trees and figures stays inside it.
- Stamp below rectangle, centered around x=600, within `y=1305..1410`, approximately 150–200 px wide. Keep a 25 px or larger gap from artwork. Reserve at least 90 px bottom margin. Do not overlap art or drift to a corner.
- On resize maintain ALL proportions. The lower half paper background and woodcut are distinct regions.

## Style: not a filter
Woodblock/linocut naïve folk-art print, flat elevation or restrained isometric geometry only. NO one-, two-, three-point converging perspective, vanishing points, photoreal lighting, cast shadow, beveling, glossy effects, gradients, watercolors or vector-smooth flat fills.

Compose from large opaque silhouettes, using overlap and vertical placement for depth. Remove distractions and minor details. Avoid introducing extra scenery (sun, buildings, people, hills, boats, etc.) absent from source. Figures are solid and proportionate, minimal/no facial features. Text from the photo need only be kept if visually important and legible.

## Exactly eight printing colors maximum (INCLUDING paper and postmark)
Example single shared eight-ink palette (adapt by mapping the scene's key hues rather than adding tones):
1. warm ivory paper `#F3E3BF`
2. charcoal black `#242B29`
3. deep pine green `#31574E`
4. muted sage `#829470`
5. ochre yellow `#D0A24C`
6. vermilion/coral accent `#CF533D`
7. dusty blue/teal `#567F8A`
8. earthy brown `#9B7258`

These are eight DISTINCT flat colors, not eight base colors plus shades. Paper and postmark count; use one of these colors for the stamp. For pictures dominated by other hues, make a different eight-color palette chosen ONCE before rendering. Never use gradients/transparency/lighting variants to sneak in more hues. Reserve the most saturated ink for a single prominent focal object. Image's photographic TOP is exempt from this eight-color restriction.

## Woodcut marks are structure, not grain overlay
Every major surface gets its OWN bold visible carved pattern, with deliberate uneven spacing and occasional blank paper gaps:
- City buildings: medium/coarse vertical rectangular slits or interrupted grids, not thousands of tiny windows.
- Water: clearly visible repeated horizontal cuts with rhythmic, varying lengths, not photographic shimmer.
- Sky: mostly open blank paper or sparse robust horizontal irregular strokes; avoid all-over texture in sky.
- Trees/foliage: compact repetitive leaf/seed shapes; group foliage into simplified dark masses.
- Ground/stone: stout dashes, grooves, and irregular punctuation marks.
- Animal fur: coarse curved dashes respecting anatomy; fabric: thicker directional hatch marks.
- Distress: subtle ink dropout, registration imperfections, hand-inked dry-brush interruptions *inside print only*. Texture must be discernible at poster thumbnail scale. Prefer fewer, thicker cuts over many tiny lines. Avoid universal random speckle/noise as primary effect.

## Postmark
Under the rectangle only, small restrained mono-color weathered ink seal. Use location in appropriate English + Chinese if verified, one tiny relevant local silhouette, and three/four cancellation waves. Stamp is a separate printed design on the cream paper, neither part of the rectangle nor an overlay on the scene. Do not add headings, captions, tourist slogans, flags, or watermark.

## Priority order and validation
1. Photo source unchanged above and original scene only.
2. 4:5 and 50/50 split.
3. Exact rectangle geometry, adequate margin, separate centered stamp.
4. No more than eight flat colors *in entire lower half including paper/stamp*.
5. Strong, medium/coarse carved patterns, NOT micro-noise or filter.
6. Flat composition; no convergent perspective.
7. Recognizability and scene-specific object arrangements without over-detailed tracing.

If any requirement conflicts, simplify architecture and foliage further; do NOT narrow margins, overfill the scene, or add colors.

## Suggested creation workflow
1. Inspect provided source photograph. Make a short scene inventory, identify accent color and confirm location if known.
2. Map photo into just eight print colors; draw simplified landmark/figure silhouettes.
3. Allocate patterned cuts by material and scale up marks until visible from afar.
4. Render illustration solely within target rectangle; render stamp separately below.
5. Generate lower half, then (where pixel exactness matters) crop source photo to top aspect and assemble with lower half using deterministic image compositing. Never let a model redraw the top photo.
6. Check bounds, palette and stamp position. Regenerate lower artwork if checks fail; retain unchanged top.
