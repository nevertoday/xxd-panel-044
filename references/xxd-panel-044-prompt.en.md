# XXD Panel 044 | Pure-Gold Flat Material Image Production Prompt

## Runtime complete-canvas contract — highest priority

- `TOP_BOTTOM` and `LEFT_RIGHT` default to one complete finished generation using the current source as a high-fidelity edit/reference input. Do not pre-split the job into photographic and design halves.
- Top-bottom keeps the faithful source in approximately the upper 50% and performs this style transformation below; left-right uses the faithful source in approximately the left 50% and the transformation on the right. Unify both regions through colour, light, rhythm, typography, and meaning.
- `DESIGN_ONLY` and `WALLPAPER_PACK` use the complete canvas while the source remains an invisible identity/content reference. Recompose every wallpaper separately for its device.
- `FINAL CANVAS` means the ratio/pixels of the whole finished artwork and must be explicitly resolved before generation; never apply source dimensions silently. `DESIGN FRAME` is used only if a failed complete-canvas retry triggers deterministic composition fallback.
- Retry a failed complete canvas once against the failed constraint only. Scripted composition is allowed only after that retry still fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless pixel calibration.

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is available through the current built-in image tool or a configured compatible route, use it first for the high-fidelity reference/edit and complete-canvas generation required by this prompt.
- Also support Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model only when the actual route can preserve the source, realise the whole finished canvas, render the target-language text, and accept the multiple references needed by a linked wallpaper pack.
- An alternative model changes only the generation route. It must not change this prompt's modes, canvas, source visibility, copy, locale, wallpaper relationship, or complete-canvas-first / composition-fallback-only logic. Do not silently downgrade a hard requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task, but never echo, display, log, or expose their value in chat, prompts, or diagnostics. Do not persist them or modify global route configuration unless explicitly requested.
- Judge availability by actual image capability, not by a provider name or one missing environment variable.

Process only the source photograph explicitly supplied for this fresh task. Privately lock identity, structure, pose, direction, action, function, opening, relation, emotional implication, and source colour. Preserve at least three source-specific cues and never borrow from another input, old output, or sample.

## Aesthetic transformation

Lay the decisive source silhouette directly onto one dark flat plane using real high-purity gold material—foil, hammered sheet, pressed metal, or thin cast gold—with restrained sheen, soft reflection, hammer marks, embossed traces, edge lift, folds, and small foil breaks.

Use this causal sequence: lock decisive silhouette and structure → preserve three cues → flatten volume into one thin gold material image → choose a source-related deep pure ground → distribute soft metallic reflection through hammering, embossing, folds, edge lift, and foil breaks → photograph frontally without distortion → integrate copy as pressed or low-contrast material detail.

## Hard visual requirements

- Preserve at least three cues across contour, proportion, pose, direction, action, opening, structural turn, or relation.
- Use a thin, planar material logic: gold foil, hammered sheet, pressed metal, or shallow cast layer lies on the surface; it is never a freestanding 3D sculpture or heavy gold block.
- Render high-purity gold with refined matte-to-soft sheen, gentle reflection, small hammer marks, embossing, edge undulation, folds, shallow relief, and selective foil breaks.
- Use a perfectly frontal, level camera and a deep, clean, restrained source-related ground with large quiet space and no perspective distortion.
- Keep one gold subject as the sole focus; reflection follows real material relief without mirror glare, vulgar yellow, or luxury-advertising drama.

## Copy and locale

Obey the resolved automatic, exact-user, or text-free copy mode and target locale. Use one extremely short subject, action, emotion, or metaphor title and only necessary microcopy. Integrate native type as fine metal embossing, shallow relief, edge-aligned marking, or low-contrast print belonging to the same plane. Preserve exact user wording verbatim. In text-free mode render no letters, numbers, captions, labels, or pseudo-text.

## Mode and acceptance


Reject: 3D gold block, freestanding sculpture, mirror gold, vulgar yellow, cheap plating, metallic sphere CGI, jewellery advertisement, oblique camera, perspective distortion, ornate luxury decoration, thick shadow, e-commerce display, template gold poster. Also reject logos, watermarks, swatches, UI, device mockups, unsupported facts, fake foreign text, and unreadable copy.

If any hard condition fails, correct the generated bitmap. Never fake the artwork with programmatic drawing, SVG, HTML, Canvas, 3D code, or a post-composited type overlay.
