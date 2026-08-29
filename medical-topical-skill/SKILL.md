---
name: medical-topical-ecommerce-skill
description: E-commerce visual and copywriting workflow for topical medical/healthcare product categories such as ointments, creams, gels, sprays, patches and plasters. Prioritizes product truth, regulatory-safe claims, clear consumer education, and conversion-focused visual proof.
---

# Medical Topical E-commerce Skill

## Scope
Use for topical healthcare/medical-product e-commerce including ointments, creams, gels, sprays, patches/plasters, topical liquids and similar products. The exact regulatory category must be established from supplied packaging, registration/filing information, instructions, or authoritative product documents before making efficacy claims.

## Core doctrine
**Regulatory truth > product truth > consumer clarity > visual proof > aesthetics.** Never use visual polish to manufacture medical efficacy.

## Trigger phrases
Activate when the user asks for:
- 医药详情页
- 药膏详情页
- 软膏详情页
- 喷剂详情页
- 贴膏/贴剂详情页
- 医疗器械详情页
- 医药主图+详情页
- 医疗健康产品电商详情页
- 使用 medical-topical-ecommerce-skill

## Required input routing
Prioritize:
1. Product packaging/front/back images
2. Instructions/label/leaflet
3. Registration/filing/approval information if applicable
4. Ingredient or active-component information when legally permitted and supplied
5. Usage method, applicable population, contraindications and warnings
6. Platform and target market
7. Brand identity and visual references

If the product category or regulatory status is unclear, do not guess. Use neutral visible-product language and flag the uncertainty.

## Product Truth Lock
Lock:
- product name
- dosage/form (ointment, cream, gel, spray, patch, etc.)
- packaging structure and label text
- volume/net weight/count
- color, container, nozzle, tube, patch shape and package geometry
- ingredient/component information exactly as supplied
- usage method exactly as supported
- registration/filing information exactly as supplied
- warnings and contraindications

Never invent a drug/medical-device status, approval number, efficacy rate, treatment outcome, active ingredient, dosage, mechanism or clinical evidence.

## Claim architecture
Classify every proposed claim:
- **A — visible fact:** directly visible on packaging/product or obvious from the supplied product.
- **B — supplied factual claim:** explicitly supported by official product materials supplied by the user.
- **C — category education:** neutral educational information that does not imply this product treats a condition.
- **D — regulated efficacy claim:** requires authoritative substantiation and correct regulatory wording.
- **E — unsupported:** remove.

Do not upgrade A/B/C into D.

## High-risk language
Do not generate unsupported claims such as:
- 治疗/根治/治愈
- 消炎/杀菌/抗病毒
- 药到病除/立刻见效
- 100%有效/零副作用
- 替代药物/替代治疗
- 对某疾病有特效
- 医生推荐/医院同款 unless verified
- 国家级/官方认证/临床验证 unless verified
- guaranteed outcomes or quantified efficacy without evidence

When the supplied evidence supports a regulated claim, preserve the exact approved meaning and avoid strengthening it with marketing exaggeration.

## Consumer communication
Translate supported facts into:
**what it is → where/how it is used → what the user needs to know → evidence → usage guidance → warnings/trust.**

Avoid fear-based disease imagery, sensational symptoms, exaggerated before/after, or pseudo-medical diagrams that imply unsupported efficacy.

## Visual proof grammar
Preferred proof patterns:
- product form and packaging clarity
- correct application/use scene
- texture/spread/dispersion when genuinely visible and non-misleading
- nozzle/spray pattern only when visually supported
- patch shape, flexibility or placement without implying therapeutic outcome
- ingredient/material source when supported
- usage steps
- package information/parameters
- factual registration/filing/trust information
- clean lifestyle context

Do not visualize an invisible biological mechanism as fact unless it is explicitly supported and accurately represented.

## Default 5 head images
- H01: product recognition + category clarity
- H02: core supported differentiator
- H03: correct use/application
- H04: material/form/packaging/functional proof
- H05: target-user scenario + trust/decision reason

Keep H01 square 1:1 unless the marketplace requires another ratio.

## Default 10 detail screens
- D01: hero + product/category recognition
- D02: user scenario / pain point expressed safely
- D03: product form + how it works at the user-experience level, only when supported
- D04: ingredient/material/formulation facts
- D05: correct usage/application steps
- D06: use scene / target audience
- D07: specifications / package contents / dimensions / dosage-form facts
- D08: warnings / contraindications / storage / usage boundaries
- D09: registration/filing/quality/trust evidence, only when supplied
- D10: closing + correct-use reminder + purchase decision reason

For regulated products, D08 is mandatory when warnings/contraindications exist.

## Medical visual language
Use clean, trustworthy, restrained visual systems. Prefer realistic product photography, hygienic environments, legible factual diagrams and restrained medical color cues. Avoid fake hospital authority, doctor endorsement, laboratory theatrics, blood/gore, disease horror, or imagery that promises treatment results.

## Before/after rule
Do not use dramatic symptom before/after images unless the exact comparative claim is authorized and substantiated. For most cases, replace with neutral use context, product-form demonstration, or factual instruction.

## Model and body depiction
If a person appears:
- show natural, plausible use
- avoid depicting severe disease or distress solely to amplify conversion
- do not imply guaranteed symptom relief from facial expression or body posture
- keep the product placement and application method accurate
- do not show application to prohibited/inappropriate body areas

## Detail-page layout
Default 3:4 vertical. Use a clear hierarchy:
**headline → visual proof → concise supporting fact → necessary qualifier/warning.**
Do not bury important warnings in tiny unreadable type.

## Reference-image rules
Reference images can supply layout rhythm, lighting, color relationships, typography and commercial tone. Do not copy another brand's packaging, logo, medical claims, doctor imagery, certification badges or exact promotional language.

## No-icon rule
Do not use decorative icon grids, fake certification badges, checkmark claims or pseudo-clinical symbols as substitutes for evidence.

## Compliance gate
Before approval, audit:
- product category/status
- every efficacy statement
- ingredient/component statement
- dosage/use instruction
- registration/filing/approval information
- warnings and contraindications
- medical imagery implication
- before/after implication
- authority/endorsement implication
- comparative claims
- platform-specific prohibited wording

If evidence is absent, downgrade to a visible fact, neutral education, or remove.

## Prompt contract
Every image prompt must include:
- exact product identity lock
- supported message
- visual proof pattern
- realistic application/use behavior
- medical/health-safe visual constraints
- product exposure level
- scene/composition
- camera/light/materials
- typography area and exact approved copy when text is required
- output ratio
- negative constraints against fake efficacy, fake certification, altered packaging and invented medical details

## QA
### Product QA
Packaging, label, dosage form, container, nozzle/tube/patch geometry, net content, color and text must match supplied references.

### Medical-claim QA
No invented efficacy, treatment, clinical result, certification, endorsement or mechanism.

### Visual QA
No misleading anatomy, fake medical authority, exaggerated symptom relief, altered product identity, unreadable warnings, or decorative pseudo-evidence.

### Set QA
Consistent product identity, typography, color system, trust level, claim boundaries and visual diversity across all 15 outputs.

## Output workflow
**Product Truth → Regulatory/Claim Lock → Buyer Scenario → Selling Point Bank → Campaign Style Lock → Visual DNA → 5+10 Storyboard → One Approval Gate → Production Prompts → Generation → Compliance QA → Product QA.**
