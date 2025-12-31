---
permalink: /markdown/
title: "Site Guide"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

{% include toc %}

## Locations of key files/directories

This page documents how my AcademicPages-based website is organized.

- **Basic site configuration:** `_config.yml`
- **Top navigation bar:** `_data/navigation.yml`
- **Single pages:** `_pages/`
- **Publications:** `_publications/`
- **Projects / Portfolio:** `_portfolio/`
- **Blog posts:** `_posts/`
- **Teaching:** `_teaching/`
- **Talks:** `_talks/`
- **Footer layout:** `_includes/footer.html`
- **Static files (PDFs, CV):** `/files/`
- **Profile image:** `images/profile.png`

---

## Writing content

- Files ending in `.md` are rendered using Markdown.
- Files ending in `.html` are rendered as raw HTML.
- This site uses **Kramdown (GitHub Flavored Markdown)** via Jekyll.

For Markdown syntax reference, see:
- [Kramdown documentation](https://kramdown.gettalong.org/syntax.html)
- [GitHub Flavored Markdown](https://github.github.com/gfm/)

---

## CV formats

This site supports two CV formats:

- **JSON-based CV** (currently used): `/cv-json/`
- **Markdown CV**: `/cv/` (hidden from navigation)

The active CV format is controlled in `_data/navigation.yml`.

---

## Build status (GitHub Pages)

You can check the GitHub Pages build status via the repository commit list:

- ✅ Green check — build successful
- 🟠 Orange circle — build in progress
- ❌ Red X — build failed

This is useful when debugging layout or Markdown issues.

---

## Math support (MathJax)

MathJax (v3) is enabled for writing equations.

Example:

$$
\nabla \cdot E= \frac{\rho}{\epsilon_0}, \quad
\nabla \times E= -\partial_tB
$$

- Use `$$ ... $$` for display math
- Use `\\( ... \\)` for inline math

---

<!--
## Mermaid diagrams
Mermaid diagram support is available but not currently used on this site.
-->

<!--
## Plotly
Plotly diagrams are supported but not currently used.
-->

<!--
## Tables
Table examples removed — not needed for this site.
-->

<!--
## HTML tags demo
Extensive HTML tag demonstrations removed for clarity.
-->

<!--
## Footnotes demo
Footnote examples removed.
-->

<!--
## Emoji support
Emoji demo removed.
-->

---

## Notes

This page serves as a **personal reference** for maintaining and extending the website.
It is not intended as a public Markdown tutorial.
