---
name: ecommerce-master-skill
description: Unified e-commerce strategy, visual direction, image prompting, and quality-control workflow. Automatically routes furniture and medical topical products to specialized modes while keeping shared commercial and visual methodology.
---

# E-commerce Master Skill

## Mission
Turn product facts/images and visual references into a coherent, conversion-focused e-commerce campaign. The commercial layer decides **what to communicate**; the visual layer decides **how to prove it**.

## Automatic category routing
Choose the specialist mode before planning. Never mix specialist rules when they conflict.

### Furniture Detail Page Mode
Trigger on: 家具详情页、淘宝家具详情页、天猫家具详情页、制作家具主图+详情页、启动家具电商详情页模式、家具主图、家具详情页、using ecommerce-master-skill for furniture.

Enable:
`references/furniture-product-lock.md` + furniture section below.

### Medical Topical Detail Page Mode
Trigger on: 医药详情页、药膏详情页、软膏详情页、乳膏详情页、凝胶详情页、喷剂详情页、贴膏详情页、贴剂详情页、医疗器械详情页、医药主图+详情页、医疗健康产品电商详情页、医药外用详情页、启动医药外用详情页模式、medical-topical-ecommerce-skill.

Enable:
`medical-topical-skill/SKILL.md` as the specialist rule set.

### General E-commerce Mode
Use when neither specialist route applies.

### Ambiguous product
If category is unclear, do not guess a regulated status. Use general e-commerce rules plus conservative claim handling until the product category/status is established.

## Shared operating doctrine
**Product/regulatory truth > commercial clarity > visual proof > aesthetics.** Never beautify by changing the product or inventing claims.

## End-to-end workflow
1. Input routing
2. Product Truth Lock
3. Regulatory/Claim Lock when relevant
4. Commercial Strategy
5. Campaign Style Lock
6. Visual DNA
7. Message → Picture Pattern
8. Picture Solo Test
9. Unified 5-head + 10-detail storyboard by default
10. ONE Approval Gate
11. Production prompts
12. Generation
13. Product + compliance + visual QA

## Shared planning outputs
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
- Set-level diversity/product-presence checks

### Unified approval board columns
Each H01-H05 and D01-D10 row should include:
**role | message | source | pattern | Picture Solo Statement | main visual | scene | subject | composition | product exposure | draft consumer copy | claim boundary | DNA carried**.

Only after this board passes may prompts be written, unless the user explicitly asks to skip approval.

## Furniture specialist rules
When Furniture Detail Page Mode is active:
- D01 hero + product memory
- D02 buyer scene / space problem
- D03 strongest functional/structural point
- D04 material/finish proof
- D05 storage/capacity/usability
- D06 real-life placement/use
- D07 dimensions/scale/spatial fit
- D08 craft/hardware/structure
- D09 service/packaging/quality/factual trust
- D10 closing lifestyle + decision reason

Lock silhouette, width/height/depth proportions, door/drawer/grid count, glass/openings, hardware, legs/base, material/finish, color, construction details, camera angle and perspective. Product replacement preserves the target scene camera; never stretch, narrow, rotate, redesign, add or remove structural elements merely for composition.

Furniture operation modes: product replacement, scene change, view change, close-up, scene expansion, material change. Each changes only what the user explicitly requests.

## Head-image rules
Default 5 roles: H01 click/main; H02 selling A; H03 selling B; H04 selling C/practical value; H05 audience/persona.
- H01 square 1:1 unless marketplace requires another ratio.
- At least 4 of 5 main visuals distinct.
- H02-H05 use different proof patterns.
- No single reference-scene element in more than 1 of 5 unless scene-locked.

## Detail-page rules
- Default 10 roles adapted by specialist mode.
- Strict 3:4 vertical by default.
- At least 7 of 10 main visuals distinct.
- At least 4 of 10 use no packaging or partial product exposure when appropriate to category.
- Detail pages must not become vertical copies of H01.
- User-provided fixed screen structures override defaults.

## Picture Solo Test
For every output write:
> The picture is [concrete visible scene]. With all text hidden, a buyer looking for 2 seconds would understand [specific message].

If the picture needs the headline to communicate the selling point, redesign it.

## Product-presence rule
Packaging/product exposure is chosen by message. Hero/closing may use full product; operation medium/partial; detail/parameter partial; lifestyle small/medium/none; material/sensory/mechanism proof often none.

## No-icon rule
No decorative icon grids, pictograms, checkmark rows, ingredient bubbles, feature-icon systems or fake badges as substitutes for evidence.

## Consumer copy rule
Write from the buyer's perspective: what they get, feel, experience or stop worrying about. Avoid manufacturer/spec-sheet language and empty superlatives. Apply the “so what?” test.

## Reference rule
References provide visual language: light behavior, typography attitude, density, commercial temperature, module rhythm and creative method. They do not automatically provide scene elements, props, brands, people, claims, prices or exact colors. Cap a single reference-scene element at 30% of outputs unless explicitly scene-locked.

## Color rule
Priority: user brand colors → product identity/material → category fit → product legibility → reference color relationships. Never blindly copy a reference hue that conflicts with product identity.

## Human/model rule
Use people only when they prove use, fit, scale, emotion, audience or credibility. Keep recurring model identity consistent while varying pose/action. Product interactions must be physically plausible.

## Prompt contract
Every prompt contains: goal, exact product lock, message, Picture Solo Statement, proof pattern, main subject, product exposure, composition, camera/view, lighting, materials, environment, human action if needed, approved consumer-facing copy, adapted palette, reference DNA, output ratio, and explicit negative constraints.

## QA gates
### Per-image
Product fidelity; structure; perspective; materials/color; human plausibility; copy/text; claim safety; proof fit; product exposure; reference DNA; ratio; commercial finish.

### Set-level
5-image diversity ≥4; 10-screen diversity ≥7; scene cap ≤30%; no icons; consumer voice; detail ≠ vertical head image; model continuity; color continuity; claim consistency; independent final files.

### Medical specialist QA
Additionally verify product category/status, every efficacy statement, ingredient/component, dosage/use instruction, registration/filing/approval information, warnings/contraindications, medical imagery implications, before/after implications, authority/endorsement implications and comparative claims. If evidence is absent, downgrade to visible fact/neutral education or remove.

## Failure handling
- Prompt-only: strengthen prompt.
- Skill-rule: patch relevant specialist/reference rule.
- Generator limitation: record blocker rather than inventing a workaround that changes product truth.
- Input limitation: use conservative visible/category-generic wording.

## Default interaction
Ask only questions that materially change strategy, product truth, regulatory status, model source or compliance. If the user explicitly says proceed/skip review, proceed while documenting assumptions.

## References
Shared:
- references/input-routing.md
- references/reference-analysis.md
- references/visual-dna.md
- references/color-adaptation.md
- references/visual-proof-grammar.md
- references/message-picture-patterns.md
- references/head-images.md
- references/detail-pages.md
- references/production-loop.md
- references/furniture-product-lock.md
- references/compliance-rules.md

Medical specialist:
- medical-topical-skill/SKILL.md
- medical-topical-skill/README.md
