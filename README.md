<div align="center">
  <img src="./docs/assets/readme-design-logo.svg" alt="README Design Skill logo" width="340" />
  <h1>README Design Skill</h1>
  <p><strong>把 GitHub README 当成项目首页来设计，而不是当成说明书来堆内容。</strong></p>
  <p>
    <a href="./skills/readme-design/SKILL.md">Skill</a>
    ·
    <a href="./skills/readme-design/references/logo-wordmark.md">Logo Guide</a>
    ·
    <a href="./skills/readme-design/assets/templates/default.md">Default Template</a>
    ·
    <a href="./skills/readme-design/assets/templates/partials/logo-hero.md">Logo Hero Partial</a>
    ·
    <a href="./skills/readme-design/assets/templates/README.md">Template Gallery</a>
    ·
    <a href="./skills/readme-design/references/patterns.md">Design Patterns</a>
  </p>
  <p>
    <img src="https://img.shields.io/badge/Codex%20Skill-ready-10A37F" alt="Codex Skill ready" />
    <img src="https://img.shields.io/badge/templates-11%20%2B%20partials-2563EB" alt="11 templates plus partials" />
    <img src="https://img.shields.io/badge/logo%20hero-supported-F59E0B" alt="README logo hero supported" />
    <img src="https://img.shields.io/badge/focus-README%20homepage-111827" alt="README homepage" />
    <img src="https://img.shields.io/github/license/Just-Agent/README-Design-Skill" alt="license" />
  </p>
</div>

<p align="center">
  <img src="./docs/assets/readme-design-cover.svg" alt="README Design Skill cover" width="980" />
</p>

---

## Why This Exists

Most open-source READMEs fail in the same quiet way: the project may be useful, but the first screen does not say what it is, who it helps, where to try it, or why anyone should trust it.

`readme-design` gives Codex a repeatable design workflow for README homepages: stronger first screens, cleaner proof, better screenshots, useful badges, original README logos/wordmarks, grounded copywriting, and templates that render well on GitHub.

## 2026 Upgrade

This skill now treats a README top logo or wordmark as a first-class design capability.

| Upgrade | What Changed | Where |
| --- | --- | --- |
| Logo decision flow | The skill decides when a public repo needs a top identity mark | [SKILL.md](./skills/readme-design/SKILL.md) |
| Logo guide | Full rules for original marks, asset paths, snippets, and QA | [logo-wordmark.md](./skills/readme-design/references/logo-wordmark.md) |
| Reusable partial | Drop-in GitHub-safe logo hero block | [logo-hero.md](./skills/readme-design/assets/templates/partials/logo-hero.md) |
| Self-hosted logo | This repository now uses its own repo-owned SVG logo at the top | [readme-design-logo.svg](./docs/assets/readme-design-logo.svg) |
| Template coverage | Default, product, library, and bilingual templates now acknowledge README logos | [Template Gallery](./skills/readme-design/assets/templates/README.md) |
| Public quality gate | Professional, beautiful, universal README criteria are part of the skill | [Design Patterns](./skills/readme-design/references/patterns.md) |

## Standard README Anatomy

| # | Section | Purpose |
| --- | --- | --- |
| 1 | Hero | Name, optional original logo/wordmark, one-sentence positioning |
| 2 | Badges | Status, license, docs, release, stars, platform |
| 3 | Primary Links | Demo, GitHub Pages, docs, download, paper, examples |
| 4 | Visual Proof | Screenshot, architecture map, preview, result sample |
| 5 | Highlights | 3-6 concrete capabilities tied to user value |
| 6 | Quick Start | Install and run with the shortest honest path |
| 7 | Usage | Commands, examples, input/output, recipes |
| 8 | Structure | File map only when it helps navigation |
| 9 | Roadmap | Current state, next work, planned direction |
| 10 | Trust | Star History, contribution guide, license, FAQ |
| + | Activity Overview | Contribution-type distribution for profile/contributor READMEs |

## Template Gallery

| Template | Best For | First Impression |
| --- | --- | --- |
| [Default](./skills/readme-design/assets/templates/default.md) | General high-quality README | Complete homepage skeleton |
| [Logo Hero Partial](./skills/readme-design/assets/templates/partials/logo-hero.md) | Repositories that need only a top identity upgrade | Logo, h1, positioning, links, badges, preview slot |
| [Product Showcase](./skills/readme-design/assets/templates/styles/01-product-showcase.md) | Apps and browser extensions | Visual, workflow-first, screenshot-ready |
| [Research Roadmap](./skills/readme-design/assets/templates/styles/02-research-roadmap.md) | Research, roadmaps, paper collections | Topic map and output center |
| [Library Docs](./skills/readme-design/assets/templates/styles/03-library-docs.md) | Packages, SDKs, APIs | Install, example, API table |
| [Profile Portfolio](./skills/readme-design/assets/templates/styles/04-profile-portfolio.md) | GitHub profile README | Personal identity and featured work |
| [Awesome Curation](./skills/readme-design/assets/templates/styles/05-awesome-curation.md) | Curated lists | Category index and selection rules |
| [Activity Overview](./skills/readme-design/assets/templates/styles/06-profile-activity-overview.md) | Contributor-focused profiles | Contribution mix chart |
| [Startup Landing](./skills/readme-design/assets/templates/styles/07-startup-landing.md) | Early products | Problem, product, why now |
| [Course Tutorial](./skills/readme-design/assets/templates/styles/08-course-tutorial.md) | Tutorials and courses | Learning path and outputs |
| [Bilingual Global](./skills/readme-design/assets/templates/styles/09-bilingual-global.md) | Chinese projects going global | English/Chinese paired structure |
| [Minimal Technical](./skills/readme-design/assets/templates/styles/10-minimal-technical.md) | Infra and devtools | Precise, restrained, technical |

## What The Skill Cares About

- **First screen clarity**: a visitor should understand the project in 10 seconds.
- **README logo / wordmark**: product-like repos should get a small original top identity when they do not already have one.
- **Original visual identity**: reference images can guide composition, but the resulting mark must be distinct and repo-owned.
- **Visual evidence**: screenshots, diagrams, result previews, or structured examples.
- **Trust signals**: badges, Star History, license, contribution path, and real status.
- **Non-AI copy**: fewer vague claims, more concrete objects, workflows, outputs, and constraints.
- **GitHub-safe design**: Markdown, tables, Mermaid, shields, and conservative HTML that GitHub actually renders.

## Logo Hero Workflow

Use this when the user asks for a README logo or when a public product-like repository has no first-viewport identity.

1. Read the repo README, assets, screenshots, package metadata, and public positioning.
2. Choose a domain-specific mark: code, document, chart, window, path, checklist, route, or product object.
3. Create an original asset under a repo-owned path such as `docs/readme-assets/logo.svg`.
4. Add it above the README `<h1>` with GitHub-safe HTML and useful alt text.
5. Keep badges, links, and a proof image close to the top.
6. Regenerate thumbnails or social cards when the repository already maintains them.
7. Verify paths, image readability, and claims before publishing.

```html
<div align="center">
  <img src="./docs/readme-assets/logo.svg" alt="Project Name logo" width="320" />
  <h1>Project Name</h1>
  <p><strong>One concrete sentence about what the project does.</strong></p>
</div>
```

## Install

Copy the skill folder into your Codex skills directory:

```text
skills/readme-design -> ~/.codex/skills/readme-design
```

In this workspace, the installed skill lives at:

```text
C:\Users\harzva\.codex\skills\readme-design
```

This repository is the source copy. When updating the skill, keep these three places synchronized:

| Target | Path or URL |
| --- | --- |
| Local source repo | `D:\study\code\0ai\产品\01-skills\README-Design-Skill` |
| Installed Codex skill | `C:\Users\harzva\.codex\skills\readme-design` |
| Remote repo | [Just-Agent/README-Design-Skill](https://github.com/Just-Agent/README-Design-Skill) |

## Example Prompts

```text
Use $readme-design to redesign this repository README into a polished GitHub homepage.
```

```text
Use $readme-design and the research-roadmap template to make this project feel like a serious public knowledge base.
```

```text
Use $readme-design to remove AI-ish copy, add visual proof, and make the first screen more convincing.
```

```text
Use $readme-design to add an original README top logo, refresh the hero section, and update thumbnail assets.
```

## References

- [awesome-github-profile-readme-chinese](https://github.com/eryajf/awesome-github-profile-readme-chinese)
- [Anthropic frontend-design skill](https://github.com/anthropics/skills/blob/main/skills/frontend-design)

## License

MIT
