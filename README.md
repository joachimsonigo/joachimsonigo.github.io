# joachimsonigo.github.io

Personal website for Joachim Sonigo. This repository is a small static site (HTML/CSS/JS) built from an HTML5 UP template and maintained manually.

Quick start
 - Preview locally: from the repository root run:

```bash
python -m http.server 8000
```

then open `http://localhost:8000/`.

 - Deploy: push to the `main` branch on GitHub and enable GitHub Pages for this repository (source: `main`). The site will be served at `https://joachimsonigo.github.io/`.

Key files
 - `index.html` — homepage
 - `projects.html` and `projects/` — projects index and per-project pages
 - `resume.html` — resume page; upload `assets/Joachim_Sonigo_Resume.pdf` for the download link
 - `sitemap.xml` — search engine sitemap (update when new pages added)
 - `robots.txt` — crawler rules
 - `images/og-card.svg` — OpenGraph preview image used for link previews

Search & analytics
 - Add the site to Google Search Console and submit `https://joachimsonigo.github.io/sitemap.xml`.
 - To enable analytics, replace `MEASUREMENT_ID` in `index.html` with your GA4 measurement id.

How to ask the agent (recommended workflow)
 - Provide the edits you want, e.g. "Add a detailed project page for InnoSat with non-confidential outcomes and link it from `projects.html`."
 - If content is private (company internal), mark it and ask for a public-friendly summary.
 - To publish changes: ask the agent to create a branch, apply changes, run a quick validation, and open a pull request.

Contributing
 - Create a feature branch `feature/<short-desc>`, commit changes, and open a PR to `main`.
 - Keep changes focused and include a short description of the intent in the PR body.

If you'd like, I can commit and push the recent updates and open a PR for you.
