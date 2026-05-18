---
name: readme-design
description: Design and rewrite polished GitHub README homepages for repositories and profile READMEs, especially Chinese/English open-source projects. Use when the user asks to beautify, redesign, improve, package, market, or make a README more professional, visual, persuasive, scannable, or GitHub Pages-like. Focus on README aesthetics, layout, badges, screenshots, project positioning, information architecture, and Markdown/HTML that renders well on GitHub.
---

# README Design

Treat a README as the repository's homepage, not just documentation. Make the first screen explain what the project is, why it matters, where to try it, and what visual proof exists.

## Core Workflow

1. Audit the current README and repository assets.
2. Identify the audience: users, contributors, researchers, employers, investors, or open-source visitors.
3. Define the repository's first-viewport message: name, positioning, proof, primary links, and visual preview.
4. Redesign the README structure before rewriting prose.
5. Add useful visual assets: screenshots, architecture diagrams, workflow diagrams, badges, previews, or GitHub Pages links.
6. Keep Markdown portable and GitHub-rendered: avoid scripts, fragile CSS, and layout tricks that fail in GitHub README rendering.
7. Verify the README is scannable on mobile and desktop.

## First Screen Pattern

Use a strong opening block:

- Centered project name or logo when the repo is product-like.
- One concise positioning sentence in Chinese or bilingual form.
- Badges grouped by meaning: status, docs, license, release, stars, platform, build.
- Primary links: Demo, GitHub Pages, docs, paper, download, examples, changelog.
- A real screenshot or preview image within the first 1-2 scrolls.

Avoid a first screen that is only a title, one subtitle, many tiny links, and a horizontal rule.

## Logo And README Wordmark

When a product-like repository does not have a recognizable first-viewport identity, design a small original logo or wordmark for the README top.

- Keep the project name as the real `<h1>` and place the logo above or beside it with GitHub-safe `<img>` HTML.
- Prefer repo-owned assets such as `docs/readme-assets/logo.svg`, `docs/assets/logo.svg`, or `assets/logo.png`.
- Make the logo original and project-specific; do not copy reference images, third-party mascots, trademarks, or marketplace icons.
- Use SVG for crisp README rendering, and create a PNG fallback only when thumbnails, social cards, or external platforms need it.
- Keep the first viewport useful: logo, positioning sentence, badges, primary links, and one proof image should fit without burying the project explanation.
- Verify the asset path, alt text, file size, and light/dark GitHub readability.

## Layout Patterns

Prefer one of these:

- Product README: hero, preview, features, quick start, examples, architecture, roadmap, FAQ.
- Research/roadmap README: hero, scope, interactive index, topic map, comparison table, download center, citation/resources.
- Tool/library README: hero, install, 30-second usage, API examples, integrations, benchmarks, troubleshooting.
- Profile README: identity header, focus areas, featured projects, tech stack, writing links, stats, contact.
- Collection/awesome README: hero, categories, curated table, badges, contribution guide, update policy.

Read `references/patterns.md` when choosing a detailed pattern.

## Template Library

Use `assets/templates/default.md` when the user asks for a complete standard README. It includes the full checklist: hero, badges, primary links, preview flow, highlights, quick start, usage, project structure, roadmap, Star History, Activity Overview, contribution, and license.

Use `assets/templates/styles/` when the user asks for a specific visual direction or when the repo clearly fits one style:

- `01-product-showcase.md`: product/app/browser extension README.
- `02-research-roadmap.md`: research, roadmap, paper, or company-analysis repo.
- `03-library-docs.md`: tool/library/API README.
- `04-profile-portfolio.md`: personal GitHub profile README.
- `05-awesome-curation.md`: curated list or awesome repository.
- `06-profile-activity-overview.md`: profile README with Activity Overview / contribution-type distribution.
- `07-startup-landing.md`: startup-style project homepage.
- `08-course-tutorial.md`: course/tutorial/learning path README.
- `09-bilingual-global.md`: Chinese-English global open-source README.
- `10-minimal-technical.md`: restrained technical README for infra/devtools.

Templates are written as polished sample READMEs, not raw placeholder dumps. Do not paste one blindly. Replace sample names, links, commands, numbers, and claims with repository facts; remove sections that do not match the project.

## Visual Standards

- Use real screenshots or generated preview images when they help visitors understand the project.
- Place screenshots under repo-owned paths such as `assets/`, `docs/assets/`, or `public/`.
- Keep image widths responsive with GitHub-safe HTML: `<img src="..." width="900" />` or `style="max-width:900px;width:100%;"`.
- Use Mermaid for architecture and workflow diagrams when a generated image is not necessary.
- Use shields.io badges sparingly and group them under the title.
- Use tables for comparisons, matrices, roadmap status, and project collections.
- Use callouts with blockquotes only for important warnings or positioning.

## Writing Standards

- Start with concrete value, not abstract slogans.
- Prefer short sections and descriptive headings.
- Use bilingual headings only when the repo targets both Chinese and global readers.
- Replace vague phrases like "very powerful" with capabilities, examples, metrics, or screenshots.
- Avoid generic AI phrasing such as "innovative", "seamless", "empowering", "next-generation", and "comprehensive" unless evidence makes the claim specific.
- Make the README persuasive but still truthful: do not invent stars, downloads, papers, benchmarks, or support status.
- For Chinese open-source repos, keep the tone confident, clean, and product-like; avoid dense academic paragraphs at the top.

## README Polish Checklist

- The first screen shows what the project is and why it matters.
- There is at least one visual proof element for UI/product/tutorial repos.
- The primary action links are visible near the top.
- Badges are relevant and not noisy.
- The table of contents is useful for long READMEs.
- Installation or usage appears before deep implementation details.
- File paths, URLs, and commands are current.
- Star History is included when growth/social proof matters.
- Activity Overview is included for profile or contributor-focused READMEs when contribution mix is part of the story.
- The license and contribution path are easy to find.
- The README still renders correctly without external CSS or JavaScript.

## Public Repository Quality Gate

For public GitHub repositories, make the README satisfy these three traits:

- **Professional:** accurate positioning, truthful badges and links, clear install/use path, license visibility, and no exaggerated claims.
- **Beautiful:** a strong first viewport, tasteful visual proof, readable spacing, restrained badge groups, and screenshots or diagrams that help people understand the project quickly.
- **Universal:** instructions and examples that work beyond the owner's machine, avoid private paths or account assumptions, and mention platform differences when they matter.

## Safety And Accuracy

- Check existing repository files before referencing screenshots, demos, docs, or badges.
- Do not claim GitHub Pages, CI, releases, license, or package support unless the repo actually has it or the user asks to create it.
- Preserve user content that represents project truth, but improve hierarchy, wording, and presentation.
- When changing README links, verify local paths exist where practical.
