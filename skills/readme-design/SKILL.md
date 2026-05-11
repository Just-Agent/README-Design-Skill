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

## Layout Patterns

Prefer one of these:

- Product README: hero, preview, features, quick start, examples, architecture, roadmap, FAQ.
- Research/roadmap README: hero, scope, interactive index, topic map, comparison table, download center, citation/resources.
- Tool/library README: hero, install, 30-second usage, API examples, integrations, benchmarks, troubleshooting.
- Profile README: identity header, focus areas, featured projects, tech stack, writing links, stats, contact.
- Collection/awesome README: hero, categories, curated table, badges, contribution guide, update policy.

Read `references/patterns.md` when choosing a detailed pattern.

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
- The license and contribution path are easy to find.
- The README still renders correctly without external CSS or JavaScript.

## Safety And Accuracy

- Check existing repository files before referencing screenshots, demos, docs, or badges.
- Do not claim GitHub Pages, CI, releases, license, or package support unless the repo actually has it or the user asks to create it.
- Preserve user content that represents project truth, but improve hierarchy, wording, and presentation.
- When changing README links, verify local paths exist where practical.

