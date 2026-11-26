# SH NEXT VELORA / ALHAF WEBORIX Portfolio

## GitHub Pages deployment
1. Extract this ZIP. The six HTML pages are at the project root.
2. Create/open your GitHub repository and upload the **contents** of this folder (not an enclosing folder).
3. Commit the files to the `main` branch.
4. Open **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
6. After GitHub finishes publishing, your site URL will be:
   `https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/`

## Contact configuration
Contact details are configured in `js/config.js`:
- Email: alhafshorim@gmail.com
- WhatsApp: +92 307 8626828

## Repair report
- Flattened the ZIP so `index.html` and the other pages are at repository root.
- Verified all six pages reference `css/style.css`, `js/config.js`, and `js/main.js` using relative paths.
- Fixed the missing `assets/image/globe.png` reference by adding a generated globe illustration at that exact path.
- Added a subtle animated space ambience to non-home pages; the home page's existing background remains unchanged.
- Enabled continuous 360-degree globe/image rotation.
- Replaced placeholder email and WhatsApp settings with the supplied contact details.
- Static path audit: no missing local HTML/CSS asset references and no root-relative local references found.
- HTML parser pass and CSS syntax parser pass.
- Note: this is a static source/path validation, not a live browser run on GitHub Pages. External CDN assets still require an internet connection.
