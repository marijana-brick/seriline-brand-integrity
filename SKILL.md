---
name: seriline-brand-integrity
description: "Create, edit, audit and polish Seriline-branded output across tools: websites, Serix or Visitor UIs, slides, documents, proposals, PDFs, emails, campaigns, product sheets, dashboards and graphics. Use when a deliverable is for Seriline or its solutions and must reflect Seriline identity rather than generic AI aesthetics. Ground content in official brand assets, actual product facts and current templates; apply a Seriline-specific anti-slop review, verify the result, and flag unconfirmed brand rules."
---

# Seriline Brand Integrity — cross-tool brand and quality guardrails

## Mission
Make every artifact feel deliberately produced for **Seriline**, not by a generic assistant. Brand fidelity is not a coat of paint: preserve the company's strategy, distinctive visual grammar, language, audience, and established product patterns. A well-designed result can be restrained, expressive, or unconventional. Do not confuse generic minimalism with good design.

## Non-negotiables
1. **Evidence before invention.** Use Seriline's actual brand book, design system, source files, approved templates, product UI, published materials and copy guidance. Consult `references/brand-profile.md` and `references/seriline-public-brand-guidelines.md`. Never invent hex codes, fonts, logos, slogans, testimonials, statistics or permissions and present them as official.
2. **Respect source hierarchy.** Explicit task instructions > current approved brand system > approved channel-specific templates > recent first-party examples > inferred patterns. If sources conflict, surface the conflict and prefer the more authoritative/recent evidence. User-approved intentional departures override stylistic defaults, not factual or safety requirements.
3. **Tool-agnostic, artifact-specific.** Work in the tools available for the task. Do not claim to have inspected Figma, Canva, Drive, Notion, a CMS, repositories or asset libraries without access. Preserve the format, editability, interactions and functional requirements of the requested artifact.
4. **No style hallucination.** If the actual brand has not been provided, do not impersonate it. Use a clearly labeled provisional direction based on confirmed product context, and mark all inferred choices for replacement. Ask only for a genuinely blocking asset; otherwise deliver a useful provisional draft.
5. **Avoid anti-slop overcorrection.** Gradients, illustrations, emoji, large type, bright colors, rounded cards and playful language are not inherently bad. They are bad when generic, arbitrary, excessive, or contrary to the brand. Preserve them when they are signature brand elements.
6. **Protect brand and user trust.** Never invent case studies, certifications, logos, quotes, customer names or quantified claims. Never silently send, publish or overwrite an artifact. Follow tool-specific authorization and review requirements.

## Operating protocol

### 1. Identify the job and context
Record, briefly and internally: deliverable and file type; audience; channel; purpose; emotional register; level of brand strictness (formal, campaign, experimental); functional and accessibility requirements; owner and approval constraints. Preserve any existing project design system.

### 2. Retrieve the actual brand
Look for the most authoritative information accessible: linked brand guidelines, local `brand-profile.md`, approved design tokens, templates, fonts, visual assets, product screenshots, published pages, editorial examples, and recent decisions. If connectors exist, search only relevant authorized sources. Distinguish **CONFIRMED**, **INFERRED**, and **UNKNOWN**. Do not treat a competitor, stock layout, or arbitrary AI-generated sample as company identity.

Use `references/seriline-public-brand-guidelines.md` for the observed online brand and its practical creative translation. Use `references/brand-profile.md` as Seriline's evidence-labeled public-source baseline, then replace assumptions with approved internal assets when provided. Consult `references/seriline-review.md` for product/trust-specific checks. Use `references/tool-playbooks.md` for output-type checks. If the profile is blank, infer only the minimum viable direction from evidence, label it provisional and do not output invented 'official' tokens.

### 3. Audit before changing
For revisions, locate tangible signs of generic output and point to their positions, e.g. slide 3 title, hero CTA, component name, paragraph, card or image. Check:
- **Visual grammar:** random accent colors, familiar purple-to-blue gradients, decorative glows, generic 3D blobs, excessive cards, inconsistent radii, icons and spacing, placeholder imagery.
- **Language:** empty adjectives, inflated claims, 'revolutionize/unlock/elevate', canned three-part slogans, overuse of em dashes, generic CTAs, unnecessary hedging, boilerplate intros.
- **Content:** weak audience relevance, vague evidence, repeated ideas, made-up facts, overstuffed frameworks, no specific POV.
- **System:** mismatched document and product styles, conflicting tokens, inconsistent logo treatment, components that only match superficially.
- **Usability:** illegible typography, contrast failures, missing hierarchy, nonfunctional controls, inaccessible markup, poor mobile behavior.

Do not make a checklist of imaginary defects; report actual issues and leave strong existing work alone.

### 4. Set a precise brand direction
Before substantial creative edits, establish a short working brief:
- **Identity:** what company/product does and for whom (verified).
- **Character:** 2–3 *distinctive* adjectives supported by examples (not 'modern, clean, premium').
- **Visual grammar:** actual typography, color roles, geometry, spacing, imagery, hierarchy (or provisional substitutes clearly marked).
- **Verbal grammar:** voice traits, sentence length, vocabulary, preferred CTA style and words to avoid.
- **One signature:** a recurring, meaningful motif drawn from the company's work or approved identity, not random decoration.
- **What to preserve:** recognizable existing brand equity and functional patterns.

Where useful, show the direction to the user before a large irreversible change. For ordinary requested creation, proceed with the most supported direction and state assumptions at handoff.

### 5. Build in structured passes
Apply the passes that match the output; do not blindly apply web UI rules to an email.
1. **Truth and substance:** accurate information, clear audience benefit, specific proof, coherent narrative.
2. **Architecture:** information priority, task flow, document structure, purposeful sections.
3. **Brand system:** correct fonts, palette roles, grid, spacing, component reuse, logos and imagery.
4. **Copy:** characteristic company voice, useful specifics, restraint, deliberate emphasis.
5. **Craft:** thoughtful alignment, visual rhythm, chart labeling, image crops, states, transitions, detailed typography.
6. **Accessibility and fidelity:** contrast, reading order, alt text, responsive behavior, usability, tool rendering.

Reuse existing templates and components wherever suitable. Prefer one distinctive move done well over five decorative flourishes. In a formal report, the signature might be a data visualization or editorial hierarchy; in an app it might be navigation or a purposeful interaction.

### 6. Verify the artifact in its native environment
Inspect/render the final output wherever supported: screen screenshots and mobile states; slide/page previews; exported PDFs; HTML interaction; document pagination; spreadsheet formatting and formulas; email mobile-safe rendering. Compare to the known brand and task requirements. Fix errors rather than merely asserting success. If rendering is unavailable, explicitly mark the quality check as unverified.

### 7. Handoff briefly
Deliver the actual requested artifact. Mention only material design choices, what brand evidence was used, outstanding assumptions, and any missing QA/permissions. For audits, provide a prioritized punch list with **location → problem → specific fix**. For revised outputs, include a concise before/after summary when useful. Avoid theatrical self-congratulation.

## Definition of done
- Recognizably belongs to the intended company, based on observed sources.
- Solves the target user's job rather than resembling a generic demo.
- Contains no invented claims or unlicensed brand assets.
- Uses consistent tokens, design language, and vocabulary for its channel.
- Renders/works in the requested tool or transparently reports what could not be verified.
- Has no gratuitous 'AI polish' and no blind aversion to authentic brand choices.

## Optional review rubric
Score 0 (absent), 1 (weak), 2 (solid) on: brand evidence, distinctive craft, audience specificity, substance, consistency, usability/accessibility, native-format QA. Any score of 0 in truth, usability, or evidence for supposedly official brand elements is blocking. Do not fabricate numeric scores without inspecting the work.

## Related references
- `references/seriline-public-brand-guidelines.md` — public-source visual, verbal and multi-channel guidance; observed vs recommended vs unverified.
- `references/seriline-review.md` — Seriline-specific product, security and trust QA gates.
- `references/brand-profile.md` — company-specific inputs; fill this first for repeat use.
- `references/tool-playbooks.md` — medium-specific rules for slides, documents, UI, email, graphics and dashboards.
- `references/brand-intake.md` — how to extract a brand system from real assets without inventing it.

## Attribution
Inspired by the **audit → direction → iterative polish** pattern in [Unslop by Damir Sokolovsky](https://github.com/heydamir/unslop) (CC BY 4.0). This is a separately authored cross-tool brand-governance skill, not a copy of Unslop's source.