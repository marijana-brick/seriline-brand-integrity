# Seriline Brand Integrity

**A cross-tool brand and quality skill for Seriline.** Use it when an AI assistant, designer or agent creates or reviews Seriline websites, product interfaces, presentations, sales material, reports, proposals, emails, graphics or dashboards.

The objective is not simply to remove obvious "AI slop." It is to produce work that **looks, sounds and behaves like Seriline**: clear, capable, security-conscious, product-specific and grounded in actual brand evidence.

> **Status:** This repository contains a **public-source interpretation**, not an official Seriline brand book. The website and published product collateral are the source of the recommendations. Approved internal identity files, design tokens and templates take precedence.

## Install

This repository **is the skill directory**: `SKILL.md`, `references/` and `agents/` live at the repo root. Install the **whole folder**, not only the Markdown file. No npm packages or runtime dependencies are needed for the skill itself.

### Claude Code

Install for all your projects:

```bash
git clone https://github.com/marijana-brick/seriline-brand-integrity.git
mkdir -p ~/.claude/skills
cp -R seriline-brand-integrity ~/.claude/skills/seriline-brand-integrity
```

For a single project, put the entire skill folder in `.claude/skills/seriline-brand-integrity/` instead:

```bash
mkdir -p .claude/skills
cp -R seriline-brand-integrity .claude/skills/seriline-brand-integrity
```

### Codex and agents supporting the shared skills convention

Install for all projects:

```bash
git clone https://github.com/marijana-brick/seriline-brand-integrity.git
mkdir -p ~/.agents/skills
cp -R seriline-brand-integrity ~/.agents/skills/seriline-brand-integrity
```

For one project, copy the full folder into `.agents/skills/seriline-brand-integrity/`.

In Codex setups that include `$skill-installer`, you can also try:

```text
$skill-installer install https://github.com/marijana-brick/seriline-brand-integrity
```

If your installer expects a skill **subdirectory** and rejects a repository-root `SKILL.md`, use the manual copy instructions above.

### ChatGPT

If your ChatGPT workspace supports custom skill uploads, make a ZIP containing this skill folder (including `SKILL.md` and `references/`) and upload it through the Skills interface. Check the actual upload and availability before relying on automatic activation.

If your workspace does not support skill uploads, copy the [agent instruction](#for-tools-without-native-skills) into the tool's instructions and attach the relevant reference files. This is a fallback, not equivalent to installing a skill.

### Other AI tools

Use the [portable agent instruction](#for-tools-without-native-skills) in a project's instructions, custom rules or system prompt. When supported, give the agent access to this repository so it can consult the full guide and review checklist. Do **not** assume a tool can read private or local files merely because a path is mentioned.

## Use

In Claude Code, invoke `/seriline-brand-integrity` if the skill is recognized as a slash command. In Codex, invoke `$seriline-brand-integrity` if the installed skill is listed. Otherwise ask naturally and mention the skill by name. Command availability varies with host and skill discovery settings.

```text
/seriline-brand-integrity Audit this dashboard and bring it in line with Seriline's brand.
/seriline-brand-integrity Rewrite this product page in Seriline's voice without inventing capabilities.
/seriline-brand-integrity Build a Seriline sales deck using approved product photos and templates.
```

```text
$seriline-brand-integrity Review this Visitor onboarding UI for generic AI styling and product accuracy.
$seriline-brand-integrity Create a Seriline-branded proposal from these notes.
```

Or simply ask:

```text
Use the Seriline Brand Integrity skill to polish this PDF report.
Follow the Seriline public brand guidelines when designing this landing page.
Review these slides for brand consistency, factual accuracy and readability.
```

The workflow is **audit → brand direction → focused edits → rendered review**. When revising existing work, the agent should identify specific issues and preserve what's already strong, not redesign by reflex. It must label unverified design choices and ask for approved files when necessary.

## For tools without native skills

Paste this as an **instruction**, not as a user-facing deliverable:

```text
You are working for Seriline. For any Seriline-facing deliverable, use the
Seriline Brand Integrity instructions in SKILL.md and, when accessible,
references/seriline-public-brand-guidelines.md, references/brand-profile.md,
references/tool-playbooks.md and references/seriline-review.md.

Make the work recognizable as Seriline: practical identity and access
management, accurate products and workflows, restrained blue-led visual
direction, clear hierarchy and technically credible, useful writing.
Avoid stock "AI cybersecurity" imagery, decorative SaaS clichés,
inflated marketing copy and unsupported security/product claims.

First audit or establish a direction, then improve the actual artifact.
Prefer approved Seriline templates, logos and photos. Never invent official
colors, font specifications, certifications or product capabilities.
Mark public-source interpretations as provisional. Check the rendered
result in its native tool and report any unverified details.
```

## Example tasks

| Deliverable | Try asking |
| --- | --- |
| Website | "Make this Serix product page look and read like Seriline. Audit before editing." |
| Product UI | "Review this identity-management dashboard for brand fidelity, task clarity and accessibility." |
| Slides | "Turn these notes into a six-slide Seriline sales presentation using approved imagery." |
| Document | "Create a two-page Seriline proposal, preserving the latest approved document template." |
| Email | "Rewrite this customer email in Seriline's clear, confident and accurate tone." |
| Campaign | "Create three campaign concepts grounded in real Cidron capabilities. Flag claims needing verification." |

## What it does

- **Audit:** Identify concrete off-brand elements, generic AI patterns, writing problems and unsupported claims.
- **Direction:** Set a short, evidence-backed design and voice direction before major edits.
- **Build:** Apply the correct tool-specific playbook while preserving function, accessibility and editing capabilities.
- **Verify:** Review the real render or output, and separate confirmed requirements from provisional interpretations.

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

The public brand guidelines are an interpretation of Seriline's published materials, **not a document issued or endorsed by Seriline's brand team**.
