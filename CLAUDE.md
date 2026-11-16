# dor-builder

Public web home of the offline DOR Narrative Builder (CHP 115A).
Live at https://runningtarget11.github.io/dor-builder/ (GitHub Pages, main branch, root).

- `index.html` is the builder. It is the same page as `dor.html` in road-dog-download, plus
  iPhone home-screen tags (apple-mobile-web-app-*, apple-touch-icon.png).
- Version rule: the builder also exists as a claude.ai artifact and as road-dog-download/dor.html.
  All copies share one version number (`<p id="ver">`). Bump it everywhere for every change and
  keep `(offline)` on the hosted copies.
- iPhone users open the link in Safari and use Share → Add to Home Screen.
