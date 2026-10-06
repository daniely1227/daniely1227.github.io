---
name: Portfolio scope
description: User's standing constraints for the portfolio and public publishing.
---

The portfolio must be a standalone GitHub Pages-compatible Jekyll site with all source at the repository root. Do not introduce a Node, React, or Vite app, a monorepo, a nested website, a backend, or a separate preview application.

**Why:** The user explicitly requires direct GitHub Pages publishing from main and the repository root.

**How to apply:** Keep Markdown content, YAML front matter, reusable HTML layouts/includes, and plain CSS. Jekyll's native development preview is the site itself, not a separate application.

Use only facts from the user-supplied resume. Do not invent or embellish achievements, roles, metrics, or projects, and do not fetch personal information from URLs. Mark missing personal details as placeholders.

**Why:** The user repeated this accuracy requirement when supplying the resume.

**How to apply:** Check new portfolio copy against the supplied source before adding it. Do not infer qualifications or completed education from an in-progress degree.

The user wants a light-only, text-first document feel with whitespace, professional serif headings, neutral sans-serif body text, no hero images, and no animations.

**Why:** These were the user's explicit visual choices.

**How to apply:** Preserve the restrained design rather than turning it into a marketing landing page.

The user requires the source resume file removed from project folders, including uploads and attachments, and from local Git history. Never reintroduce it. The phone number is not approved for public display.

**Why:** The user explicitly requested deletion of the source resume and approved purging local history.

**How to apply:** Before any public GitHub push or restoration from a clone or backup, inspect the transferred files and history. Avoid reintroducing source attachments or unapproved contact information.
