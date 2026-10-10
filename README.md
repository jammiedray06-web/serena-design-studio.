# Serena Design Studio — Starter Prototype

This is a mobile-friendly browser prototype, not yet a native Android app.

## How to preview on an Android phone
1. Download and extract `serena_design_studio_starter.zip`.
2. Open `index.html` in a browser or upload the files to a static host such as GitHub Pages.
3. For a public hosted version, create a public GitHub repository, upload `index.html`, then enable GitHub Pages in the repository's Settings > Pages.
4. Keep in mind GitHub Pages sites are public. Do not put private measurement data or personal images in the repository.

## Features in this prototype
- Garment type and style option controls with a simple concept preview.
- Extended size-label list through 7XL and region selection.
- Body measurement entry and inch/cm conversion.
- Reference image upload and touch-friendly drawing canvas.
- Sketch PNG download.
- Experimental elastic-waist rectangular skirt pattern calculations.
- Full-size SVG download with a 5 cm calibration square.
- Basic sewing notes download.

## Important limitations
- This prototype does not yet generate a PDF pattern; it exports an SVG at physical dimensions and text instructions. Print at 100% / actual size and verify the calibration square.
- The skirt pattern is an experimental first draft, not a validated commercial pattern. Sew a test garment and validate fit and construction.
- International numerical size conversion charts are not yet implemented. Regional labels vary; use body measurements as the drafting source until a named, verified chart is added.
- The preview is an illustration, not garment geometry.
- Saved measurements and design briefs use browser local storage on that device only.
- No account system, cloud sync, payments, analytics, or Play Store package is included.

## Next development steps
1. Verify all calculations and physical dimensions with a sewing professional and test garments.
2. Add unit tests for pattern geometry.
3. Add verified, source-attributed regional sizing tables, including plus sizes.
4. Implement tiled multi-page PDF output and test with print calibration.
5. Build more garment-specific pattern engines (tops, dresses, trousers, jackets, children's clothing).
6. Port the stable feature set to Flutter or another Android framework, test on devices, then prepare a signed Android App Bundle.
7. Complete Google Play developer registration, privacy disclosures, and required testing before production release.
