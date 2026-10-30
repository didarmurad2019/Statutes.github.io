# ICRI-STE Statutes Website — Complete Package

A responsive, professional static website for the International Council for Research & Innovation in Science, Technology & Engineering (ICRI-STE).

## Package contents
- `index.html` — complete statutes website and navigation.
- `assets/styles.css` — responsive design system, mobile layout and print stylesheet.
- `assets/site.js` — mobile navigation, in-page section tracking and searchable statutes.
- `assets/icri-mark.svg` — original vector site mark.
- `assets/governance-overview.svg` — governance and laboratory structure.
- `assets/research-matrix.svg` — laboratory research domains.
- `assets/entity-alignment.svg` — lab-to-LLC research alignment.
- `assets/strategy-pillars.svg` — strategic research pillars infographic.
- `assets/research-lifecycle.svg` — research lifecycle diagram.
- `assets/integrity-framework.svg` — research integrity infographic.
- `assets/bionexa.svg`, `assets/enerlytix.svg`, `assets/terranexa.svg` — illustrative entity graphics.

All illustrations are original SVG vector assets. They scale cleanly on desktop and mobile and are stored in the `assets/` folder.

## Publish on GitHub Pages
1. Download and extract the ZIP.
2. Upload the *contents* of the extracted folder to the root of your GitHub repository.
3. Confirm that `index.html` is at the repository root and the `assets` folder sits beside it.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
6. Wait for GitHub Pages to complete deployment. Use the published URL shown in Settings → Pages.

## Editing
- Update wording in `index.html`.
- Adjust visual styling in `assets/styles.css`.
- Update navigation/search behaviour in `assets/site.js`.
- Replace SVGs in `assets/` with approved institutional brand artwork when available; preserve filenames or update the references in `index.html`.

## Governance and legal notice
This web edition is a consolidated publication layout organised into 15 Parts and 62 provisions. It is not a verbatim conversion of the earlier 133-article master draft. Reconcile it with the approved master statutes before formal adoption. Confirm ICRI-STE's legal form, jurisdiction, authorised office-holders, adoption process and any required registrations with appropriate professional advice.

BioNexa Intelligence, LLC, Enerlytix Technologies, LLC and TerraNexa Intelligence, LLC are described as associated by research alignment only. This package does not assert that they are subsidiaries, owned by ICRI-STE, or covered by ICRI-STE's liabilities.


## Laboratory and company photographs
The updated `index.html` references six JPEG photographs. Place these files directly inside the existing `assets/` folder, preserving the filenames exactly:

**Laboratories**
- `Computational_Healthcare_Intelligence_(CHI)_Lab.jpeg`
- `Intelligent_Energy_Systems_&_Sustainable_Technologies_(IESST)_Lab.jpeg`
- `Environmental_ Intelligence_&_Autonomous_Systems_(EIAS)_Lab.jpeg`

**Associated innovation entities**
- `BioNexa_Intelligence LLC.jpeg`
- `Enerlytix_Technologies_LLC.jpeg`
- `TerraNexa_Intelligence_LLC.jpeg`

The JPEG photographs are not bundled in this archive because they are to be added to `assets/` by the site owner. The HTML uses URL-encoded paths for spaces and ampersands; do not rename the files.
