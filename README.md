# ICRI-STE · Statutes, Constitution & Governance

Static website (plain HTML/CSS/JS, no build step) for GitHub Pages.

## Contents

```
index.html              Main page (all statutes content preserved)
404.html                Branded not-found page
robots.txt, sitemap.xml Search-engine files
.nojekyll               Tells GitHub Pages to serve files as-is
assets/
  icri-mark.svg, apple-touch-icon.png, og-image.png   Emblem, icons, social preview
  governance-overview.svg   Hero figure + Appendix A
  research-matrix.svg       Appendix B
  entity-alignment.svg      Appendix C
  strategy-pillars.svg      Appendix D
  research-lifecycle.svg    Appendix E
  integrity-framework.svg   Appendix F
  *.jpeg                    Cover images: CHI, IESST, EIAS labs; BioNexa, Enerlytix, TerraNexa
```

## Deploy on GitHub Pages

1. Create a repository (for a user site: `<username>.github.io`; for a project site: any name, e.g. `Statutes.github.io`).
2. Upload **everything in this folder** (including the hidden `.nojekyll` file and the `assets` folder) to the repository root.
3. Go to **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After about a minute the site is live at `https://<username>.github.io/<repo>/`.

## Before publishing: check the URLs

`index.html`, `sitemap.xml` and `robots.txt` use this address for canonical and social-preview links:

`https://didarmurad2019.github.io/Statutes.github.io/`

If your final address is different, replace it in those three files (and in `404.html`, which links to `/Statutes.github.io/`).

## Editing the figures

The SVG figures are plain text and can be edited in any code editor or in Inkscape/Figma. Fonts fall back to system fonts when viewed as images.
The cover JPEGs are generated illustrations; replace any of them with your own photo by keeping the same file name.

## Notes

- The "Deployment guide" button in the hero links to `README.md`. On GitHub Pages this opens as plain text; change the link to your repository's README page if you prefer.
- The statutes are a proposed framework; the institutional status notice on the page should stay until formal adoption.
