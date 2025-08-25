# Lomond Robotics website

Static site built with Hugo and deployed via GitHub Actions to GitHub Pages.

Live: `https://michaeljirasek.com/lomondrobotics/`

## Local development

1. Install Hugo Extended.
2. Run: `hugo server -D`
3. Build: `hugo`

## Deployment

Push to `main`. The workflow at `.github/workflows/gh-pages.yml` builds and publishes the `public/` folder to GitHub Pages.
