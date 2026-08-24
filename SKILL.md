---
name: photo-to-blind-box-collection
description: Create a coordinated six-item single-person chibi 3D blind-box collection from three two-person life photos or six single-person scene photos, then design a print-ready scene-based package and six 50 x 80 mm collectible cards. Use for end-to-end photo-to-figure collections that require consistent identities, a scenic package front, solid-color remaining panels, an accurate calendar, source-derived silhouettes, and Gathered Scenes Zine card backgrounds. Do not use for a one-off avatar or a figure-only request that does not include the collection workflow.
---

# Photo to Blind Box Collection

Create one coherent six-figure collection, one package system, and six collectible cards. Preserve each person's identity and the relationship between each photo and its assigned figure.

## Required skills and tools

- Use image generation and editing for 3D figures, scene transformations, transparent cutouts, and compositing. Inspect every supplied image before generation.
- During the card phase, read and use `$scenes-gathered-zine-v1-3`, then apply the explicit overrides in [card-workflow.md](references/card-workflow.md).
- Use deterministic layout tools for calendars, silhouettes, dielines, dimensions, labels, and print exports. Do not rely on image generation for critical text, dates, cut lines, fold lines, or measurements.

## Phase gates

Complete the phases in order. Do not skip an approval gate.

1. **Photo intake.** Read [intake.md](references/intake.md). Ask whether this is a two-person or single-person project before requesting the full image set.
2. **Six figures.** Read [figure-workflow.md](references/figure-workflow.md). Produce exactly six single-person figures and a numbered contact sheet. Stop for approval before packaging.
3. **Packaging.** Read [packaging-workflow.md](references/packaging-workflow.md). Build and approve the scenic front first, then complete the remaining solid-color panels and print-ready dieline.
4. **Cards.** Read [card-workflow.md](references/card-workflow.md). Create six separate 50 x 80 mm portrait cards, one for each approved figure.

## Collection invariants

- The final collection always contains exactly six **single-person** figures numbered 01–06.
- A two-person project starts from three different two-person scene photos; each scene yields two separate figures.
- A single-person project starts from six different scene photos; each scene yields one figure.
- If the submitted photos mix single-person and two-person scenes, obtain an explicit six-item mapping before generating.
- Establish a stable identity bible for every recurring person and reuse it across all six designs.
- Packaging defaults to both people on the front for a two-person project and the one person on the front for a single-person project.
- Only the package front uses the transformed scene. All other package panels and flaps use coordinated solid colors. The area outside the packaging dieline is white.
- Replace every inherited `L²` or previous collection mark with the user-provided product name.
- Card artwork contains no micro-text and no typography of any kind.
- Treat all supplied life photos as private project assets. Do not expose them outside the requested outputs.

## Approval and correction limits

- Show one numbered six-figure contact sheet and obtain approval before packaging begins.
- Show one package-front preview and obtain approval before building the full flat plan.
- After each generation stage, make at most one targeted automatic correction pass for obvious errors. If identity, mapping, pose, or layout remains ambiguous, ask the user.
- Never silently change an outfit, accessory, relative height, assigned scene, or person identity. Never merge two people into one figure.

## Deliverables

Organize outputs in a project folder with clear filenames:

- `figures/`: six individual full-body renders, six transparent cutouts, one numbered contact sheet, and six derived silhouettes.
- `packaging/`: approved front artwork, full panel artwork, dieline review image, and print-ready PDF.
- `cards/`: six individual 50 x 80 mm card fronts plus print-ready versions when bleed is requested.

Return finished assets and a concise summary. Do not return generation prompts unless the user asks for them.
