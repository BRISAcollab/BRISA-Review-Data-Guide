# BRISA Review Data Guide

This repository contains the BRISA Review Data Guide, a practical reference for organizing preclinical systematic review and meta-analysis projects and preparing files for a public repository.

The guide is intended to support a more consistent project structure across BRISA teams while allowing different software, platforms, and review designs. It separates two related tasks:

- **Internal workspace:** the complete working record of the review, including drafts, original exports, training files, reviewer-level data, decisions, intermediate files, analyses, and final materials.
- **Public release:** a curated set of final and shareable materials that allows another researcher to understand the review, inspect the data, and reproduce or reuse the work when applicable.

## What the site covers

The guide provides recommended folders for:

1. README and project orientation
2. Administration
3. Protocol and registration
4. Search development, final strategies, exports, and deduplication
5. Screening
6. Data extraction
7. Risk of bias and other assessments
8. Analysis
9. Outputs
10. Manuscript files
11. Public repository preparation
12. Repository selection

Each section includes:

- the purpose of the folder;
- example file names;
- suggested file formats;
- whether the material is normally included in the public release;
- built-in examples of key documents and datasets.

The examples are recommendations, not a fixed list of required files. Projects may add, remove, or adapt folders depending on the review design and the software used.

## Repository files

```text
index.html       Complete site, including embedded CSS
brisa-logo.png   BRISA logo used by the site
.nojekyll        Prevents GitHub Pages from processing the site with Jekyll
LICENSE.md       License for the guide text and original materials
README.md        Repository documentation
```

## Publish with GitHub Pages

1. Place the files above in the root of the repository.
2. Open **Settings → Pages** in GitHub.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`.
5. Save the settings.

GitHub Pages will publish `index.html` as the site homepage.

## Editing the guide

The site uses plain HTML and CSS and does not require a build system.

- Edit page content directly in `index.html`.
- The CSS is embedded in the `<style>` block near the top of `index.html`.
- Keep `brisa-logo.png` in the repository root unless the image path is updated in the HTML.

## Related BRISA resources

BRISA website: https://www.reprodutibilidade.org/brisa

## License

Unless otherwise noted, the original text and documentation in this repository are licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**.

Third-party logos, linked publications, external resources, and materials that have their own licenses are not relicensed by this repository.

See `LICENSE.md` for details.
