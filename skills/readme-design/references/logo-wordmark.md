# README Logo And Wordmark Guide

Use this guide when a README needs a recognizable first-viewport identity. The goal is a GitHub-safe project mark that helps visitors remember the repository without turning the README into a marketing poster.

## When To Add A Logo

Add a README logo or wordmark when at least one of these is true:

- The repository is a public product, app, CLI, skill, plugin, design system, template, or portfolio.
- The README top currently has only a title, badges, and links.
- The user explicitly asks for a logo, cover mark, brand mark, mascot-like identity, or top visual.
- The project already has screenshots or thumbnails and needs a consistent identity across them.

Skip or keep it minimal when:

- The repository is a tiny internal utility, private experiment, or archival code dump.
- A strong official logo already exists and the user wants to preserve it.
- The README is intentionally strict technical documentation where a mark would distract.

## Design Decision Tree

| Project type | Logo direction | Safe symbols |
| --- | --- | --- |
| CLI / devtool | Compact code or terminal mark | prompt, bracket, cursor, package, route |
| Agent skill / plugin | Document plus action mark | file, spark, route, progress, checklist |
| UI / app | Product-shaped wordmark | panel, window, control, cursor, state |
| Data / research | Evidence mark | grid, chart, timeline, map, node |
| Learning / course | Path mark | steps, book, checkpoint, compass |
| Awesome / collection | Curated index mark | list, star, cards, shelf |
| Profile | Personal wordmark | initials, signature, focus icons |

## Asset Defaults

| Asset | Preferred path | Notes |
| --- | --- | --- |
| README logo | `docs/readme-assets/logo.svg` or `docs/assets/logo.svg` | SVG is crisp and portable on GitHub |
| PNG fallback | `docs/readme-assets/logo.png` | Use only when a platform needs PNG |
| README hero/preview | `docs/readme-assets/hero.png` | Use for screenshot composites, not as the only title |
| Social card | `docs/readme-assets/thumbnail/og.png` | Regenerate when the logo changes |

Recommended SVG size:

- Canvas: `640x320`, `760x360`, or square `512x512`.
- README display width: `180` to `360`.
- Keep text readable at `240px` display width.
- Use transparent or light-safe backgrounds unless the README design needs a contained badge.

## GitHub-Safe Snippet

```html
<div align="center">
  <img src="./docs/readme-assets/logo.svg" alt="Project Name logo" width="320" />
  <h1>Project Name</h1>
  <p><strong>One concrete sentence about what the project does.</strong></p>
  <p>
    <a href="https://example.com">Demo</a>
    ·
    <a href="./docs">Docs</a>
    ·
    <a href="./CHANGELOG.md">Changelog</a>
  </p>
</div>
```

Use relative paths for repository assets. Do not use `file://` paths, local Windows paths, or temporary screenshot paths.

## Quality Checklist

- The logo is original and clearly different from any visual reference.
- The mark relates to the repository domain, not a generic decoration.
- The README still has a real `<h1>` for accessibility and GitHub navigation.
- The logo has useful `alt` text.
- The asset path exists in the repository.
- The logo renders on GitHub light mode and remains legible on dark mode.
- Badges, links, and first proof image still fit naturally under the logo.
- Any thumbnail, Open Graph, or social preview assets are refreshed when needed.

## Prompt Pattern

```text
Design an original README top logo for this repository.
Use the project domain, existing screenshots, and README positioning.
Create a repo-owned SVG at docs/readme-assets/logo.svg.
Add it above the README h1 with GitHub-safe HTML.
Do not copy the reference image; use it only for layout inspiration.
Verify the asset path and alt text.
```
