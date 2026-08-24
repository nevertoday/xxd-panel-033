---
name: xxd-panel-033
description: "Create XXD Panel 033 artwork from supplied photos in four combinable modes: photo above/editorial collage below, photo left/design right, design alone, or a four-device wallpaper pack with independent or anchor-linked continuity. Rebuilds the source as a modern magazine-cover illustration with a recognisable subject motif, layered repetition, scale contrast, vivid source-derived colour, tactile print texture, and image-bound cover typography. Use for the exact 033 fashion-editorial collage style; never use it for generic tourism posters, e-commerce layouts, cartoons, or unrelated magazine templates."
---

# XXD Panel 033 · 现代杂志封面式平面拼贴

Turn each supplied photograph into finished modern editorial-cover artwork. Preserve the photograph only in paired modes; every transformed frame must reduce the same subject into a recognisable visual motif, then build a layered cover system through source-derived repetition, enlargement, crop, overlap, vivid flat colour, tactile print texture, and typography that actively participates in the composition.

Operational rules follow the shared XXD Panel workflow contract: four combinable modes; an explicitly confirmed whole-canvas ratio or exact resolution before generation; single complete-canvas raster generation by default; high-fidelity source reference in paired modes; linked or independent four-device wallpapers; copy and locale preflight; fresh generation jobs; privacy-preserving raster generation; deterministic composition as fallback only; and one fresh task directory per source and mode. Style-specific sections refine aesthetics and copy but never override this contract.

## Non-negotiable contract

- One source photo may be processed in one or more selected modes. Each selected ordinary mode (`top-bottom`, `left-right`, `design-only`) produces one PNG; selected `wallpaper-pack` produces exactly four separate PNGs. Selecting all four modes therefore produces seven final files per source. Keep every mode in its own task directory and never combine modes, sources, or wallpapers into a grid, contact sheet, or overview.
- Resolve a non-empty ordered set of modes before generation: `top-bottom`, `left-right`, `design-only`, and/or `wallpaper-pack`. Accept one choice, multiple choices separated by `+`, Chinese/English commas or whitespace, natural-language names, or `全部` / `all`. Deduplicate repeated choices and execute in menu order 1→4. If none is specified, ask with the multiline multi-select menu in the workflow. Do not ask again when the set is already clear.
- When the selected set contains `wallpaper-pack`, require a second choice: `linked` or `independent`. A linked pack approves one anchor wallpaper, iPad by default, and makes every other device reference both the original photo and that same anchor. An independent pack gives every device only the original photo. Neither permits resizing or cropping one wallpaper into the others. Do not ask this follow-up when wallpaper mode is not selected.
- Paired modes target a visually equal 50/50 relationship within one coherent generated canvas. Minor generative deviation is acceptable unless the user explicitly requires pixel-exact halves; exact deterministic geometry belongs to the documented fallback. `design-only` and every wallpaper contain no visible source photograph, no seam, and no reserved photographic panel.
- The whole final canvas ratio or exact pixels must be explicitly resolved before generation. Offer the archived/original-prompt 3:4, source aspect as an explicit choice, common ratios, or custom ratio/pixels; never infer explicitly selected final-canvas dimensions silently. Exact pixels take precedence over an explicitly chosen ratio.
- Visible photography remains faithful. Allow only restrained editorial grading and environmental extension needed for an explicitly overridden canvas. Never stretch, distort, repaint, replace, or structurally alter the subject.
- The transformed frame is not a photo filter or a stock cover template. It preserves at least three source-specific identity cues, then converts the defining subject, contour, pose, environment fragment, or structural relation into a layered background–subject–accent editorial collage with one clear focal point.
- Copy has no silent default. Resolve automatic copy, exact custom copy, or text-free output before image generation. Automatic and custom modes also require a target language or locale. By default, one source-specific copy package is shared verbatim across all selected modes; accept explicit per-mode copy overrides when the user supplies them.
- Render no logo, watermark, signature, colour swatch, UI, device mockup, decorative pseudo-text, or unrelated explanatory prose.

## Aesthetic motive lock

Modes and device ratios may change placement but never the 033 motive. Every transformed frame must visibly express this chain:

**the photograph's most memorable subject, contour, pose, action, relation, material, season, or emotional pressure → one recognisable graphic motif → source-derived repetition, enlargement, crop, layering, and texture variation → a clear background / middle subject / foreground accent hierarchy → vivid but disciplined source-derived colour → bold native cover typography that reveals the same idea rather than merely naming it**.

The defining motif is not automatically the largest object. Choose the subject feature or relation that best carries the photograph's identity and narrative, then use scale and repetition to create a thematic visual field without losing the primary reading. One small high-contrast accent may sharpen drama or story, but it cannot replace the subject.

Reject a result as generic if an unrelated photo could replace the source without materially changing the motif, layer hierarchy, crop, repetition rhythm, palette, texture, or cover copy. Also reject template forests, generic travel advertising, product grids, stock magazine mastheads, scrapbook clutter, children's cartoons, smooth 3D, muddy colour, and decoration that does not strengthen the source story.

## 033 visual system

### Recognisable motif and layered field

- Keep at least three source-specific cues across contour, pose/orientation, proportion, action, material, colour, opening, overlap, negative shape, environment structure, or relational distance.
- Reduce rather than mechanically trace. Convert the strongest subject, local contour, environmental element, or structural relation into one graphic motif that remains immediately tied to this source.
- Build an intentional background layer from enlarged or repeated source-derived shapes, a dominant middle subject layer, and a restrained foreground accent or typographic crossing. Each layer has a distinct scale and job.
- Allow off-centre placement, overlap, boundary crossing, partial occlusion, and assertive crop when they increase focus and rhythm. Never distribute motifs evenly like wallpaper or lose the primary subject in repetition.

### Scale, repetition, and editorial tension

- Use repetition to create a visual field, not to multiply unrelated decoration. Repeated forms must inherit the source contour, material, season, gesture, or structure.
- Establish one decisive scale contrast: monumental versus tiny, close crop versus distant repeat, dense block versus open field, or heavy dark anchor versus bright accent.
- A small high-contrast accent may introduce a second beat, contradiction, or narrative clue. It remains subordinate and source-grounded.
- Keep the hierarchy legible at thumbnail size: focal subject first, title system second, supporting layers third.

### Colour and print material

- Extract the source's most alive, recognisable, emotionally useful colours and condense them into one dominant, one or two supporting, one grounding dark, and one sparing highlight.
- High saturation is allowed when controlled by area, value, and contrast. Avoid candy colour, fixed palettes, grey mud, or colour that no longer belongs to the source.
- Use flat editorial fields with selective grain, halftone, grid, fabric, spray, ink transfer, dry brush, or print-register texture. Texture creates material depth but never obscures identity or typography.
- Preserve active whitespace and clean reading paths even when the composition is dense. Rich layering is not permission for clutter.

## Copy as a real cover system

Automatic copy reads the subject, attitude, action, season, material, relation, and supported implication, then resolves one striking main title and one more emotional or narrative subtitle in the target locale. The title should feel highly bound to this picture and create a small moment of recognition; it is not a generic magazine label.

- Prefer one bold main title, one subordinate narrative subtitle, and only genuinely useful microcopy. Issue numbers, dates, places, times, labels, and facts appear only when supplied or reliably established; never fabricate them to imitate a magazine.
- Let type cross colour fields, stack vertically, run at large scale, overlap the motif, or occupy negative space when legibility and native-script structure remain strong.
- The type family, weight contrast, spacing, line breaks, and overlap must echo the motif's shape, scale, energy, and texture. It cannot be a title pasted on after the illustration.
- Cleverness must be earned by the source. Do not force a pun, motivational quote, sentimental backstory, or universal words such as “DREAM”, “MEMORY”, or “JOURNEY”.
- Apply the unrelated-image swap test. If the wording works just as well on another image, rewrite it.
- Preserve finished user wording verbatim. Refine an editable direction only within the user's permission while protecting audience, goal, mandatory words, tone, implication, and semantic phrase breaks.

Resolve locale independently from command language:

```text
target market or audience > requested output language > direction language; if none is explicit, ask before generation
```

Use natural contemporary language, native rhetoric, punctuation, spacing, and line breaking. Japanese uses appropriate kanji/kana balance and kinsoku-aware breaks; Korean uses correct spacing and intact Hangul syllables; UK editions use British English; Arabic uses natural Modern Standard Arabic unless a regional variety is requested, correct connected shaping, RTL flow, and semantic breaks. Never infer nationality or audience language from appearance, clothing, scenery, filenames, metadata, or signs. Never use pseudo-foreign text for atmosphere.

## Raster generation and privacy

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is exposed through the host's built-in image tool or an already configured compatible route, use it before any other model. Preserve the current XXD execution contract: resolve the whole final canvas before generation, use the source as a high-fidelity reference, generate paired modes as one complete canvas, and keep deterministic composition as fallback only.
- Also support **Seedance 5.0 Pro**, **Nano Banana Pro (Gemini Image Pro)**, **Nano Banana 2 (Gemini Image Flash)**, or another compatible bitmap model when it is actually available through a tool or configured route and can satisfy the selected mode. Required capabilities include reference-image generation/editing, source fidelity, the resolved whole-canvas ratio, native target-language text, and multi-image reference input when a linked wallpaper pack needs it.
- Alternative models are secondary routes, not a different workflow. Do not let a model switch silently change the selected modes, final canvas, source-visibility rules, copy, locale, wallpaper relationship, fresh-task boundary, raster-only delivery, or the full-canvas-first strategy. If an alternative cannot satisfy a hard requirement, do not silently degrade that requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. A user may voluntarily provide credentials for the current task. Accept them without echoing, displaying, logging, or reporting their value. Do not persist credentials or modify provider, account, billing, or global route configuration unless the user explicitly asks for that configuration change.
- Determine availability from an actual image-capability check. Do not declare GPT Image 2 or every other route unavailable merely because one tool is absent, one call failed, or one expected environment variable is unset.

Prefer GPT Image 2 through the host's built-in bitmap image-generation capability when exposed, and follow the available `imagegen` skill for the built-in execution details. View each local source before generation. Use one generation call per distinct asset; a wallpaper pack requires four calls. “Flat collage”, “grid”, “cover layout”, and “print texture” describe appearance only and never authorise SVG, HTML, CSS, Canvas, diagrams, or programmatic drawing as the artwork.

If built-in bitmap generation is unavailable, use `scripts/configured_imagegen.py`, which reuses an already configured compatible bitmap route and emits sanitised status only:

```bash
python3 scripts/configured_imagegen.py probe
python3 scripts/configured_imagegen.py edit --image source.png \
  --prompt-file /private/job-temp/transform-prompt.txt \
  --out /private/job-temp/design.png --size 1536x1024 --quality high
```

Judge readiness by actual bitmap capability, not a provider name or one environment variable. Never display, echo, log, or report the user's actual provider, endpoint, headers, credential values, account identifiers, route configuration, prompts, or response bodies. Do not manually inspect unrelated credential files. Do not persist user-provided credentials or modify global route configuration unless explicitly requested. The bridge's sanitised JSON is the complete allowed diagnostic surface.

An explicit invocation of `/xxd-panel-033` or `$xxd-panel-033` with a source image and requested output authorises this generation through any already configured authenticated bitmap route available to the session. Do not ask for a second confirmation solely because the route changes. This does not authorise changing credentials, providers, billing, accounts, or global settings.

Only report generation as unavailable after checking preferred GPT Image 2, every eligible exposed alternative, the bundled probe, and any suitable route or API key the user elects to provide. State the limitation narrowly and never guess the cause or expose the user's actual provider. Never substitute code-rendered art.

## Fresh-task and source boundary

Every invocation starts a fresh generation job unless the user explicitly asks to continue, audit, compare, edit, or reuse a named earlier result. Repeating the same source and parameters still means generating a new result in a new task directory. An old file can never satisfy a new request.

Use only images attached to the current invocation, explicit user paths, or a previously supplied image that the current request clearly identifies as “the same image”. Never broadly scan the Desktop, workspace, output root, or historical task folders to find a substitute source. If the intended source cannot be accessed, ask for it.

## Workflow

1. Resolve one or more modes. If missing, ask exactly this as normal multiline chat text and wait:

   ```text
   请选择一个或多个模式（回复序号；多选可用 +、顿号或逗号）：

   1. 上下双联（原图在上＋033 设计在下）
   2. 左右双联（原图在左＋033 设计在右）
   3. 纯设计版（只显示 033 设计画面）
   4. 四端壁纸套装
      手机＋iPad＋电脑＋儿童手表

   示例：1｜1+3｜1、2、4｜全部
   ```

2. Before any ordinary-mode generation, explicitly resolve the **final finished canvas**, not the size of one panel. If the user did not already supply a ratio or exact pixels, ask and wait:

   ```text
   请选择最终成品画幅（回复序号即可；多选模式可共用，也可分别指定）：

   1. 原提示词画幅 3:4
   2. 跟随原图比例
   3. 常用比例
      1:1｜4:5｜2:3｜3:2｜16:9｜9:16
   4. 自定义比例或准确像素

   这里指整张最终成品的比例，不是单个区域。
   示例：1｜3：9:16｜4：2160×3840
   ```

   “跟随原图比例” is valid only when the user explicitly selects it. Never infer a silent canvas from the source dimensions, orientation, archived 3:4 brief, mode, or previous output. In multi-select, ask which mode an ambiguous ratio belongs to. Exact pixels take priority over a chosen ratio. For paired modes, odd split axes are allowed for direct generation; require an even split axis only if deterministic fallback composition is actually triggered.

3. Before generation, resolve copy mode and locale. If missing, ask and wait:

   ```text
   正式做图前，请确认文字设置（回复序号即可）：

   1. 自动文案
      我根据原图与 033 气质创作文案；请同时注明语言或地区
   2. 自定义文案
      请直接输入要呈现的准确文字，并注明语言或地区
   3. 无文字

   示例：1｜日语
   示例：2｜英式英语｜STILL IN BLOOM
   ```

   Automatic copy must be source-specific and native to the resolved locale. Preserve exact custom copy verbatim. Do not infer locale from appearance, clothing, scenery, filenames, metadata, or visible signs.

4. Only when `wallpaper-pack` is selected, resolve its relationship and device sizes. Ask for `1. 连贯套装` or `2. 四张独立` when missing. A linked set approves one iPad anchor by default; the other three outputs each reference the original plus that same anchor and are independently recomposed. An independent set gives every device only the original. Then ask for either the common preset—phone `1440×3200`, iPad `2048×2732`, desktop `3840×2160`, watch `1024×1024`—or labelled custom pixels. Never crop one wallpaper into another or chain derivatives.

5. Start a fresh job and reserve collision-safe output directories before generation. Use only the current invocation's explicit source or theme. Read `references/xxd-panel-033-prompt.en.md` or `references/xxd-panel-033-prompt.zh-CN.md` immediately before building the generation request.
6. Privately lock the principal subject or inseparable relationship, at least three source-specific recognition cues, the style's complete aesthetic motive, composition logic, materials, palette, typography, exact copy, and locale. The source photograph is the factual and identity anchor; do not borrow content from samples or old outputs.
7. Use **single complete-canvas generation as the default for every mode**:
   - `top-bottom`: supply the source as a high-fidelity edit/reference input and generate one finished image containing the faithful source in the upper half and the 033 transformation in the lower half.
   - `left-right`: supply the source as a high-fidelity edit/reference input and generate one finished image containing the faithful source on the left and the 033 transformation on the right.
   - `design-only`: generate the 033 transformation across the whole canvas; the source is reference-only and not visible.
   - `wallpaper-pack`: generate four separate complete canvases, one per device, following the resolved independent or linked relationship.
8. Append the complete-canvas payload below to the full local style prompt. Keep all 033-specific aesthetic and typography instructions active across the entire composition. For paired modes, ask for approximately equal regions while prioritising a coherent finished artwork: colour, light, rhythm, typography, meaning, and any cross-panel echo must feel intentionally unified.
9. Generate each distinct output as a fresh raster image job. Do not request two separate half-images, a contact sheet, a mockup, an empty reserved panel, or a code-rendered substitute.
10. Inspect the actual bitmap at full size and thumbnail size. Check, in order: whole-poster integration; 033 aesthetic fidelity; source identity and structure; visual and semantic correspondence between regions; typography and locale; mode, ratio/pixels, count, and PNG format; then approximate 50/50 geometry.
11. If a paired result fails a hard requirement, retry the **complete canvas once**, changing only the failed constraint. Use `scripts/compose_panel.py` only after that retry still fails, or when the user explicitly requires pixel-identical source preservation, the active image route cannot realise the selected canvas, the requested ratio exceeds route limits, or final lossless pixel calibration is necessary. The script is a fallback utility, never the default creative path and never an aesthetic judge.
12. Reopen every final PNG, apply the acceptance gate, and return absolute paths in source order and mode order 1→4. Wallpaper order is phone, iPad, desktop, watch.

## Complete-canvas generation payload

Append one resolved block to the style prompt for each output:

```text
OUTPUT MODE: TOP_BOTTOM | LEFT_RIGHT | DESIGN_ONLY | WALLPAPER_PACK
DEVICE PROFILE: NONE | PHONE | IPAD | DESKTOP | WATCH
FINAL CANVAS: <whole finished ratio and/or exact WIDTHxHEIGHT>
GENERATION STRATEGY: SINGLE COMPLETE CANVAS
REFERENCE ROLE: SOURCE — HIGH-FIDELITY CONTENT AND IDENTITY ANCHOR
SOURCE VISIBILITY: UPPER 50% | LEFT 50% | REFERENCE ONLY — NOT VISIBLE
LAYOUT RULE:
- Produce one finished poster in one image.
- TOP_BOTTOM keeps a faithful photographic source in the upper half and creates the transformed design in the lower half.
- LEFT_RIGHT keeps a faithful photographic source in the left half and creates the transformed design in the right half.
- DESIGN_ONLY and WALLPAPER_PACK use the whole canvas for the transformed design and show no source photograph or reserved panel.
- Keep paired regions approximately equal while unifying colour, light, rhythm, typography, and meaning.
- Do not output separate panels, a contact sheet, a mockup, or an empty placeholder.
WALLPAPER RELATIONSHIP: NONE | INDEPENDENT | LINKED
ANCHOR DEVICE: NONE | IPAD
```

For text output append:

```text
COPY MODE: REQUIRED
COPY ORIGIN: USER_EXACT | USER_DIRECTION | SOURCE_DERIVED
COPY LOCALE: <resolved locale>
COPY PAYLOAD: <the exact 033-specific title and supporting-text package resolved under the local production prompt>
COPY RULE: Render only the populated strings in COPY PAYLOAD, each exactly once. Do not rewrite, translate, spell-correct, duplicate, or add text. Use native shaping, direction, punctuation, spacing, and semantic line breaks. Preserve the 033-specific hierarchy, amount of supporting text, placement, material, and typographic role instead of applying a generic overlay.
```

For text-free output append only `COPY MODE: NONE — render no text or pseudo-text anywhere.`

## Composition fallback only

`scripts/compose_panel.py` remains available for deterministic recovery and audit. Trigger it only under step 11. When used, generate a same-aspect design asset from the full 033 prompt, preserve the source without destructive crop or stretch, and document which fallback condition applied. A direct complete-canvas success must not be split and recomposed again.

```bash
# Read-only audit after direct generation
python3 scripts/compose_panel.py --audit final.png --layout top-bottom --size WIDTHxHEIGHT

# Deterministic fallback after the complete-canvas retry has failed
python3 scripts/compose_panel.py --source photo.png --design design.png \
  --out final.png --layout top-bottom --size WIDTHxHEIGHT
```

## Output location

Save finished work under `~/Desktop/xxd/xxd-panel-033/` unless the user supplies another destination. Create the shared `~/Desktop/xxd/` wrapper, the skill root, and each task directory when needed.

- Wrap every source-and-mode result in a fresh task directory: `<source-stem>-top-bottom/`, `<source-stem>-left-right/`, `<source-stem>-design-only/`, or `<source-stem>-wallpaper-pack/`.
- A batch or multi-select creates one sibling task directory per source and selected mode. Never mix sources or modes.
- Ordinary task directories contain only one finished PNG: `<source-stem>.png`, `<source-stem>-lr.png`, or `<source-stem>-design.png`.
- The final count per source equals one file for each selected ordinary mode plus four files when `wallpaper-pack` is selected. `all` / `全部` therefore means seven final PNGs across four sibling task directories.
- A wallpaper task directory contains exactly four finished PNGs named `<source-stem>-wallpaper-phone.png`, `-ipad.png`, `-desktop.png`, and `-watch.png`; do not create device subdirectories.
- Never overwrite. Append `-2`, `-3`, and so on to a colliding task-directory name while keeping filenames unchanged.
- Keep prompts, intermediate generations, plans, audits, and source copies outside the finished task directory.

## Acceptance gate

Before accepting each result verify:

- Mode, exact pixels, explicit final-canvas ratio or pixels, split axis, seam, and output count are correct.
- Visible photography is faithful and type-free; source-hidden outputs contain no source photograph or seam.
- The focal motif is recognisable through at least three source-specific identity cues; repetition and crop strengthen rather than erase it.
- Background, middle subject, and foreground accent have distinct scale and jobs; one clear focal point survives at thumbnail size.
- Palette is source-derived, vivid, and disciplined by area and value; grain, halftone, fabric, spray, transfer, or dry-brush texture is selective rather than muddy.
- Automatic title and subtitle express the grounded meaning and fit this image specifically; exact user copy remains verbatim. Dates, issue numbers, places, and labels are never invented. All rendered text is correct and native to the resolved locale; text-free output contains no text or pseudo-text.
- Type behaves as an integrated magazine-cover system through scale, stacking, crossing, overlap, and negative space—not a boxed title pasted on afterward.
- Every wallpaper is separately recomposed, respects safe regions, contains no system UI, and is not a crop of another device result. A linked pack shares one visual family without drifting from the source.
- Every delivered PNG was newly generated for this invocation and lives in its fresh task directory.

## Override policy

Preserve user-specified source, mode set, output count, dimensions, target locale, copy mode, and exact finished wording. Priority is explicit text-free request > exact user wording > editable user direction > source-derived automatic copy. Exact pixels take precedence over an explicitly chosen ratio; neither may be inferred silently. A labelled wallpaper size overrides only that device.

User instructions may change subject emphasis, palette intensity, layer density, typographic energy, or copy within 033, but do not silently relax one-photo isolation, exact paired geometry, four separate wallpaper outputs, fresh-task generation, source-hidden output rules, or native-language typography. Leave the modern editorial-cover collage aesthetic only when the user explicitly asks to leave the 033 style.

## Provenance boundary

The user's original style brief is archived at [references/033-source.md](references/033-source.md). It records the initial 3:4 top-bottom example but does not override the operative mode and explicit final-canvas selection and complete-canvas generation rules. The full local 033 prompt is the production specification. Never borrow subjects, colours, copy, or compositions from samples or previous outputs.
