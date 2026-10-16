# Martin Fernandez-Stoll — engineering portfolio site

Plain static site (HTML + CSS, no build step). Pages: `index.html`, `tsat-2a.html`, `kaos-2.html`, `kleo-1.html`, `about.html`.

## Preview locally
Double-click `index.html`.

## Publish on GitHub Pages
1. On github.com, create a new **public** repository. Naming it `<your-github-username>.github.io` gives you the address `https://<your-github-username>.github.io`; any other name gives `https://<username>.github.io/<repo-name>`.
2. Upload the *contents* of this `website` folder (not the folder itself) to the repository root, including the hidden `.nojekyll` file. Easiest: "Add file → Upload files", drag everything in, commit.
3. Repository **Settings → Pages → Build and deployment**: Source "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
4. The site goes live at the address above within a minute or two.

## Editing
Text lives directly in the HTML files; styles in `assets/css/style.css`. Web-sized images are in `assets/img/` (originals stay in the project folders). The flight clip in `assets/video/` is muted and trimmed before the "To Be Continued" ending; the original is untouched in `TSat-2A/images/`.

## Deliberately left out
- Phone number: the downloadable résumé (`assets/Martin_Fernandez-Stoll_Resume.pdf`) is a web copy with the phone line removed. Regenerate it whenever the main résumé changes.
- GNOR boat and the referee dashboard.
- Portfolio PDF link (the PDF isn't built yet).
