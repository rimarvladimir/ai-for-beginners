# AI App Lab

A static website prototype for a beginner-friendly course on validating, building, launching, and marketing an app with AI.

## What's included

- Ten expandable curriculum modules, from idea research to product maintenance.
- A sample lesson and an enrollment preview.
- A downloadable Markdown idea evaluation worksheet.
- A responsive layout built with plain HTML, CSS, and JavaScript.

The course is a concept: lessons are still to be produced, the proposed price is CHF 149, and enrollment is not open. The prototype has no checkout and collects no personal information.

## Preview locally

Open `index.html` directly in your browser, or serve the repository with Python:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>. No installation or build step is required. Google Fonts requires an internet connection; local fallback fonts are used otherwise.

## Files

- `index.html`: page content, styles, curriculum data, and interactions.
- `.nojekyll`: disables Jekyll processing for GitHub Pages.

## Publish with GitHub Pages

1. Push the website files to GitHub.
2. Open the repository's **Settings → Pages**.
3. Choose **Deploy from a branch**, select **main** and **/ (root)**, and save.
4. GitHub will display the published website URL once deployment completes.

## Editing

Edit `index.html` to update the page. Curriculum titles, durations, lessons, and outcomes are defined in the `modules` array near the end of the file. Preview changes in a browser before publishing.
