---
name: ecommerce-master-skill
description: Unified e-commerce strategy, visual direction, image prompting, and quality-control workflow. Combines commercial copywriting strategy with visual production, with special safeguards for furniture and physical-product accuracy.
---

# E-commerce Master Skill

## Mission
Turn product facts/images and visual references into a coherent, conversion-focused e-commerce campaign. The commercial layer decides **what to communicate**; the visual layer decides **how to prove it**.

## Trigger modes
Activate the relevant mode when the user's request clearly matches it:
- **Furniture Detail Page Mode**: “家具详情页”, “淘宝家具详情页”, “天猫家具详情页”, “制作家具主图+详情页”, “启动家具电商详情页模式”, or “使用 ecommerce-master-skill 做家具详情页”.
- **General E-commerce Mode**: other product main-image/detail-page requests.
- If the user explicitly names `ecommerce-master-skill`, activate it even without a trigger phrase.

When Furniture Detail Page Mode is activated, automatically enable the furniture/structured-product rules below and default to a furniture-oriented 5-head + 10-detail plan unless the user specifies another count.

## Operating doctrine
**Product truth > commercial clarity > visual proof > aesthetics.** Never beautify by changing the product.

## End-to-end workflow
1. **Input routing** — classify information as complete, partial, or image-only. Inspect product/reference roles.
2. **Product Truth Lock** — lock visible structure, dimensions/proportions, materials, colors, packaging text, and supplied facts. Surface conflicts rather than guessing.
3. **Commercial Strategy** — identify target buyer, purchase motivation, anxiety/objection, conversion driver, prioritized selling points, and Feature → Benefit → Evidence.
4. **Claim Safety** — classify claims as visible, category-generic, user-provided/evidenced, or unsupported. Remove or soften unsupported claims.
5. **Campaign Style Lock** — define commercial genre, color relationship, typography attitude, layout rhythm, light/material world, camera language, emotional temperature and what must not drift.
6. **Visual DNA** — treat references as language, not scene. Borrow light, type, density, mood and layout logic; do not blindly copy scene, props, brand, people, claims or colors.
7. **Visual Proof** — for every output, select the strongest message-to-picture pattern and pass the Picture Solo Test before writing prompts.
8. **5 + 10 Unified Storyboard** — default to 5 marketplace head images + 10 detail screens. Preserve any user-defined screen structure. Enforce diversity and product-presence rules.
9. **ONE Approval Gate** — show the complete 5+10 planning board together. Do not ask for duplicate strategy/visual approvals.
10. **Production Prompts** — after approval (or explicit skip), write one complete prompt per independent output.
11. **Generation + QA** — generate, validate product accuracy, proof fit, typography, claims, ratio, reference DNA, model consistency and set-level diversity; regenerate failures.

## Furniture Detail Page Mode
When active, use a furniture-first content hierarchy:
- D01: hero + product memory
- D02: buyer scene / space problem
- D03: strongest functional or structural selling point
- D04: material / finish proof
- D05: storage / capacity / usability proof
- D06: real-life placement or use
- D07: dimensions / scale / spatial fit
- D08: craft / hardware / structural detail
- D09: service / packaging / quality / factual trust proof
- D10: closing lifestyle + product decision reason

For furniture main images, prioritize: H01 product recognition/click, H02 strongest differentiator, H03 structure/material proof, H04 use/space-fit proof, H05 target-home persona. Never force all five to show the whole cabinet.

### Furniture visual locks
Lock silhouette, width/height/depth proportions, door/drawer/grid count, glass/openings, hardware, legs/base, material/finish, product color, construction details, camera angle and perspective. If replacing a product into another scene, preserve the requested scene camera and fit the product to it. Do not stretch, narrow, rotate, redesign, add/remove structural elements, or alter material to improve composition.

### Common furniture-specific modes
- **Product replacement**: replace only the requested product; preserve scene camera, requested props and scene structure.
- **Scene change**: change wall/floor/bed/props/model while keeping the product locked.
- **View change**: generate front/left/right/45-degree views while preserving product geometry.
- **Close-up**: crop into actual material/structure without inventing construction.
- **Scene expansion**: extend environment while preserving original product scale and perspective.
- **Material change**: change only the explicitly requested material/finish; preserve geometry.

## Required planning outputs
Before generation, provide:
- Product Truth Lock
- Information route
- Selling-point bank
- Consumer-angle map
- Claim-safety boundaries
- Campaign Style Lock
- Visual DNA contract
- Product-use plausibility map when people/actions appear
- Product-first color system
- 5-image diversity board
- 10-screen diversity board
- Set-level diversity / scene-cap / product-presence checks

### Unified approval board columns
Each H01-H05 and D01-D10 row should include:
**role | message | source | pattern | Picture Solo Statement | main visual | scene | subject | composition | product exposure | draft consumer copy | claim boundary | DNA carried**.

Only after this board passes may prompts be written, unless the user explicitly asks to skip approval.

## Head-image rules
- Default 5 roles: H01 click/main; H02 selling A; H03 selling B; H04 selling C/practical value; H05 audience/persona.
- H01 is square 1:1. If a clear first-head reference exists, follow its layout skeleton while replacing product, copy, claims, brand and incompatible colors.
- H02-H05 must prove different messages with different visual patterns.
- At least 4 of 5 head images must have distinct main visuals.
- No reference-scene element in more than 1 of 5 outputs unless explicitly scene-locked.

## Detail-page rules
- Default 10 roles: D01 hero; D02 pain/scene; D03-D05 selling points; D06 usage; D07 practical; D08 detail/parameter; D09 trust; D10 closing.
- Strict 3:4 vertical by default, not 9:16.
- At least 7 of 10 main visuals must be distinct.
- At least 4 of 10 should use no packaging or partial product exposure.
- Detail pages are content-led and must not be vertical copies of H01.
- If the user provides fixed screen directions, preserve them.

## Picture Solo Test
For every output write:
> The picture is [concrete visible scene]. With all text hidden, a buyer looking for 2 seconds would understand [specific message].

If the picture needs the headline to communicate the selling point, redesign it.

## Product-presence rule
Packaging/product exposure is chosen by message, not habit. Hero/closing can use full product; operation can use medium product; detail/parameter can use partial product; scene/lifestyle can use small/medium or none; material, ingredient, sensory and mechanism proof commonly need no packaging.

## No-icon rule
Never generate icons, pictograms, checkmark rows, ingredient bubbles, feature-icon grids, badge ribbons or decorative feature-arc systems. The visual itself must carry the proof.

## Consumer copy rule
Write from the buyer's perspective: what they get, feel, experience or stop worrying about. Avoid manufacturer/spec-sheet language and empty superlatives. Apply the “so what?” test to every headline.

## Reference rule
Reference images provide visual language: light behavior, typography attitude, density, commercial temperature, module rhythm and creative method. They do not automatically provide scene elements, props, brands, people, claims, prices or exact colors. Cap any single reference-scene element at 30% of outputs unless the user explicitly requests a scene lock.

## Color rule
Priority: user brand colors → product identity/material → category fit → product legibility → reference color relationships. Never blindly copy a reference hue that conflicts with the product.

## Human/model rule
Use people only when they prove use, fit, scale, emotion, audience or credibility. When a recurring model appears, keep identity consistent while varying pose/action. Translate reference poses into physically plausible interactions with the actual product.

## Prompt contract
Every prompt contains: goal, exact product lock, message, Picture Solo Statement, proof pattern, main subject, product exposure, composition, camera/view, lighting, materials, environment, human action if needed, consumer-facing copy, adapted color palette, reference DNA, output ratio, and explicit negative constraints.

## QA gates
### Per-image
Product fidelity; structure; perspective; materials/color; human plausibility; copy/text; claim safety; proof fit; product exposure; reference DNA; ratio; commercial finish.

### Set-level
5-image diversity ≥4; 10-screen diversity ≥7; scene cap ≤30%; detail packaging mix ≥4 none/partial; no icons; consumer voice; detail ≠ vertical head image; model continuity; color continuity; claim consistency; independent final files.

## Failure handling
Classify failure as:
- **Prompt-only** — rule exists; strengthen prompt.
- **Skill-rule** — rule missing/weak/contradictory; patch the relevant reference.
- **Generator limitation** — repeated generation cannot satisfy the requirement; record blocker rather than using deterministic local repair for final visuals.
- **Input limitation** — facts/assets missing; use conservative visible/category-generic wording.

## Default interaction
Ask only questions that materially change strategy, product truth, model source or compliance. Do not repeatedly block the workflow for optional information. If the user explicitly says to proceed or skip review, proceed while documenting assumptions.

## References
Read only what the task needs:
- `references/input-routing.md`
- `references/reference-analysis.md`
- `references/visual-dna.md`
- `references/color-adaptation.md`
- `references/visual-proof-grammar.md`
- `references/message-picture-patterns.md`
- `references/head-images.md`
- `references/detail-pages.md`
- `references/production-loop.md`
- `references/furniture-product-lock.md`
- `references/compliance-rules.md`
