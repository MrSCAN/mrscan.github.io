# Chinonso Ngwu — Personal Portfolio

Live site: https://mrscan.github.io/

A minimal, modern, single-page portfolio for Chinonso Ngwu, Full-Stack Software Engineer at Cisco Meraki specializing in Edge AI and Computer Vision.

## Structure

- `index.html` — the entire site (self-contained HTML + CSS + tiny vanilla JS, no build step, no jQuery, no Bootstrap).
- `assets/Chinonso_Ngwu_CV.pdf` — downloadable CV linked from the nav and hero.
- `favicon.png` — site favicon.
- `index.old.html` — backup of the previous Bootstrap-based template.
- `projects/` — legacy project detail pages (kept for now; not linked from the new homepage).
- `assets/img/`, `assets/vendor/`, etc. — legacy assets from the previous template.

## Deployment

Pushed to the `master` branch of the `mrscan.github.io` repo; served via GitHub Pages at the root domain.

## Updating the CV

1. Re-generate the PDF (from the CVs folder one level up).
2. Copy it in:
   ```sh
   cp ../Chinonso_Ngwu_CV.pdf assets/Chinonso_Ngwu_CV.pdf
   ```
3. Commit and push.

## License

[MIT](http://opensource.org/licenses/mit-license.php)
