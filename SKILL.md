---
name: create-low-saturation-urban-characters-v2
description: Create or extend full-body modern urban character illustrations in the confirmed “低饱和都市人物插画 Skill V2｜硬朗直线版” style, including single characters, coordinated character series, compact scenes, and front-side-back turnaround sheets. Use for insurance, finance, healthcare, and lifestyle-service visuals; do not use for rounded blue service illustration V2, photorealistic, 3D, painterly, or highly detailed character art.
---

# 低饱和都市人物插画 Skill V2｜硬朗直线版

Create polished characters with one stable visual system. Use image generation for raster output. The written proportion, geometry, facial, palette, and negative rules below are the authoritative style specification. If the user supplies a character reference, include it as the identity, pose, clothing, and proportion reference while keeping this Skill's hard-line visual grammar.

## Reference workflow

This package intentionally contains no bundled reference images. Do not search for or substitute unrelated style references. When the user supplies an image, pass only that supplied image to the image generator and preserve its identity and pose. Without a supplied image, generate directly from the complete written specification below.

## Visual system

- Use clean two-dimensional flat-vector illustration with hard-edged solid color blocks and a pure white background.
- Keep the mood modern, light, friendly, restrained, and professional for insurance, finance, healthcare, and lifestyle-service branding.
- Use a natural slender body with a head-to-body ratio of about 1:6.5 to 1:7. Make limbs slightly elongated. Preserve a narrow torso, straight leg construction, and restrained shoulder width.
- Keep poses relaxed with a subtle sense of movement. Make gestures legible and anatomically plausible.
- Simplify facial features: black dot or short-line eyes, a geometric nose, a restrained coral-pink smile, and a friendly neutral expression.
- Use low-saturation pale peach skin. Indicate joints, palms, fingers, neck, and small anatomical details only with sparse coral-pink thin lines.
- Build hair from large, clean black shapes with firm geometric boundaries. Preserve a strong silhouette and only essential divisions; never render individual strands.
- Use simple contemporary clothing made from large flat shapes. Minimize seams, folds, decorations, and accessories unless the brief requires them.
- Construct shoulders, sleeves, cuffs, hems, trousers, skirts, shoes, tools, suitcases, buildings, and furniture primarily from straight segments and simple geometric planes. Corners and direction changes must be explicit and clean.
- Reserve simple single curves for the skull, jaw, joints, and necessary hair contours. Do not use decorative S-curves, wavy contours, soft bulges, or inflated shapes.
- Do not use heavy outlines. Use sparse, single-weight coral structure lines only where they clarify anatomy or garment construction. Keep them straight or as one controlled curve; never sketch, double-line, feather, or wobble.
- Every color boundary must be crisp and opaque. No gradients, transparency, airbrush, glow, halo, blur, shading, highlights, depth modeling, paper texture, or antialias-like soft edge treatment.
- Faces must remain flat and minimal. Do not add cheeks, blush, eyelids, pupils, realistic ears, facial shading, or extra age lines unless the brief requires a single restrained cue.

## Shape economy

- Each character should use a small number of large shapes. Clothing normally uses no more than three main color blocks.
- Use at most one to three interior garment lines per major garment. Do not draw realistic folds.
- Give each character only the props required by the brief. Simplify props into straight-edged silhouettes with minimal internal details.
- In scene mode, render architecture and plants with the same hard-edged flat geometry. Keep them separate from character silhouettes unless overlap is explicitly requested.

## Palette

Use high-lightness, low-saturation colors. Keep the supplied reference palette when one exists. Otherwise select from this family:

| Role | Preferred color | Hex guide |
| --- | --- | --- |
| Skin | pale peach pink | `#FFB8AC` |
| Anatomy details and lips | soft coral | `#FF6670` |
| Hair and eyes | solid black | `#000000` |
| Warm primary | soft orange | `#FF8A4C` |
| Coral primary | muted coral pink | `#F98589` |
| Blue primary | gentle cornflower blue | `#5C99EE` |
| Light blue | pale gray blue | `#B9D1F2` |
| Warm neutral | pale apricot | `#F4C6A7` |
| Cool neutral | medium gray | `#8F8F8F` |
| Background | pure white | `#FFFFFF` |

Allow only small adjustments for harmony. Do not raise saturation sharply, introduce unrelated accents, or apply light-to-dark variation within a color block.

## Reference preservation

When extending a supplied character, preserve the following invariants unless the user explicitly requests a change:

- facial design, expression, head shape, hairstyle silhouette, skin tone, and body proportions;
- pose, gesture, arm bends, hand placement, leg stance, body lean, and weight distribution;
- clothing cut, garment lengths, color blocks, shoes, glasses, handheld objects, and other accessories;
- original illustration simplicity and line density.

Do not replace the pose with a neutral model-sheet pose. Do not beautify, add detail, or redesign the character.

## Three-view mode

For a turnaround sheet, show exactly three complete full-body views on one wide white canvas: front, exact 90-degree side profile, and back. Use equal scale, aligned head height and foot baseline, and even spacing.

- Rotate the same posed character in space; preserve the original gesture and body proportions across all views.
- Keep accessories and handheld objects, showing only the surfaces logically visible from each angle.
- Infer unseen hair and garment surfaces conservatively from the reference.
- Keep side and rear silhouettes structurally consistent with the front view.
- Do not crop the head, hands, feet, hairstyle, or clothing.

## Generation modes

- **Character mode:** prioritize the character; use pure white background and only requested props.
- **Scene mode:** keep characters unchanged and render every background object with the same hard-edged flat system. Use sparse isolated scene elements and abundant white space.
- **Turnaround mode:** follow the three-view requirements below while preserving the original pose.

## Series consistency

For multiple new characters, keep the head-to-body ratio, facial grammar, skin rendering, line weight, palette saturation, and overall visual density constant. Differentiate characters primarily through hairstyle, clothing silhouette, posture, accessories, age cues, and occupation cues.

## Prompt construction

Translate the user's brief into a concise production prompt containing:

1. character identity, age range, occupation or role;
2. hairstyle, clothing, accessories, pose, expression, and any prop;
3. full-body framing and required view or aspect ratio;
4. the visual system and palette rules above;
5. invariants from any reference image;
6. the negative constraints below.

## Negative constraints

Avoid photorealism, 3D, painterly rendering, generic soft commercial illustration, soft rounded vector art, inflated shapes, wavy contours, hand-painted brush texture, thick black outlines, high saturation, dramatic lighting, shadows, gradients, highlights, transparency, glow, blur, feathering, noise, individual hair strands, skin texture, blush, oversized heads, short chibi bodies, over-detailed facial features, complex clothing folds, cluttered backgrounds, extra characters, extra limbs, malformed hands, incorrect finger counts, cropping, text, logos, and watermarks.

## Quality check

Before delivery, compare the result against this written specification and verify: full-body completeness where requested, five fingers per visible hand, correct limb count, restrained facial features, low saturation, pure white background, crisp opaque edges, straight garment and prop geometry, no lighting effects, no gradients, no realistic folds, and no soft generic-vector drift. For turnaround sheets, also verify that all three views depict the same person at the same scale with the same pose and outfit. If the result fails, make one targeted retry addressing only the failed checks.
