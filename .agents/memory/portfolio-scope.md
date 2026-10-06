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

Use a clean source-only repository for public GitHub publishing rather than pushing development checkpoint history containing source uploads. The phone number is not approved for public display.

**Why:** Initial development checkpoints included the uploaded resume; removing it from the current tree does not remove it from old commits.

**How to apply:** Before any public GitHub push, inspect what history will be transferred and avoid publishing source attachments or unapproved contact information.
