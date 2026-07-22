# Fantasy Text-Minimal Overlay

Use this overlay when the user asks for keyword tests, fast batches, ABC comparisons, "文字创意极简", "fantasy", or poster outputs similar to the approved examples in `assets/reference-good/`.

First inspect `assets/reference-good/fantasy-text-minimal-contact-sheet.jpg` when matching taste matters. Load individual images from `assets/reference-good/` only if the contact sheet is not enough.

For the v2 Image 2 direction, inspect `v2-tests/selected-triptychs/selected-overview.jpg` when available. The selected triptychs show the preferred balance: short H1, one material proof, a real cultural carrier, and a readable A/B/C difference.

## Taste Summary

The approved direction is not generic "Chinese style". It is a refined text-material cover system:

- one high-tension physical evidence field;
- one readable title action;
- one quiet text reserve;
- one useful interruptor;
- source-led neutrals plus at most one accent;
- severe crop pressure and deliberate blankness.

Good evidence examples: wet stone, bronze patina, cracked lacquer, torn paper, silk thread, porcelain fracture, salt grain, pagoda brick, winter lotus fiber, wafer grid, water reflection, city wall, instrument strings, sugar gloss, Taihu stone holes.

Approved v2 evidence examples: lacquer shadow, marriage ring/string, celadon glaze, salt field, bronze ridge, Miao silver, Suzhou garden window, Peking opera costume, shadow puppet leather, Tibetan carved/painted surface, Beijing hutong wall, Datong grotto stone.

## Fast Batch Defaults

For 1-6 short keywords, proceed without asking:

- ratio: 3:4 vertical;
- quality: medium for speed tests, high for final selected outputs;
- mode: Mode B-like complete poster layout for multi-character topics, Mode A only when the title is short and the material-title fusion is the point;
- text reserve: medium unless the subject clearly needs a quiet catalogue field;
- image tool priority: prefer the host-native built-in `img` / `image_generation` tool when it is available; use Garden/API generation only when no built-in image tool is exposed;
- output: save images to the user-configured output root, for example `<OUTPUT_ROOT>\images`; save prompts to `<OUTPUT_ROOT>\drafts`.

## v2 Title Refinement

Before prompting, compress the topic into a stronger visible H1.

- Use 1-4 Chinese characters for the main title whenever possible.
- Let subtitle, English tag, small copy, and visual evidence carry the full place/craft context.
- Prefer `天井` over `徽州天井` when Huizhou is visible in the architecture.
- Prefer `青花瓷` or `青花` over a long `景德镇青花...` construction when porcelain evidence already implies Jingdezhen.
- Keep `苗银`, `皮影`, `京剧`, `北京`, `大同`, `婚姻`, and `漆影` direct and legible; do not bury them inside poetic compound titles.

Reject long literal H1 strings when a shorter title will read harder and the evidence can do the explaining.

## ABC Comparison Defaults

When the user asks for A/B/C tests:

- `A`: 古图档案介入. Use archival field, rubbing, map, old paper, print, or historical-image logic.
- `B`: 单一物证. Use one object or material as the visual boss; keep title calmer.
- `C`: 字体结构实验. Let title become a frame, crop-window, relief, mask, section, or structural interruption.

Keep all three treatments for a topic recognizably related, but make the title action different enough that review is meaningful. After generation, arrange each topic as one triptych with A/B/C labels so the user can judge the group quickly.

## Composition Card

Before each prompt, decide these fields:

- `primary evidence`: one object/material/image event only;
- `title action`: reflection, interruption, label, measurement, specimen, shadow, relief, crop-window, thread, waterline, map coordinate, or inscription;
- `axis`: vertical, horizontal, diagonal, radial, or edge-pressure;
- `text reserve`: low 12-22%, medium 25-38%, or high 40-55%;
- `interruptor`: one line, dot, thread, edge, map trace, waterline, route, or colour plate;
- `palette`: neutrals plus at most one accent;
- `material proof`: fibers, patina, stone pores, lacquer cracks, water, dust, thread, wafer grid, etc.;
- `beauty engine`: why the image is desirable before reading the title.

Reject a concept if the same title action could work unchanged for an unrelated keyword.

## Layout Systems

Choose exactly one.

### Quiet Catalogue

For objects, craft, stones, instruments, food, tools, AI hardware.

- Hero crop: 45-70%.
- Title: small or medium, near a quiet field.
- Mechanism: label, measurement, reflection, relief, or material interruption.

### Document Field

For cities, history, poetry, publishing, archive, map, architecture.

- Hero: document strip, map trace, rubbing, wall, or architectural crop.
- Title: coordinate, specimen, vertical inscription, or measured label.
- Mechanism: map line, torn edge, registration drift, or section mark.

### Night Material

For music, water, fashion, performance, dark materials.

- Hero: one lit fragment against a deep black field.
- Title: pale and restrained.
- Mechanism: reflection, thin light, shadow, string, or waterline.

### Thread / Line Tension

For textiles, instruments, kites, routes, strings, cracks.

- Hero: diagonal or taut line crossing a material field.
- Title: interrupted by the line, completed by glints, or aligned to tension.

### Water / Reflection

For places, weather, poetry, lotus, night, harbor, memory.

- Hero: water surface, reflection, ice edge, or wet ground.
- Title: reflected, broken, or softened by water.
- Interruptor: one waterline or ice line.

## Rotation Rules

For batches, rotate mechanisms:

- one reflection/waterline;
- one measurement/specimen label;
- one material interruption;
- one image-inside/crop-window or relief;
- one quiet catalogue/object label.

Do not use more than two consecutive giant-title posters. Do not use shadow more than once in a batch unless requested.

## Text Rules

Keep text minimal:

- H1: exact user keyword;
- English label: optional literal label, 1-3 words;
- copy line: optional, poetic but non-factual;
- metadata: only if supplied by user.

Never invent real dates, venues, institutions, quotes, collection numbers, artist credits, or historical claims.

## Common Failures

- fake dense microtype;
- red seal as automatic cultural sign;
- huge title with no material reason;
- beautiful object photo with title pasted on top but no relationship;
- buildings, props, or people shaped as giant Chinese glyphs;
- generic ink, mist, tourist nostalgia, or cyberpunk wallpaper.
- invented cultural hybrids, fake traditions, or strange nonexistent subjects;
- overlong titles that explain the culture instead of letting the evidence show it;
- reviewing isolated single images when the actual task is an A/B/C group comparison.
