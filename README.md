# Justin Du

Personal research website: **https://zdoorr.github.io/**

Static HTML and CSS, hosted with GitHub Pages from the `main` branch and root directory. No build step or external dependencies.

## Content

- papers/gatzweiler-krattenthaler/: the Gatzweiler-Krattenthaler preprint, full abstract, TeX source, verification package, citation metadata, and SHA-256 checksums.

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

## Versioned preprint archives

The Gatzweiler-Krattenthaler preprint, version 1, is archived in the immutable GitHub release [gatzweiler-krattenthaler-v1](https://github.com/zdoorr/zdoorr.github.io/releases/tag/gatzweiler-krattenthaler-v1). Its PDF, TeX source, source-and-verification ZIP, and checksum file are attached to the release. GitHub locks the release assets and associated tag; later manuscript revisions should receive new version identifiers.

Version 2 is the current Gatzweiler-Krattenthaler manuscript, archived in the immutable release [gatzweiler-krattenthaler-v2](https://github.com/zdoorr/zdoorr.github.io/releases/tag/gatzweiler-krattenthaler-v2). It includes the clarified Lemma 5.1 proof, a renewed review record, and a self-contained package manifest. The original version-1 release and files are retained.

## Proposed conjectures

The five English version-2 notes are grouped after the two main papers on the homepage. `papers/conjectures/` contains the collection page, five individual abstract pages and PDFs, BibTeX entries, checksums, and a shared English-source-and-verification supplement. The general statements remain open; the maximum-ambiguity note is an open extremal problem. First public posting: 14 November 2026.
