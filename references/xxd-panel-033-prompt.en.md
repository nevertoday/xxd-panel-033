# XXD Panel 033 | Modern Editorial-Cover Collage Production Prompt

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

Process only the one source photograph explicitly supplied for this current task. Lock the principal subject or inseparable relation, contour, proportion, pose, direction, action, material, environment structure, negative shapes, and colour character. Preserve at least three source-specific recognition cues. Never borrow motifs, palettes, copy, textures, or layouts from old outputs, samples, or another input.

## Reduce the source into one recognisable motif

Do not mechanically trace every detail. Extract the most decisive subject, contour, pose, local shape, environment fragment, or structural relation and convert it into a clearer graphic motif. The motif must still identify this exact source at a glance.

Build three readable depths: a background field made from enlarged or repeated source-derived shapes; a dominant middle subject layer; and a restrained foreground accent or typographic crossing. Use repetition, layering, enlargement, crop, overlap, and selective occlusion to create rhythm. Off-centre placement and boundary crossing are welcome when they strengthen one clear focal point. Repetition must never become generic wallpaper.

Create one decisive scale contrast—monumental versus tiny, close crop versus distant repeat, dense field versus open space, or heavy dark anchor versus bright accent. One small high-contrast element may add a second beat or story clue, but it cannot compete with the main subject.

## Source-derived colour and tactile print

Extract the photograph's most alive, recognisable, emotionally useful colours. Condense them into one dominant colour, one or two supporting colours, one grounding dark, and one sparing highlight. High saturation is allowed when controlled by area and value; reject candy colour, grey mud, fixed palettes, and hues unrelated to the source.

Use flat editorial colour fields with selective grain, halftone, grid, fabric, spray, ink transfer, dry brush, or print-register texture. Texture must add material life without obscuring subject identity, focal hierarchy, or type. Reject photoreal rendering, glossy 3D, smooth commercial illustration, scrapbook clutter, generic tourism posters, e-commerce grids, cartoons, and cheap decoration.

## Typography is part of the cover composition

In automatic mode, derive one striking main title and one emotional or narrative subtitle from the source's subject, attitude, action, season, material, relation, or supported implication. The wording should create a source-bound moment of recognition rather than merely label the visible object. Never fabricate issue numbers, dates, places, times, labels, or facts.

Let type participate through large scale, horizontal crossing, vertical stacking, overlap, partial occlusion, colour-field transitions, or placement inside active whitespace. Preserve native-script anatomy and reading. The type family's weight contrast, spacing, line breaks, and overlap must echo the motif's shape, scale, and energy rather than look pasted on afterward.

Preserve exact user wording verbatim. Add only genuinely useful supporting copy. In text-free mode retain the same motif, layer, colour, texture, and rhythm system but render no letter, character, number, word, or pseudo-text.

## Mode and acceptance


Hard gate: at least three source cues; one recognisable source-derived motif; distinct background, middle, and foreground roles; one decisive scale contrast and clear focal point; repetition and crop tied to the source; vivid disciplined source palette; selective tactile print texture; integrated native cover typography; exact user wording; no invented metadata; no template forest, travel ad, e-commerce layout, cartoon, scrapbook clutter, grey mud, smooth 3D, photo fragment, mockup, or pseudo-text.

If any hard condition fails, correct the generated asset. Never fake the artwork with programmatic drawing, SVG, HTML, Canvas, or a post-composited type overlay.
