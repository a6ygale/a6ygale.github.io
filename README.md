# Abygale Cochrane — Research Portfolio

A multi-page, static GitHub Pages portfolio with a dark futuristic electromagnetic-lab aesthetic.

## Pages
- `index.html` — overview, animated wavefront visual, interactive array-factor simulator
- `research.html` — research directions
- `projects.html` — project cards with category filters
- `notes.html` — technical notes and resource index
- `about.html` — background and interests
- `cv.html` — CV-style overview and link placeholders

## Deploy to GitHub Pages

1. Download and unzip this package.
2. Back up your current repository locally or create a branch.
3. Copy the files and folders in this package into the repository root. Merge the new `assets/css`, `assets/js`, and `assets/img` contents with existing `assets` files rather than deleting old material.
4. Review and update all biography, education, job, and project details.
5. Add direct links to existing presentations, lab reports, images, and your current PDF CV.
6. Commit and push to the repository's publishing branch. Check **Settings → Pages** to confirm the correct source branch/folder.

The site uses relative links and should work at `https://a6ygale.github.io/` without a build step.

## Interactive array demo

The browser-only simulator plots the normalized magnitude of the ideal uniform linear array factor:

`AF(θ) = |sin(Nψ/2) / (N sin(ψ/2))|`, where `ψ = 2π(d/λ)(sin θ − sin θ₀)`.

The controls change element count, normalized spacing, steering angle, and a display-frequency label. Because spacing is normalized to wavelength, the plotted ideal array factor is unchanged by the frequency label. The demo assumes isotropic elements, equal amplitudes, a linear array, and far-field conditions. It is illustrative, not validated hardware data.

## Before publishing
- Confirm CV dates, degree status, and current job title.
- Link the actual source for each project and include verified plots/results.
- Add only public-safe descriptions of professional work; do not upload employer-confidential data.
- Replace resource placeholders with checked URLs.
- Test mobile navigation and the array simulator in your browser.
- If your existing repository uses Jekyll or another theme, review `_config.yml` and existing files before merging. This package is plain static HTML/CSS/JS and does not require Jekyll plugins.
