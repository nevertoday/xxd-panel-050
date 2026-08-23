---
name: xxd-panel-050
description: "Create XXD Panel 050 artwork from supplied photos in four combinable modes: photo above/bespoke airy-blue minimalist flat-vector travel scene below, photo left/design right, design alone, or a four-device wallpaper pack with independent or anchor-linked continuity. Use for the exact 050 style; reject generic city-name travel templates, landmark piles, mechanical tracing, repeated postcard layouts, photorealism, gradients, textures, heavy shadows, crowded detail, dirty colour, excessive pink, and detached headline bars."
---

# XXD Panel 050 · 空气蓝定制旅行矢量场景

Rebuild the source as a bespoke premium minimalist flat-vector travel scene: one unmistakable source-bound focus, two to four meaningful environmental cues, quiet editorial spacing, and a light blue-led palette. The result is a tailored visual identity for this subject, never a generic destination poster.

Operational rules follow the shared XXD Panel workflow contract: four combinable modes; source-adaptive ordinary canvases; exact 50/50 paired geometry; linked or independent four-device wallpapers; copy and locale preflight; fresh generation jobs; privacy-preserving raster generation; and one fresh task directory per source and mode. Style-specific sections refine aesthetics and copy but never override this contract.

## Non-negotiable contract

- One source may use one or more selected modes. Each selected ordinary mode (`top-bottom`, `left-right`, `design-only`) produces one PNG; `wallpaper-pack` produces four separate PNGs. Selecting all four modes produces seven final files per source. Never combine them into a grid, contact sheet, overview, or mockup.
- Resolve a non-empty ordered set of modes. Accept one choice, multiple choices separated by `+`, Chinese/English commas or whitespace, natural-language names, or `全部` / `all`; deduplicate and execute in menu order 1→4.
- If `wallpaper-pack` is selected, resolve `linked` or `independent`. A linked pack approves one iPad anchor by default, then every other device references the original source plus that same anchor. An independent pack gives every device only the original. Never crop one wallpaper into another and never chain derivatives.
- Paired modes split exactly 50/50. `design-only` and every wallpaper show no source photo, seam, or reserved photographic panel.
- Exact user pixels win, then explicit ratio/destination. Otherwise adapt losslessly: `top-bottom` = `W×2H`, `left-right` = `2W×H`, `design-only` = `W×H`. The archived 3:4 canvas is not a silent default.
- Keep visible photography faithful: restrained editorial grading and necessary environmental extension only; never stretch, distort, repaint, replace, or structurally alter the source.
- Preserve at least three source-specific identity, silhouette, proportion, pose, direction, structure, function, colour, distance, or narrative-relation cues in every transformed frame.
- Copy has no silent default. Before generation resolve `自动文案`, `自定义文案`, or `无文字`; automatic and custom modes also require target language or locale. Preserve exact user copy verbatim.
- Render no logo, watermark, signature, colour swatch, UI, device mockup, decorative pseudo-text, or unrelated prose.

## Aesthetic motive lock

Every transformed frame must visibly follow this source-bound chain:

**lock subject, pose, and narrative relation → preserve three specific cues → choose one primary visual focus → derive two to four environmental proofs from the source → reorganise around the subject rather than a template → unify through airy-blue flat-vector language → retain calm breathing room → make title and tagline part of the scene's identity**.

Reject the result as generic if an unrelated photograph could replace the source without materially changing recognition, main focus, supporting evidence, spatial organisation, palette relation, or copy. The operative exclusions are: generic city-name poster, landmark pile, postcard checklist, mechanical tracing, repeated layout, unrelated scenery, photorealism, plastic CGI, gradient, texture, heavy shadow, crowded detail, dirty colour, excessive dusty rose, and detached headline bar.

## 050 visual system

- Preserve at least three source-specific cues across identity, silhouette, proportion, pose, axis, action, structure, function, material, distance, or relation; never reduce the subject to a generic category icon.
- Choose exactly one primary visual focus. Add only two to four source-grounded environmental cues that reveal place, everyday life, atmosphere, or state. If people are necessary, keep three to six small figures integrated into the setting, without a second protagonist.
- Let the source determine whether the scene becomes a street, plaza, shore, courtyard, passage, platform, planted setting, interior corner, open landscape, or lived fragment. Do not impose a destination template or pile up recognisable landmarks.
- Use premium minimalist flat-vector language shaped by Japanese stationery, boutique sticker illustration, and contemporary editorial travel branding: simple geometry, soft contours, coherent line weight, flat colour, restrained detail, clean depth, measured whitespace, and quiet rhythm.
- Derive temperature from the source, then lead with powder blue, mist blue, sky blue, or airy cool blue. Balance with ivory, cream, pale beige, soft grey-green, and architectural neutrals. Dusty rose or muted blush may appear only as a tiny accent.
- Keep one clear hierarchy and enough air. Reject photoreal rendering, thick shadows, watercolour or paper texture, elaborate strokes, gradients, busy backgrounds, excessive detail, visual noise, and repeated object placement.

## Copy belongs to the image language

Automatic copy must infer one concise title and restrained tagline from the source's actual place, object, theme, state, atmosphere, deeper meaning, or hidden relation—not from a generic city-name formula. Add a coordinate-like micro-note or tiny information only when supported. Place native type in earned whitespace, commonly but not mechanically upper-left, and align it with vector shapes, sight lines, and spatial rhythm. It must feel inseparable from the travel identity rather than pasted on afterward.

Copy must pass the unrelated-image swap test. Preserve exact supplied wording verbatim; refine only an explicitly editable direction while protecting audience, purpose, mandatory words, tone, implication, and semantic line breaks.

Resolve locale independently from command language:

```text
target market or audience > requested output language > direction language; if none is explicit, ask before generation
```

Use native wording, rhetoric, punctuation, spacing, shaping, direction, and line breaks. Never infer nationality or audience language from appearance, clothing, scenery, filenames, metadata, or signs.

## Raster generation and privacy

Use the host's built-in bitmap generation capability by default and follow the available `imagegen` skill when exposed. Use one generation call per distinct asset; a wallpaper pack needs four. Style language describes raster appearance only and never authorises SVG, HTML, CSS, Canvas, 3D code, diagrams, or programmatic drawing as the artwork.

If built-in generation is unavailable, use the bundled privacy-safe configured route:

```bash
python3 scripts/configured_imagegen.py probe
python3 scripts/configured_imagegen.py edit --image source.png \
  --prompt-file /private/job-temp/transform-prompt.txt \
  --out /private/job-temp/design.png --size 1536x1024 --quality high
```

Judge readiness by actual bitmap capability, not a provider name or a single environment variable. Never display, log, persist, or report providers, endpoints, headers, credentials, account identifiers, route configuration, prompts, responses, or secrets. The bridge's sanitised status is the entire allowed diagnostic surface. An explicit invocation with source and desired output authorises any already configured authenticated bitmap route available to the session; do not request another confirmation solely because the route changes.

Only report generation unavailable after built-in bitmap capability and the bundled sanitised probe both fail. State the limitation narrowly, never guess its cause, and never substitute code-rendered art.

## Fresh-task and source boundary

Every invocation starts a fresh job unless the user explicitly asks to continue, audit, compare, edit, or reuse a named result. Repeating the same source and settings still requires fresh generation. An old file can never satisfy a new request.

Use only current attachments, explicit paths, or a previously supplied image clearly identified by the user. Never scan Desktop, `~/Desktop/xxd/xxd-panel-050/`, or historical task folders for a substitute.

## Workflow

1. If mode is unresolved, ask in normal multiline text and wait:

   ```text
   请选择一个或多个模式（回复序号；多选可用 +、顿号或逗号）：

   1. 上下双联（完整原图＋同尺寸设计图）
   2. 左右双联（完整原图＋同尺寸设计图）
   3. 纯设计版（沿用原图比例，不显示原照片）
   4. 四端壁纸套装
      手机＋iPad＋电脑＋儿童手表

   前三种不指定尺寸时按原图自适应；也可主动指定尺寸。壁纸可按设备分别给分辨率。
   示例：1｜1+3｜1、2、4｜全部
   ```

2. If wallpaper relationship is unresolved, ask for `1. 连贯套装（原图＋同一批准定调图）` or `2. 四张独立（每张只参考原图）`.
3. Before generation, ask for `1. 自动文案（注明语言／地区）`, `2. 自定义文案（准确文字＋语言／地区）`, or `3. 无文字` when unresolved.
4. Resolve dimensions per mode. For wallpapers ask for labelled custom sizes or the common preset: phone `1440×3200`, iPad `2048×2732`, desktop `3840×2160`, watch `1024×1024`. Exact paired canvases require even split axes; never silently round.
5. View the source and privately lock identity, at least three recognition cues, structure, action, relation, environmental evidence, emotional implication, colour logic, copy payload, and target locale. Do not claim unsupported facts.
6. Create a new collision-safe root under `~/Desktop/xxd/xxd-panel-050/`, then one source folder and sibling mode folders. Never overwrite or use an old output as completion evidence.
7. Read `references/xxd-panel-050-prompt.en.md` or `.zh-CN.md`, append the locked source facts, exact copy payload, `OUTPUT MODE`, `FINAL SIZE`, and `DESIGN FRAME`, then generate each distinct design frame separately.
8. For paired modes, generate only the design panel at the planned half-frame size and compose with `scripts/compose_panel.py`. For design-only and wallpapers, generate the whole canvas without the source photo or a seam.
9. Inspect every result at full size. Correct the asset—not only the prompt—until identity, style, copy, locale, raster format, dimensions, and count pass.

## Output structure

```text
~/Desktop/xxd/xxd-panel-050/<fresh-task>/
└── source-01/
    ├── top-bottom/final.png
    ├── left-right/final.png
    ├── design-only/final.png
    └── wallpaper-pack/phone.png · ipad.png · desktop.png · watch.png
```

Create only selected folders. Return direct PNG paths and a concise count summary. Do not create an automatic combined preview.

## Acceptance gate

- Correct fresh source, selected modes, dimensions, file count, and exact 50/50 paired geometry.
- At least three source-specific recognition cues remain; one primary focus, two to four grounded contextual cues, and every visual-system requirement above are visible.
- Copy is exact, source-bound, language-native, legible, and structurally integrated; text-free output contains no text or pseudo-text.
- Linked wallpapers share the original source and same approved anchor without derivative chaining; independent wallpapers use only the source.
- Final files are raster PNGs. No SVG/HTML/Canvas/programmatic-art substitute, mockup, overview, UI, watermark, or leaked private route information.

## Override policy

Preserve explicit subject, mode set, output count, exact pixels or ratios, wallpaper relationship, copy mode, exact wording, locale, and intended meaning. User overrides may alter these variables but do not silently authorise abandoning source identity, the 050 aesthetic motive, fresh-task isolation, raster-only output, privacy, or verification. If the user explicitly requests a different aesthetic, acknowledge that it leaves this Skill's style rather than pretending it remains 050.

## References

- Read `references/xxd-panel-050-prompt.en.md` or `references/xxd-panel-050-prompt.zh-CN.md` immediately before generation.
- `references/050-source.md` archives the original style brief and is evidence, not an implicit 3:4 default.
