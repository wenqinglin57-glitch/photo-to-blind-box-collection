# Six collectible cards

## Fixed card specification

- Produce six separate card fronts, one for each approved figure.
- Trim size: 50 mm wide × 80 mm high, portrait orientation, exact 5:8 ratio.
- Resolution: 300 DPI.
- Keep the figure and important scene content inside a safe area.
- When a print-ready version is requested, add 3 mm bleed without changing the 50 × 80 mm trim size.
- Do not create card backs unless requested.
- Do not place any text, captions, names, numbers, dates, logos, watermarks, or micro-text on the card artwork.

## Card intake

For every card, ask for:

1. The scene photo to use as the background reference.
2. Which approved figure 01–06 to add.
3. Whether to use that figure's exact approved pose or create a newly requested pose.

If the user supplies all six mappings at once, do not ask one card at a time. By default, preserve the exact approved render and pose.

## Background pass with `$scenes-gathered-zine-v1-3`

Read and use the skill, but apply these card-specific overrides:

- Output is 5:8, not the skill's default 3:5.
- No micro-text, lettering, title, caption, logo, date, or watermark.
- Do not include or redraw the Q-version figure during the background pass.
- Use 3–7 auxiliary fragments.
- Every auxiliary fragment must be extracted from the source photo's contours, colors, material, direction, rhythm, or meaning. It is a low-detail paper echo of the source, not an added decoration.
- Do not invent unrelated icons, flowers, stickers, geometric motifs, or scenery.
- Scenic extension must remain related to adjacent source objects and the source's semantic minimum.
- Preserve one truthful photographic anchor, active negative space, one structural high-chroma hue when useful, and a visibly hand-torn fibrous photo-to-paper boundary.
- Aggressively compress dense foliage and micro-detail into a few quiet large forms.

Approve the background only when the source scene remains recognizable, the fragment count is 3–7, and there is no text of any kind.

## Figure composite pass

- Composite the exact approved transparent 3D figure cutout after the background is finished.
- Preserve the approved face, body proportion, hairstyle, outfit, pose, props, and glossy PVC material.
- Do not convert the figure into watercolor, paper collage, or ink-wash.
- Use minimal grounding shadow only; do not add a base.
- Keep the full head, hands, props, and shoes inside the safe area.
- Do not cover the scene's essential photographic anchor or its torn-paper boundary.
- Add no extra decoration during compositing.

## Card quality gate

Verify:

- exactly six separate cards exist;
- each card is 50 × 80 mm at 300 DPI;
- each assigned scene is recognizable;
- each card has 3–7 source-derived auxiliary fragments;
- no card contains text or micro-text;
- the correct full approved figure is present and uncropped;
- the six cards feel like one collection while retaining six distinct scenes.

