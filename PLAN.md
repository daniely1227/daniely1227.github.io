# Portfolio Site Plan

## Purpose and design

Build a personal portfolio for `daniely1227.github.io` as a quiet, text-first document: light theme, generous whitespace, professional serif headings, neutral sans-serif body text, no hero images or animation, and a responsive single-column layout intended to keep each page readable in one scroll.

## Pages and content

- **Home:** concise introduction and links to the other pages.
- **About:** biography.
- **Work Experience:** roles and experience.
- **Contact:** public email link to `daniel.yun@berkeley.edu`.

No About or work history was supplied. Those details, along with any other personal facts, will be visibly marked as placeholders rather than invented.

## Implementation

- Use GitHub Pages-compatible Jekyll, Markdown pages with YAML front matter, and reusable layouts/includes.
- Put `_config.yml`, `index.md`, `_layouts/`, `_includes/`, `assets/`, and all other site files directly in the project root. Leave `baseurl` empty and use Jekyll URL filters for internal links.
- Include semantic HTML, accessible contrast, navigation, footer, SEO metadata, sitemap, favicon, and a README covering updates, local preview, and Lighthouse.
- Use plain HTML and CSS with no backend, database, form service, framework, third-party trackers, or unnecessary JavaScript.
- Replace the generated starter workspace with the standalone root-level Jekyll site so GitHub Pages can publish from `main` and `/ (root)`.

## Verification

Check root-level publishing structure and internal navigation; inspect the site at 375px and 1280px; run Lighthouse and target at least 90 in Performance, Accessibility, Best Practices, and SEO.

## Assumptions

- The portfolio owner is Daniel Yun, based on the supplied GitHub username and email address.
- Until personal copy is provided, the site will show clear content placeholders.
- The supplied email address is approved for public display as a `mailto:` link; visitors will need an email app to use it.
