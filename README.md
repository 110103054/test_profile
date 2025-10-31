# Personal Resume Site

This repository hosts a static personal resume webpage written in HTML and CSS.

## Local development

Use any static file server to preview the site locally. For example, with Python installed:

```bash
python3 -m http.server --directory . 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

## Deployment

GitHub Actions automatically publishes the contents of the repository to GitHub Pages when changes are pushed to the `main` branch.

1. Enable GitHub Pages in the repository settings and select **GitHub Actions** as the source.
2. Push commits to `main` (or trigger the workflow manually from the **Actions** tab).
3. Wait for the `Deploy static resume site` workflow to finish; the published URL is available in the deployment summary.
