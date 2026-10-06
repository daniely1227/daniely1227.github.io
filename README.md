# Daniel Yun — GitHub Pages portfolio

This repository is the complete Jekyll source for the GitHub user site at [daniely1227.github.io](https://daniely1227.github.io). The website files are at the repository root so GitHub Pages can publish directly from `main` and `/ (root)`.

## Update the site

- Edit `index.md`, `about.md`, `work-experience.md`, or `contact.md` to update page content.
- Shared page structure is in `_layouts/default.html`; navigation and footer are in `_includes/`.
- Visual styles are in `assets/css/main.css`; the favicon is `assets/favicon.svg`.
- Keep portfolio facts limited to details Daniel has supplied. The About page marks the missing biography as a placeholder.
- The public email and LinkedIn link are in `contact.md` and `_includes/footer.html`. The phone number is intentionally not displayed.
- `_config.yml` sets the user-site URL and leaves `baseurl` empty. Internal links use Jekyll's `relative_url` filter.
- `jekyll-seo-tag` supplies page metadata and `jekyll-sitemap` generates `sitemap.xml`.

## Preview locally

Install Ruby and Bundler, then from the repository root run:

```sh
bundle install
bundle exec jekyll serve
```

Open <http://127.0.0.1:4000>. Jekyll rebuilds the site when source files change.

## Publish with GitHub Pages

1. Use `daniely1227.github.io` as the GitHub repository name.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose branch **main** and folder **/(root)**, then save.

GitHub Pages builds the Jekyll site from the root; no separate generated-site folder or manual build step is needed.

For a new public repository, upload the current site source rather than copying the development/checkpoint Git history. The uploaded resume has been removed from the current source tree, but earlier development commits may still contain it.

## Run Lighthouse

1. Start the local preview with `bundle exec jekyll serve`.
2. Open <http://127.0.0.1:4000> in Chrome.
3. Open Developer Tools → **Lighthouse**, run an audit for both Mobile and Desktop, and review Performance, Accessibility, Best Practices, and SEO.

The goal is at least 90 in each category. Use the audit findings to guide any future changes.

### Verified local results

Latest Lighthouse runs on October 6, 2026:

| Page | Mobile Performance | Desktop Performance | Accessibility | Best Practices | SEO |
| --- | ---: | ---: | ---: | ---: | ---: |
| Home | 99 | 100 | 100 | 100 | 100 |
| About | 98 | 100 | 100 | 100 | 100 |
| Work Experience | 100 | 100 | 100 | 100 | 100 |
| Contact | 99 | 100 | 100 | 100 | 100 |

Accessibility, Best Practices, and SEO results were 100 on both mobile and desktop. Scores can vary with the test environment.

## Choices and assumptions

- System fonts provide professional serif headings and neutral sans-serif body text without external font requests.
- GitHub Pages-supported Jekyll plugins provide SEO tags and a sitemap. The site uses no JavaScript or third-party trackers.
- A standalone personal biography was not supplied, so it is marked as a placeholder.
- The supplied email address is approved for public display; the phone number is not displayed.
