---
name: detail-flow
version: upstream-adapted
source: AJbeckliy/detail-flow
source_url: https://github.com/AJbeckliy/detail-flow
---

# DetailFlow — Ecommerce Master Integration

This is an integrated specialist route based on the public `AJbeckliy/detail-flow` Skill. The upstream repository is the reference source; this local copy is adapted as a specialist inside `ecommerce-master-skill` so it can coexist with the furniture and medical-topical routes.

## When to activate
Use this route when the user asks for a general ecommerce product detail page, long-form product page, 8-screen detail page, redesign/polish/audit of an ecommerce detail page, or explicitly asks to use `detail-flow`.

Do NOT override a more specific specialist route. If the product is clearly furniture, use Furniture Detail Page Mode. If it is a topical medical/health product such as ointment, cream, spray or patch, use Medical Topical Detail Page Mode and its compliance rules.

## Core execution contract
For image-led ecommerce detail-page requests:
1. Analyze product and reference inputs separately.
2. Produce the complete page blueprint first.
3. Stop for user approval of the blueprint.
4. Establish text master and visual/style master.
5. When useful, create and inspect a 1:3 continuous long-page master reference.
6. Generate the first 2 final 9:21 slices.
7. Concatenate and inspect the 2-slice preview.
8. Present the 1:3 master, first 2 slices, preview and audit together.
9. Stop for the second user approval.
10. Generate remaining slices.
11. Concatenate the complete page and run final audit.
12. Save/report the approved output set.

Standard workflow has exactly two approval gates unless the user explicitly changes the workflow or a serious failure requires intervention.

## Blueprint requirements
For each screen define:
- slice_id
- buyer_question
- module_type
- module_label
- claim_seed
- screen_job
- evidence_type
- content_density
- layout_archetype
- copy_module_type
- copy_structure_pattern
- primary_module
- secondary_modules
- text_exact
- hierarchy_strategy
- composition_shift
- top_edge_anchor
- bottom_edge_anchor
- visual_composition
- reference_style_notes
- risk_unknowns

Screen 01 establishes 2–4 core claim seeds. Later screens must expand, prove, visualize or contextualize those seeds instead of introducing unrelated claims.

## Visual continuity
Treat 8 screens as sequential sections of ONE ecommerce detail page, not eight independent posters.

Maintain:
- shared background world
- lighting direction
- palette
- typography system
- product rendering style
- recurring motifs
- spacing rhythm
- edge-to-edge transitions

Vary composition and information density while preserving the visual world. Avoid repeating a centered hero/product-plus-subject poster on every screen.

Top and bottom edge zones carry continuity only; keep critical claims and essential product proof away from these transition areas.

## Copy hierarchy
Do not force every screen into `headline + subtitle + hero`.

Use varied structures such as:
- hero claim stack
- question / answer
- single line with labels
- annotation map
- three-point breakdown
- scene-caption cluster
- mini steps
- trust checklist
- quiet closing

Each screen must answer a distinct buyer question. Adjacent screens must not be interchangeable when read without imagery.

## Product truth
Use supplied product images, confirmed facts and approved blueprint as authoritative inputs. Preserve product identity, packaging, color, shape, proportions, components and distinctive details. Do not invent exact specifications, certifications, awards, medical effects, discounts, partnerships or other unsupported facts.

For a product image-led request, distinguish:
- observed facts
- user-confirmed facts
- reasonable category inference
- unknown/risky claims

## Reference-image handling
Use reference images for abstract visual DNA: layout rhythm, light, typography attitude, density, material treatment, camera language and commercial temperature.

Do not copy another brand's product, logo, exact text, person identity or unsupported claims.

## Picture Solo Test
For every screen:
> With all text hidden, a buyer looking for 2 seconds should understand what this picture is proving.

If the visual depends entirely on the headline, redesign the visual proof.

## Prompt contract
Every production prompt should contain:
- exact product identity lock
- screen goal
- claim seed
- Picture Solo Statement
- proof/evidence pattern
- primary and secondary modules
- product exposure
- composition
- camera/view
- lighting
- materials/environment
- human action when relevant
- approved exact copy
- reference DNA
- output ratio
- negative constraints

## QA
Per image:
- product fidelity
- structure/proportions
- perspective
- material/color
- text accuracy
- claim safety
- proof fit
- composition/hierarchy
- ratio

Set level:
- screen diversity
- copy differentiation
- continuity
- product identity consistency
- typography/palette consistency
- no standalone-poster repetition
- no unsupported claims

## Upstream reference
The original public Skill is maintained at:
https://github.com/AJbeckliy/detail-flow

This integration intentionally keeps the `ecommerce-master-skill` router as the top-level authority and uses specialist routes for product-specific constraints.
