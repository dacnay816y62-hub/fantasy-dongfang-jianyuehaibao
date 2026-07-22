---
name: oriental-editorial-poster
description: "Create finished Chinese cultural, fantasy, and minimalist text-material editorial posters or publication covers with mandatory Image 2 style image generation. Use when a user gives a title, theme, exhibition/brand/cultural content, reference images, short keyword batches, ABC tests, or asks for 文字创意极简, fantasy text-driven visuals, 东方编辑海报, art-book covers, refined sparse poster tests, or culturally grounded Chinese typography posters. Supports v2 title refinement, real cultural evidence, Mode A direct creative image posters, Mode B steadier complete image-generated poster layouts, and A/B/C comparison batches; avoid generic AI Chinese-style posters."
---

# 东方文化编辑海报 v2

Treat this as a research-and-composition skill with mandatory image generation, not a generic one-prompt “Chinese-style poster” shortcut.

The goal is a contemporary editorial page that uses cultural evidence and material logic: real paintings, historical prints, artifacts, archival photography, calligraphy samples, book pages, material details, or generated reinterpretations that are clearly not presented as archival fact. In Mode A, image generation may create the whole poster with a more expressive image-title fusion. In Mode B, image generation still creates the whole poster, including title placement and typographic composition, but with a calmer publication-cover balance between text field, image evidence, and layout hierarchy.

Read [editorial-systems.md](references/editorial-systems.md) before composing.

For short keyword tests, quick batches, "fantasy", "文字创意极简", or outputs intended to match the user-approved sparse text-material examples, also read [fantasy-text-minimal.md](references/fantasy-text-minimal.md). That overlay is the default taste layer for fast 1-6 keyword poster batches: one strong material evidence field, one semantic title action, restrained text, one useful interruptor, no fake small text, and no generic Chinese decoration.

When judging taste or running ABC comparisons, inspect `v2-tests/selected-triptychs/selected-overview.jpg` first. It captures the current approved direction: refined short Chinese titles, a single cultural/material proof, one image-title relationship, and calm editorial space.

## v2 defaults from Image 2 testing

These rules supersede earlier broad "fantasy oriental" tendencies.

- Use Image 2 / image generation for actual poster tests; do not stop at prompt writing when the user asks for output images.
- When the user is testing Chinese text fidelity, asks to fix question marks/typos, or explicitly rejects post-added text, the visible H1 must be generated inside the image model pass. Do not add, replace, or correct the main title later with PIL, SVG, HTML/CSS, Photoshop, or any other layout fallback. If the title is wrong, simplify the prompt/title and regenerate.
- Prefer real, recognizable cultural evidence over invented cultural mashups: porcelain, silverwork, lacquer, garden windows, opera costume details, shadow puppets, city wall, grotto stone, archive maps, fabric, paper, waterline, patina, or craft marks.
- Refine the main Chinese title before prompting. The H1 should usually be 1-4 Chinese characters. Carry the longer topic through evidence, subtitle, English tag, or small copy.
- Do not over-explain with the title. For example, "徽州天井" can become "天井" when Huizhou is visible through architecture; "景德镇青花" should emphasize "青花瓷" or "青花" rather than forcing every proper noun into the H1.
- For abstract topics such as 乡愁, 婚姻, or 城市缩影, choose a tangible carrier first: threshold, ring, ledger, map fold, ticket, old wall, road trace, household object, or reflected surface.
- For place names such as 北京 or 山西大同, avoid landmark collage. Use one local material clue: hutong brick, map edge, wall section, grotto stone, roof ridge, sign shadow, or archival street fragment.
- Favor finished editorial posters over tourism posters, museum placards, guochao ecommerce graphics, cyberpunk wallpaper, or pure mood images.
- In batches, evaluate by complete groups, not isolated favorites. A good group has a coherent subject and three clearly different treatments.

## ABC test modes

Use A/B/C only when the user asks for tests, comparisons, or multiple directions.

| Mode | Name | Output logic |
| --- | --- | --- |
| **A** | 古图档案介入 | Use archive, rubbing, map, print, old paper, or historical-image logic. The title behaves like an inscription, specimen, crop, or archival interruption. |
| **B** | 单一物证 | Use one object or material as the visual boss. The title is restrained and the object carries the cultural identity. |
| **C** | 字体结构实验 | Let the title become a structure, mask, crop-window, relief, section, or frame. Keep it readable and avoid turning the whole subject into a literal giant glyph. |

For a five-topic ABC test, produce 15 images and save matching prompts. Also make a contact sheet or triptych view when the user needs review.

## Poster-first correction defaults

These defaults override any earlier tendency to make a single clever image.

- Treat the deliverable as a finished poster, cover, or publication page. The result must have layout hierarchy, real title placement, readable metadata rhythm, and poster-level composition. Do not let the generated image become the whole answer unless the user explicitly asks for a creative-image experiment.
- Decorative hairlines, dots, registration marks, circles, rulers, and random editorial ornaments are optional, not mandatory. Add them only when they clarify hierarchy, alignment, scale, or source logic. If they do not have a job, omit them.
- For intangible cultural heritage, city culture, regional identity, exhibitions, festivals, craft subjects, and any multi-character title or topic, default to **Mode B: image-generated poster layout** unless the user explicitly requests Mode A.
- In Mode B, the image model should generate the complete poster in one image-generation step, including the main title as part of the visual layout. The difference from Mode A is not whether text is generated; it is the text/image weighting: B should reserve a clearer title field, steadier hierarchy, and calmer poster structure, while A may fuse title and image more aggressively.
- Batch tests should use real topics, phrases, places, crafts, or cultural subjects, not isolated one-character titles, unless the user explicitly requests single-character tests.
- For test sets, use current, concrete, visually productive topics. Avoid odd invented nouns and false traditions.
- When a topic is hard to visualise faithfully, choose a conservative editorial layout: strong image crop, clear title block, restrained subtitle, one coherent copy line, and no forced image-text trick.

## Input contract

Accept natural-language content, however incomplete. Extract:

- title and subtitle;
- cultural subject, place, object, mood, or narrative;
- date, location, price, credits, publication issue, body copy, or bilingual copy;
- intended use and required ratio, if supplied.

Do not ask for missing content. Preserve all supplied proper nouns, numbers, dates, and wording. Omit unknown facts instead of inventing an institution, artist, quotation, date, translation, or historical claim.

Default to 3:4 vertical unless the user specifies another format.

The subject may be cultural heritage, a product, architecture, a person, a craft, a scientific object, food, a landscape, a material macro, or an abstract concept. Do not turn every subject into the same ink-and-paper visual language. The subject and supplied material determine the visual mechanism.

## Non-negotiable principle

Do **not** respond to the brief by generating a generic “oriental poster” in one image-model prompt.

However, every finished poster **must use image generation as a core production step**. A purely manual SVG, HTML/CSS, Photoshop, Figma, PIL, or layout-only result is not sufficient. The generated image may be a complete creative poster, original poster base, hero evidence reinterpretation, material field, or controlled visual plate, but the final delivered cover must visibly depend on a generated visual pass that was prompted from the editorial brief and reference analysis.

## Production modes

Let the user choose one of two production modes before generating whenever the mode is not already clear:

| Mode | Use when | Method | Tradeoff |
| --- | --- | --- | --- |
| **A. Direct image poster** | The user wants maximum visual creativity, fantasy text treatment, image-text fusion, or minimal editorial covers where the title is part of the image. | Generate the whole poster in one image-generation pass, including the major Chinese title as a designed visual form. Retouch, crop, or lightly post-process only after generation. | Stronger integration and stranger typography; weaker exact text control. |
| **B. Image-generated poster layout** | The user wants a finished poster with clearer text/image balance, multi-character cultural subjects, or a steadier publication-cover layout. | Generate the whole poster in one image-generation pass, including the main title and layout hierarchy, while keeping the title field calmer and more readable than Mode A. | More poster-like and coherent; still has model text risk, but avoids the later-added-template look. |

If the user explicitly chooses A or B, obey that choice. If they do not choose, ask one concise A/B question when feasible. If proceeding without asking, default to **A** for short creative titles and visual experiments, and **B** for exact text, long copy, dates, venues, prices, credits, or provenance-sensitive work.

After production mode is chosen, select a **text-reserve ratio**. This is the usable calm area reserved for real title, copy, or metadata, not meaningless empty background.

| Text reserve | Usable text field | Use when | Default behaviour |
| --- | --- | --- | --- |
| **Low / 12-22%** | Title is tightly integrated into the image; only a small label zone remains. | A-mode image-text fusion or one-word covers. | Material/image carries most of the page. |
| **Medium / 25-38%** | One clear title zone plus a compact copy or metadata group. | Most editorial posters. | **Default** when the user gives no preference. |
| **High / 40-55%** | A strong open field for longer title, body copy, or exact information. | B-mode factual covers, text-led briefs, or restrained catalogue pages. | Open field must contain intentional readable content or a defined future text zone. |

Ask for this choice immediately after A/B when feasible. If the user does not choose, let the LLM infer it from the supplied text amount and record the choice in working notes. Do not choose a high reserve merely because a short title needs a minimal cover.

Build the result in this order:

1. reference analysis (when reference images exist);
2. content hierarchy;
3. source-image plan;
4. real-source collection;
5. title-character collection;
6. title-design strategy;
7. editorial layout system;
8. production mode selection;
9. text-reserve ratio selection;
10. LLM concept divergence and semantic selection;
11. image-generation brief and prompt;
12. generated visual pass;
13. optional editable composition or typography correction;
14. final quality check.

## 0. Analyse references before designing

When the user provides a reference or selects a previous output, do not treat it as a template to recolour or re-title. First write a private **design grammar card**:

| Read | Record |
| --- | --- |
| hierarchy | which element is structural, readable, illustrative, and informational |
| type role | whether each title character is a frame, mask, label, specimen, or interruption |
| image role | whether imagery is evidence, a crop inside type, a trace, an object, or a field |
| geometry | axes, crop pressure, blank zones, rules, and reading path |
| rhythm | scale contrast, repeated marks, information density, and pauses |
| palette/material | source-led colours and why each texture belongs |

Then make a **variation contract** before composing. Preserve at most two or three principles from a reference; deliberately change at least three of: title role, title scale, image behaviour, primary axis, reading path, information rhythm, palette, crop logic, or editorial system.

Example: a reference may succeed because one glyph is a dark structural column, another is an image-mask, the readable title is small, and empty paper carries the rhythm. A new tea poster may keep the distinction between structural type and readable type, but must not automatically retain its left column, right mask, palette, or exact information block.

Never respond to “this one is good” by reproducing its layout with new content. State privately what is good about it, then choose a new composition that uses the insight in a subject-specific way.

## 1. Turn content into an editorial brief

Write a private one-sentence premise in this form:

> “[subject] is presented as [editorial attitude] through [specific cultural evidence].”

Then define the hierarchy:

| Layer | Use |
| --- | --- |
| H1 | Title, usually 2–8 characters. |
| H2 | Subtitle, issue name, or one short framing phrase. |
| Hero evidence | One researched image or object that carries the page. |
| Secondary evidence | One to three close crops, alternate scans, or related details. |
| Metadata | Date, location, edition, category, bilingual label, or credits. |
| Copy block | One coherent theme sentence or short paragraph that gives the small type a reason to exist. |
| Interruptor | A rule, crop, colour plate, page number, index, or document strip. |

Never let every layer shout. Establish one visual hierarchy and one reading path.

## 1A. Build a transferable minimal editorial grammar

Use this section for **every** subject, including non-cultural, commercial, technical, or abstract briefs. It captures the quality bar of refined minimal text-image covers without copying any supplied reference layout.

Before choosing colours or writing an image prompt, make a private `composition card` with exactly these fields:

| Field | Requirement |
| --- | --- |
| Primary evidence | One material, object, crop, trace, shadow, or image event only. |
| Title action | The title must perform a material-specific semantic action selected by the LLM concept gate in section 1B. A shadow, cutout, outline, crop-window, relief, measurement, reflection, silhouette, projection, or interruption is a possible result, not a preset. Never merely oversized text. |
| Dominant axis | Choose one: vertical, horizontal, diagonal, radial, or edge-pressure. |
| Text reserve | Use the selected Low, Medium, or High text-reserve ratio. State what readable title/copy/metadata it is for. It must not be an unexplained void. |
| Interruptor | One precise secondary event only: a thread, rule, colour bar, registration dot, edge, or small material trace. |
| Palette | Source-led neutrals plus at most one controlled accent; normally no more than three colours. |
| Material proof | Name the observable physical evidence: fibres, rust, grain, cast shadow, weave, machined edge, paper tooth, oxidation, condensation, stone, or another subject-specific trait. |
| Beauty engine | State the visual sensation, focal material/light, mass-to-void choreography, and colour climate that make the page desirable before the title is noticed. |

The title and the evidence must alter each other. Examples of transferable relationships:

- a tool or object throws a title-shaped shadow;
- a textile interrupts outlined letters;
- a photographed material occupies only a title stroke or crop-window;
- a title becomes a shallow emboss, measurement, reflection, or silhouette;
- a thread, waterline, architectural joint, wire, or rule cuts through a title;
- an edge crop makes the object and title share a boundary.

Do not reuse the same relationship twice in a row during tests or a series. The system is reusable because the relationship changes with the material, not because the same composition is recoloured.

## 1B. LLM concept gate: find a semantic mechanism before styling

Do this privately before every poster. The LLM must analyse the title, subject, supplied material, intended audience, and any references, then propose **six genuinely different concept candidates**. A candidate is not a visual effect. It must state:

1. `material fact`: one specific trait of the source, object, process, or idea;
2. `semantic pivot`: what the title means differently because of that trait;
3. `title mechanism`: how image and title become inseparable;
4. `why this cannot be swapped`: why the same mechanism would fail for an unrelated noun;
5. `text reserve`: Low, Medium, or High and what it will hold.

Score each candidate 1-5 for `material inevitability`, `semantic surprise`, `formal beauty`, `visual economy`, and `distance from the last five outputs`. Select only a concept with an average of at least 4, with `formal beauty` and `material inevitability` each scoring at least 4. If none clears the bar, develop six new mechanisms. Do not start image generation from a weak candidate.

Use this rejection question: **Could the same image treatment work unchanged if the title and subject were replaced by another random noun?** If yes, reject it as decorative or forced.

Then run an equally important aesthetic rejection question: **Would this still be a visually desirable editorial image if the title were hidden for one second?** If not, reject it. A mechanism is not creative when it turns the subject into a diagram, a rebus, or an object-shaped font.

### Beauty is not decoration

Do not trade visual beauty for a literal conceptual trick. The image must have a primary sensory pull before the title is decoded: a light condition, colour tension, material richness, crop pressure, rhythm, or a quiet counterweight. The title should sharpen that pull, reveal a second reading, or introduce a controlled disturbance. It must not become the entire subject.

Reject a concept when it does any of the following:

- turns architecture, objects, or people into huge literal glyph-shaped structures;
- uses embossing, cutouts, texture filling, or 3D lettering without an aesthetic reason beyond making text readable;
- makes a poster read as a diagram, puzzle, technical illustration, or AI key art rather than an editorial image;
- fills the frame with visual evidence but leaves no hierarchy, breathing rhythm, or focal beauty;
- reduces a living performance, city, or historical figure to its most obvious icon.

When a concept is semantically strong but visually dry, keep the semantic pivot and change the image language. For example, use the rhythm of a city section instead of buildings becoming letters; use the beauty of fabric in motion before allowing a title to emerge at one high-tension fold; use a route as a compositional current rather than paving every title stroke.

### Shadow is an exception, not a house style

Shadow typography is permitted only when all three are true:

- the supplied material naturally creates a distinctive cast shadow;
- the shadow changes the meaning of the title, rather than merely displaying it;
- it was not used in either of the two immediately preceding posters or more than once in the last five.

At most one of the six concept candidates may use a shadow. Do not use a shadow after it has been rejected in the concept gate. Prefer a mechanism rooted in the subject's process, failure, tension, structure, use, transformation, or cultural meaning.

Examples of semantic mechanisms, not templates:

- a weaving title is interrupted at the exact points where warp and weft exchange dominance, making the word behave like a weave rather than sitting on fabric;
- a kite title becomes a tension diagram whose strokes only hold together under pull from the string;
- a forged title is a negative space left by the tool action, not metal letters with decorative sparks;
- an archival title inherits omissions, folds, registration drift, or censored areas from a document rather than receiving an arbitrary vintage texture.

The LLM should articulate the chosen concept in one private sentence before composing: `This poster only works because ...`.

### Minimal editorial hard limits

- One hero object/material event per cover; a second image is permitted only as a small echo or crop.
- One title action, one dominant axis, and one interruptor. Do not combine multiple tricks.
- Do not apply a title to a material merely because the effect is technically possible. The title action must pass the semantic mechanism gate.
- The hero image must remain visually compelling when the title layer is mentally removed. Treat typography as a second reading, not the sole reason the picture exists.
- Do not construct giant buildings, props, cities, or objects as literal Chinese glyphs. Let the title arise from a subject-specific condition at a limited, meaningful moment.
- Do not add generic mist, ink splashes, seals, borders, collage scraps, decorative patterns, or pseudo-editorial filler to make an image feel designed.
- Do not generate a moodboard, mockup, product shot, festival scene, illustrative tableau, or social-media frame when the request is for a poster.
- Prefer edge pressure, real scale contrast, and deliberate blankness over decorative density.
- An elegant sparse cover must still show material proof. Empty space is structural, not an excuse for an underdeveloped image.

### Subject-to-mechanism routing

| Subject or source | Preferred evidence | Strong title actions |
| --- | --- | --- |
| tool, craft, machine, product | worn edge, mechanism, cast part, working surface | shadow, crop-window, measurement, silhouette |
| textile, paper, fiber, food | macro weave, fold, grain, stain, cut edge | outline, cutout, thread interruption, relief |
| architecture, city, landscape | joint, elevation, horizon, reflected plane, map trace | edge crop, projection, rule, image-inside-stroke |
| person, performance, fashion | silhouette, costume fold, gesture, stage light | shadow, negative-space cutout, cropped title plane |
| archive, writing, history | print fragment, rubbing, page edge, document mark | inscription, strip, specimen field, crop-window |
| nature, weather, sound, abstract idea | waterline, residue, cloud, vibration, light trace | reflection, trace, silhouette, interrupted outline |

These are routing cues, not templates. Change the title action, axis, crop logic, and palette whenever the subject changes.

If the user supplies no body copy, draft one original, non-factual thematic sentence or short paragraph before composing. It may evoke the subject, material, place, or mood, but must not invent dates, venues, historical claims, or other metadata.

## 2. Plan sources before looking for images

Choose evidence based on the content, not on a generic Chinese aesthetic:

| Content cue | Search for evidence such as |
| --- | --- |
| place / city | historical maps, local archive photography, architectural fragments, street documentation |
| painting / season / landscape | public-domain painting scans, album-leaf details, botanical or bird studies |
| craft / objects | museum collection photography, close material studies, workshop tools, illustrated manuals |
| text / publishing | stone rubbings, book pages, printing fragments, manuscript crops |
| music / theatre / performance | programme ephemera, costume/prop detail, stage diagrams, archival portrait fragments |
| contemporary brand / exhibition | one cultural object or material reference plus restrained original supporting imagery |

Plan one hero evidence item, one secondary detail, one background trace, and one optional generated gap-fill. Do not assemble a random moodboard.

## 3. Collect real visual evidence

Search online before generating imagery. Prefer collection pages from museums, libraries, archives, foundations, universities, or public-domain/open-access repositories. For every retained source, keep:

- a direct source page;
- title/object name and creator/period when provided;
- image/right status or uncertainty;
- a downloaded or captured working copy;
- a planned role: hero, crop, background trace, or detail.

Use existing historical imagery as **editorial evidence**: crop it, scale it, mask it, overprint it, screen it, or pair it with another scan. Do not claim a source is public domain when its status is unknown; avoid final commercial use of unclear assets.

Use only one or two primary image sources per page. Richness must come from crops and relationships, not from adding unrelated pictures.

## 4. Build the title from real calligraphy samples

For each Chinese title character:

1. Search a calligraphy-character dictionary such as [书法字典](https://www.shufa5.com/) or another credible character source, one character at a time.
2. Capture 3–5 candidates with their source page, script, and attribution when available.
3. Make a title-character board. Compare outer contour, stroke density, internal white space, directional energy, and resolution.
4. Select individual samples intentionally. A title may use one writer/work for unity or mix characters from different sources for a designed heavy/light cadence.
5. Isolate each selected glyph from its background; retain its original skeleton and natural imperfections.
6. Compose the title from these actual character layers. Do not ask an image model to “write calligraphy.”

Use calligraphy only where it earns a role. For a formal catalogue cover, a Song/Ming title may be stronger. Keep body, dates, place, and English in crisp modern typesetting.

If reliable samples cannot be collected, use Song/Ming or Heiti. Never use fake AI brush lettering as a fallback.

## 5. Select a title-design strategy

Title design must not default to "one huge cropped title" for every brief. Choose one strategy before composing:

| Strategy | Use when | Form |
| --- | --- | --- |
| Edge monument | short, forceful titles | one or two large cropped characters create the structure |
| Quiet catalogue | refined cultural subjects | small or medium title with image/object as dominant evidence |
| Split inscription | text, archive, publishing | title is broken into columns, strips, annotations, and sampled glyphs |
| Type specimen | font/calligraphy/AI/design themes | multiple controlled title variants become the content |
| Object label | craft, food, fashion, product-like subjects | restrained title behaves like a museum label around a strong object crop |
| Text field | literary, city, document-heavy subjects | many small title repetitions, bilingual marks, and metadata create rhythm |

For batches or iterative tests, rotate strategies. Do not produce more than two consecutive posters using Edge monument. If the previous output used a giant cropped title, the next output must use Quiet catalogue, Split inscription, Object label, or Text field.

If a previous design used image-inside-type, do not assume the next title needs a type mask. Image inside type is a relationship, not a house style: choose it only when the source has meaningful interior texture and the title benefits from becoming a frame.

The title should show design intent through at least two of these: scale contrast, glyph substitution from a real sample, stroke cropping, baseline/grid shifts, vertical/horizontal tension, image clipped into selected strokes, repeated micro-title, or a deliberate blank around the title. Avoid treating "font design" as merely enlarging a Song/Ming character.

## 6. Select one editorial system

Select exactly one system from [editorial-systems.md](references/editorial-systems.md). Do not combine every reference effect.

Each poster must include:

- one hero evidence field;
- one secondary crop, enlarged detail, or ghosted trace;
- title layer;
- a real metadata group or a deliberately blank archival label zone;
- one interruptor.

Do not default to black brush lettering, torn paper, red seals, grunge, or ink splashes. Every texture must come from an identifiable source logic: silk scan, printing plate, rubbed stone, paper edge, material macro, or archive photograph.

## 7. Mode B corrected composition rule

This rule supersedes any older wording that describes Mode B as "generate a base first, then add real typography." That older interpretation makes the result look like a post-composited layout template and should not be the default.

For **Mode B**, the image-generation step must still produce the finished poster, including the main title, title placement, image placement, and overall visual hierarchy. The difference from Mode A is the **ratio and discipline** of text to image:

- Mode A may fuse title and image aggressively, producing stranger title-form experiments.
- Mode B should keep the title field clearer, the poster hierarchy steadier, and the image/text balance calmer, while still generating them together in one image pass.
- Do not generate a blank visual base and add a separate information bar afterward unless the user explicitly asks for exact production typography.
- In B prompts, ask for one clear main title, no long small text, no fake metadata, no pseudo-labels, no QR codes, and no invented event information.
- Decorative hairlines, dots, circles, registration marks, and grids remain optional. Omit them unless they have a real compositional job.
- If exact factual text is later required, perform a minimal correction pass after the generated poster exists; that is a finishing fallback, not the definition of Mode B.

## 7B. Exact-text finishing fallback

Use a layout-native method—SVG, HTML/CSS, Photoshop, Figma, or another editable composition tool—only when the user needs exact factual typography, a production-ready file, or corrections after a generated poster exists. This is a finishing fallback, not the default definition of Mode B.

- This fallback is forbidden when the user says the text must be completed inside image generation, when the deliverable is a raw image-generation text-fidelity test, or when the problem being tested is garbled Chinese, question marks, or wrong characters. In those cases, regenerate the poster natively instead of post-correcting the H1.
- Keep H1, H2, dates, locations, and all supplied text exact in fallback finishing.
- Use hard crops and deliberate edge pressure; avoid “image left, title right” unless the selected system requires it.
- Create variation through scale: hero crop, micro-detail, large title, small metadata, and one tiny mark.
- Replace isolated decorative microtype with one coherent copy block: a supplied sentence, sourced caption, or a short original thematic line tied to the subject. Keep it to roughly 8–35 Chinese characters or 1–3 short lines. If English is included, translate or label the same idea; never add unrelated pseudo-English.
- Use no more than four colours. Let source colours lead; add only one controlled accent.
- Do not create decorative pseudo-Chinese, invented seals, QR codes, fake museum labels, or filler English.
- Keep the source imagery recognisable as a printed/archival object, but never reproduce a whole source image untouched when a crop conveys the idea more clearly.

For **Mode A**, the generated image may be the final composition. Post-process only to crop, upscale, remove obvious artifacts, or add a small exact caption if the user requests it. Do not flatten Mode A back into a conventional typeset poster unless the user asks to switch to Mode B.

## 8. Use image generation as a mandatory production pass

Use an image-generation tool for every poster. This is a hard requirement, not an optional enhancement.

The generated pass must follow the selected production mode.

### Mode A: direct image poster

Generate the whole poster directly. Prompt the image model to treat the main Chinese title as a designed visual object integrated with the subject, material, crop, shadow, mask, or image structure.

Use Mode A for outputs like bold single-character posters, giant type-as-object, material inside strokes, shadow typography, typographic silhouettes, or minimal covers where the title and image are inseparable.

Mode A rules:

- Keep the title short whenever possible, ideally 1–4 Chinese characters.
- Include the exact target title in the prompt, but accept that the generated title is a visual artifact with higher text-risk than Mode B.
- Inspect the output. If the core title is unreadable, wrong, or visually broken, regenerate with a simpler title prompt or switch to Mode B.
- Do not use Mode A for long copy, exact metadata, dates, prices, credits, or factual labels.
- Avoid fake seals, pseudo-Chinese filler, QR codes, invented institutional names, and random small text.

### Mode B: complete image-generated poster layout

Generate the complete poster layout in one image-generation pass, including main title placement, image placement, text reserve, and overall hierarchy. Mode B is calmer and more publication-like than Mode A, but it is still an image-generated poster, not a blank base waiting for pasted typography.

The generated pass may be:

- an original full-poster visual with a clear title zone and readable H1;
- an original hero material/object study integrated with typography and hierarchy;
- an atmospheric paper, silk, rubbing, textile, shadow, grain, or archive field that still resolves as a poster;
- a controlled poster plate with deliberate text reserve and minimal real copy;
- a generated reinterpretation of user-provided references that changes composition, crop logic, palette, subject behaviour, and reading path enough to avoid copying.

Before generating, write a compact image-generation brief containing:

- subject and editorial premise;
- selected editorial system;
- preserved reference principles, limited to two or three;
- required structural changes for copyright and variation;
- palette and material logic;
- production mode A or B;
- selected text-reserve ratio and its intended text content;
- chosen LLM concept sentence and the rejected generic alternatives;
- beauty engine: desired sensation, focal material/light, mass-to-void choreography, and colour climate;
- forbidden elements, including fake seals, pseudo-Chinese filler, copied photo composition, invented historical claims, and mode-inappropriate text.

For either mode, append the `composition card` from section 1A to the working brief. The image prompt must explicitly state the primary evidence, title action, dominant axis, amount of empty field, interruptor, palette, and material proof. Reject prompts that only name a style, genre, or mood without defining this visual relationship.

In Mode B, do not prefer generating a blank poster base. If the model mangles important wording, perform the exact-text finishing fallback after the generated poster exists, or simplify the title and regenerate.

Never ask the image model to invent factual metadata, museum labels, archival provenance, QR codes, institutional names, or copied classical paintings. In Mode A, generated title-forms are allowed as creative typography; in Mode B, title calligraphy must use real character samples or Song/Ming/Heiti fallback after generation.

## 9. Final quality gate

Before delivery, verify:

- The page reads as an independent cultural publication, not an AI “new Chinese” template.
- The production mode is recorded as A or B in working notes.
- Any real source imagery is traceable in working notes and used in a deliberate crop/relationship; any generated imagery is clearly treated as generated, not archival evidence.
- In Mode A, the generated title-form is visually intentional and close enough to the requested core title to be usable; regenerate or switch to B if the core title is wrong, garbled, or unreadable.
- In Mode B, the H1 is readable and intentional; when exact factual text is required, corrected title glyphs are real samples or explicitly typeset fallback, not synthetic brush characters.
- The chosen title-design strategy is not repeating the previous poster's structure unless the user explicitly asked for a series.
- If a reference was supplied, the result reuses its design logic rather than its positional template; the variation contract changes at least three structural choices.
- The page has image hierarchy, title hierarchy, metadata rhythm, and one interrupting editorial device.
- The composition card names the selected text-reserve ratio and what readable content occupies it; no poster reads as unfinished because its blank zone has no job.
- The LLM concept sentence explains why the image-title relationship only works for this subject. If the mechanism could be swapped unchanged onto another random noun, reject and regenerate before delivery.
- The beauty engine can explain why the image is aesthetically desirable before its title is decoded. If it reads as a diagram, rebus, technical illustration, or literal object-font, reject and regenerate.
- The title intensifies the hero image at one meaningful condition and does not consume the image as a giant shaped structure.
- A shadow title satisfies all three exception rules in section 1B; otherwise reject it.
- The output is sparse by construction, not empty by omission: the hero material/object is convincingly observed at a meaningful crop and scale.
- The result does not depend on an ink-and-paper, red-seal, giant-calligraphy, or generic cultural-poster shortcut when the subject does not call for it.
- A supplied reference has been reduced to transferable relationships rather than copied coordinates, title placement, object crop, palette, or information blocks.
- Richness comes from image-text relationships, not from a universal dirt/grunge overlay.
- No isolated unexplained microtext remains. In Mode A, suppress random generated small text; in Mode B, every small text group is a coherent sentence, short paragraph, sourced caption, or exact metadata.
- In Mode B, all user-provided wording and factual details are exact; in Mode A, do not use generated text for factual claims, dates, venues, prices, or credits.
- The output is a single clean poster/cover, no mockup or social-app frame.

Return the finished visual. Keep a compact source list and title-character record with the working files; show it if the user requests provenance or wants to reuse the layout.
