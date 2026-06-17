# zuotian1012.github.io

Personal homepage for GitHub Pages: <https://zuotian1012.github.io>

## What Changed

The repository originally contained a Hugo Academic template and generated files under `public/`, but there was no `index.html` at the repository root. If GitHub Pages is configured to publish from `main / root`, that causes the site URL to show a 404.

This repository now includes a root-level static homepage:

- `index.html` - the published homepage
- `404.html` - redirects unknown paths back to the homepage
- `.nojekyll` - tells GitHub Pages to serve files directly without Jekyll processing
- `assets/site/hero-visual.png` - the homepage hero image

## How To Edit

Open `index.html` and personalize:

- the short introduction in the About section
- email, CV, Scholar, or LinkedIn links in the Contact section
- real project titles and descriptions under the Projects section
- coursework and skills in the Background section

## How To Publish

Commit and push these files to `main`. In GitHub:

1. Go to repository Settings.
2. Open Pages.
3. Set Source to `Deploy from a branch`.
4. Select branch `main` and folder `/root`.
5. Save and wait 1-3 minutes.

Then visit <https://zuotian1012.github.io>.
