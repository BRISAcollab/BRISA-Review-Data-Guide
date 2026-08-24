# BRISA Project Data Management and Sharing Guide

This repository contains the BRISA Project Data Management and Sharing Guide, the BRISA Quick Start, and downloadable project templates for preclinical systematic review and meta-analysis projects.

The guide supports a consistent internal project structure across BRISA teams and separates two related records:

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

The Quick Start identifies BRISA requirements. The detailed guide distinguishes required, conditional, recommended, internal-only, and public-release materials. Groups outside BRISA may adapt the structure to their own institutional requirements.

## Download packages

- `downloads/BRISA_PROJECT_TEMPLATE_BLANK.zip`: standard folder structure and blank starting files.
- `downloads/BRISA_PROJECT_TEMPLATE_WORKED_EXAMPLE.zip`: the same structure populated with synthetic examples.

The packages are distributed with the website. No Google Drive access is required to download them.

## Repository files

```text
index.html       Complete site, including embedded CSS
brisa-logo.png   BRISA logo used by the site
downloads/       Downloadable blank and worked-example project packages
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
- Keep `brisa-logo.png` and the `downloads/` folder in the repository root unless their paths are updated in the HTML.

## Related BRISA resources

BRISA website: https://www.reprodutibilidade.org/brisa

## License

Unless otherwise noted, the original text and documentation in this repository are licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**.

Third-party logos, linked publications, external resources, and materials that have their own licenses are not relicensed by this repository.

See `LICENSE.md` for details.
