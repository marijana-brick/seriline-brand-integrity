# Seriline Brand Integrity

**A cross-tool brand and quality skill for Seriline.** Use it when an AI assistant, designer or agent creates or reviews Seriline websites, product interfaces, presentations, sales material, reports, proposals, emails, graphics or dashboards.

The objective is not simply to remove obvious "AI slop." It is to produce work that **looks, sounds and behaves like Seriline**: clear, capable, security-conscious, product-specific and grounded in actual brand evidence.

> **Status:** This repository contains a **public-source interpretation**, not an official Seriline brand book. The website and published product collateral are the source of the recommendations. Approved internal identity files, design tokens and templates take precedence.

## Getting started

1. Read [`SKILL.md`](SKILL.md) for the agent operating protocol.
2. Read [`references/seriline-public-brand-guidelines.md`](references/seriline-public-brand-guidelines.md) for actionable brand guidance based on Seriline's online presence.
3. Check [`references/brand-profile.md`](references/brand-profile.md) for brand facts, product terminology, assumptions and missing official specifications.
4. Use [`references/tool-playbooks.md`](references/tool-playbooks.md) to adapt the brand for the current tool or artifact.
5. Before delivery, run [`references/seriline-review.md`](references/seriline-review.md) and verify the actual result.

## Example agent instruction

```text
For any Seriline-facing deliverable, follow SKILL.md and the Seriline public brand
guidelines. Use official assets and approved templates when available. Preserve
the company's practical, trustworthy identity; do not default to generic SaaS
gradients, fake hardware renders or exaggerated security claims. Mark unverified
design tokens or product claims rather than inventing them. Review the finished
artifact in its native tool before delivery.
```

## What's in this repo

| File | Purpose |
| --- | --- |
| [SKILL.md](SKILL.md) | Agent workflow: discover → audit → direct → build → verify |
| [Public brand guidelines](references/seriline-public-brand-guidelines.md) | Visual identity, voice, examples, design and content rules inferred from first-party online materials |
| [Brand profile](references/brand-profile.md) | Product context, source hierarchy and unknown official specifications |
| [Brand intake](references/brand-intake.md) | Process for adding approved internal identity assets |
| [Tool playbooks](references/tool-playbooks.md) | Channel-specific rules for UI, slides, documents, marketing and more |
| [Seriline review](references/seriline-review.md) | Brand, product accuracy and trust checklist |
| [API reference](references/api_reference.md) | Additional supporting reference |
| [agents/openai.yaml](agents/openai.yaml) | Skill discovery metadata |

## Working rules

- **Prefer brand truth over plausible invention.** Use existing logo artwork, product photos, product names, approved templates and demonstrable facts.
- **Keep the style coherent across tools without making every artifact identical.** A security admin UI and a customer brochure solve different jobs.
- **Explain with mechanisms and workflows.** Show how a credential is issued, an identity is updated or a visitor checks in.
- **Validate security and legal claims.** Do not invent certifications, performance numbers, compatibility or GDPR guarantees.
- **Do not present inferred tokens as official.** Color hex values, fonts, spacing, logo clearspace and component specifications require an approved source.

## Source library

First-party starting points (accessed 2026-11-05):

- [Seriline English website](https://www.seriline.com/en)
- [About Seriline](https://www.seriline.com/en/about-us)
- [Identity management](https://www.seriline.com/en/identity-management)
- [Access management](https://www.seriline.com/en/access-management)
- [Cidron](https://www.seriline.com/en/cidron)
- [Visitor management](https://www.seriline.com/en/visitor-management-system-visitor)
- [Seriline marketing materials](https://www.seriline.com/en/support/marketing-material)

See the public brand guidelines for an evidence-to-rule mapping.

## Improving accuracy

The highest-value next additions are the official vector logo, color codes, typography specification, slide master, approved document templates, product UI library and current product photography. Replace provisional statements in the public guide with approved rules as these arrive. Track which changes were approved, by whom and when.

## Provenance

The skill follows an audit → direction → iterative refinement workflow inspired by [Unslop](https://github.com/heydamir/unslop). This is a separate, Seriline-focused implementation. The public brand guidelines are an interpretation of Seriline's published materials, **not a document issued or endorsed by Seriline's brand team**.
