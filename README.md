# Product-Led Growth — SKILL.md files for AI agents

[![13 skills](https://img.shields.io/badge/skills-13-0b7285)](#whats-inside)
[![Format: Agent Skills](https://img.shields.io/badge/format-SKILL.md-5f3dc4)](https://agentskills.io/specification)
[![Works with Claude Code & Codex](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Codex%20%7C%20Claude.ai-1c7ed6)](#install)
[![Licence: CC BY 4.0](https://img.shields.io/badge/licence-CC%20BY%204.0-2b8a3e)](https://creativecommons.org/licenses/by/4.0/)

Free, ready-to-run **product-led growth** skills for **Claude, Claude Code, OpenAI Codex** and any agent that reads
the [Agent Skills](https://agentskills.io/specification) format. Free models, onboarding, feature adoption,
upgrade prompts, product-qualified leads, product-led sales, team expansion and ecosystem growth surfaces. Each
skill is a single `SKILL.md`: a senior practitioner's workflow — when to use it, the inputs to ask for, a numbered
process, decision rules, an output template and sources — loaded only when a task needs it.

Part of the [Marketing Skills library](https://github.com/afeezadebayo/marketing-skills) by
[Afeez Adebayo](https://afeezadebayo.com) · [Browse online](https://afeezadebayo.com/skills-md/marketing/product-led-growth/)

## Install

Each skill is its own folder with a `SKILL.md`, so you can drop any folder straight into an agent.

**Claude Code**
```bash
git clone https://github.com/afeezadebayo/product-led-growth-skills.git
cp -r product-led-growth-skills/plg-audit ~/.claude/skills/        # all projects
# or  .claude/skills/   inside one project
```

**OpenAI Codex**
```bash
cp -r product-led-growth-skills/plg-audit ~/.agents/skills/         # all repos
```

**Claude.ai / Desktop** — zip a skill folder, then **Settings → Capabilities → Skills → Upload skill**
(code execution must be enabled). To bulk-load the whole category into a Claude Project, custom GPT or
knowledge base, grab the single-folder `.zip` from the
[library page](https://afeezadebayo.com/skills-md/marketing/product-led-growth/).

Then start a new session and ask your agent which skills it can use.

## What's inside

| Skill | What it does |
|---|---|
| [`plg-audit`](plg-audit/SKILL.md) | Audit a product-led motion end to end with a stage-by-stage funnel and 90-day plan. The entry point. |
| [`plg-strategy`](plg-strategy/SKILL.md) | Decide whether and how to be product-led: fit, motion choice, value moment, operating model. |
| [`free-model-design`](free-model-design/SKILL.md) | Design free offers that drive revenue: freemium, trials, reverse trials, limits and gates. |
| [`in-product-onboarding`](in-product-onboarding/SKILL.md) | Design in-product onboarding from first login to the value moment and beyond. |
| [`feature-adoption`](feature-adoption/SKILL.md) | Drive adoption of features that change retention and expansion, with barrier diagnosis. |
| [`in-app-upgrade-prompts`](in-app-upgrade-prompts/SKILL.md) | Design in-app upgrade experiences: paywalls, limit prompts, trial endings, admin requests. |
| [`team-expansion-invites`](team-expansion-invites/SKILL.md) | Grow accounts from one user to whole teams through collaboration moments and invite flows. |
| [`product-qualified-leads`](product-qualified-leads/SKILL.md) | Define, score and route product-qualified leads and accounts from usage and fit signals. |
| [`product-led-sales`](product-led-sales/SKILL.md) | Design product-led sales motions where humans help accounts the product has already won. |
| [`in-app-messaging`](in-app-messaging/SKILL.md) | Plan in-app messaging that guides rather than interrupts: announcements, tips, surveys. |
| [`product-education`](product-education/SKILL.md) | Build product education that raises activation, adoption and retention: help centres, academies. |
| [`templates-integrations-growth`](templates-integrations-growth/SKILL.md) | Build product-led acquisition surfaces: template galleries, integration pages, marketplaces. |
| [`plg-metrics`](plg-metrics/SKILL.md) | Measure product-led growth from sign-up to net revenue retention with a shared metric tree. |

## How these skills work

Agents use *progressive disclosure*: they read each skill's `name` and `description` (~100 tokens) at the start
of a session and load the full `SKILL.md` only when your request matches — so you can install many without
filling the context window.

## Author & licence

By [**Afeez Adebayo**](https://afeezadebayo.com) — Marketing, SEO & Growth (SEO & Organic Growth at Grey, YC W22).
[LinkedIn](https://www.linkedin.com/in/afeez-adebayo/) · [X](https://x.com/za_icon) · [Newsletter](https://afeezadebayo.com/newsletter/)

Released under [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/) — use, share and adapt, including
commercially, with credit to Afeez Adebayo and a link to the source page in each file.

<sub>Keywords: product-led growth skills, PLG, SKILL.md, Agent Skills, Claude skills, Claude Code skills, Codex
skills, AI agent skills, freemium, free trial, onboarding, feature adoption, upgrade prompts, product-qualified
leads, product-led sales, team expansion, PLG metrics.</sub>
