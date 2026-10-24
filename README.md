# Justin Du

Personal research website: **https://zdoorr.github.io/**

Static HTML and CSS, hosted with GitHub Pages from the `main` branch and root directory. No build step or external dependencies.

## Content

- `index.html`: personal introduction and research list.
- `papers/han-xiong/index.html`: the preprint’s abstract page, bibliographic metadata, and downloads.
- `papers/han-xiong/*.pdf`: the released preprint.
- `papers/han-xiong/*_source.zip`: TeX source and verification materials.
- `assets/style.css`: shared responsive styles.
- `robots.txt` and `sitemap.xml`: crawler discovery.

## Updating

Edit the HTML or replace the relevant research files, then commit and push to `main`. GitHub Pages publishes the changes automatically.

For a new paper, add a separate directory under `papers/`, provide a visible full abstract and a PDF in that directory, and link it from the homepage. Keep the title, author, and publication date consistent across the page’s citation metadata and the PDF. Add its canonical URL to `sitemap.xml`.

The site supports search-engine crawling and scholarly metadata; indexing is controlled by the search engines.
