# Building Energy Ontology Studio — public course viewer

This folder is a **safe, read-only GitHub Pages edition** of the student's local course application.
It contains only public research documentation text, precomputed ontology data, and downloadable teaching datasets.
It does not contain Neo4j credentials, local database files, user-uploaded documents or private source material.

## Publish without buying a domain (GitHub Pages)

1. Sign in to GitHub and select **New repository**. Set repository name to `building-energy-ontology-studio`; choose **Public**.
2. Unzip this archive on your computer. Upload **all contents of this folder** to the repository root (including `index.html`, `app.js`, `style.css`, `site_data.json`, and `downloads/`). Do not upload the zip itself as a single file.
3. In the repository, go to **Settings > Pages > Build and deployment**. Choose **Deploy from a branch**, branch **main**, folder **/(root)**; save.
4. Once GitHub indicates the site is deployed, open the exact public URL shown in Pages settings. A typical project URL has the form `https://YOUR-GITHUB-USERNAME.github.io/building-energy-ontology-studio/`.
5. Test **Overview**, **Documents**, **10-stage Pipeline**, **Ontology**, **Knowledge graph** and **Exports** from a different browser/device.

The GitHub URL is not real until **you** upload the files and enable Pages. This public viewer is static: teachers can explore the existing research data but cannot upload new documents or run Python/Neo4j remotely. The full local Python app retains those features.

## Local test (optional)

Open a terminal in the folder and run `py -m http.server 8502`; then open `http://127.0.0.1:8502/`. The JSON data may not load if you double-click `index.html` directly under file://.

## Version and provenance

- 19 real records from an earlier verified Scrapy 2.20 crawl.
- 25 ontology concepts, 39 page-to-concept relations.
- Graph shown is an exported **precomputed** graph, not a live remote Neo4j query.
- Data and computed results are classwork, not generated live by GitHub Pages.
