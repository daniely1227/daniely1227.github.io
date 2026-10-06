# Portfolio Site Plan

## Purpose and design

Build a personal portfolio for `daniely1227.github.io` as a quiet, text-first document: light theme, generous whitespace, professional serif headings, neutral sans-serif body text, no hero images or animation, and a responsive single-column layout intended to keep each page readable in one scroll.

## Pages and content

- **Home:** concise factual introduction based on the resume and links to the other pages.
- **About:** education, leadership activities, languages, interests, and other supplied background.
- **Work Experience:** the roles, dates, responsibilities, and outcomes at BofA Securities, National Pension Service, and SK E&S, based only on the resume.
- **Contact:** public email link to `daniel.yun@berkeley.edu` and the LinkedIn link supplied in the resume.

The resume is the sole source for personal facts. Preserve names, titles, dates, figures, credentials, and outcomes as supplied; do not fetch information from LinkedIn or add inferred claims. Use a visible placeholder for any personal bio or other detail the resume does not provide. Do not publish the phone number unless Daniel separately approves it for public display.

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
- The supplied resume may be condensed for readability only when the meaning and all claims remain unchanged.
- The supplied email address is approved for public display as a `mailto:` link; visitors will need an email app to use it.
