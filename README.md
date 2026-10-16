# Sriram Mahalingam — Personal Website

A responsive, accessible static portfolio based on the October 2026 resume. No dependencies, build step, tracking, or backend.

## Publish with GitHub Pages

1. Sign into https://github.com/sri50183309 and create a public repository named `sri50183309.github.io`. If it already exists, review its contents before replacing anything.
2. Upload `index.html`, `styles.css`, `favicon.svg`, and `.nojekyll` to the repository root. Do not upload the ZIP file itself.
3. Open Settings → Pages. Under Build and deployment, select **Deploy from a branch**, then `main` and `/ (root)`. Save.
4. When GitHub finishes deployment, visit https://sri50183309.github.io/.

## Edit content

Edit `index.html` for text and links; edit `styles.css` for presentation. All asset paths are relative, so the site also works under a project repository path.

The site uses the supplied LinkedIn URL rather than the different URL in the resume. It includes the resume's email address, but omits the phone number, certification credential number, and raw resume download. Metrics are supplied resume claims, not independently verified. Career headings describe work areas rather than asserting an office title.

## Local preview

Run `python3 -m http.server 8000` in this folder and open http://localhost:8000.
