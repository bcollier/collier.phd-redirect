# collier.phd redirect

Sends every path on collier.phd (and www.collier.phd) to the same path on
https://ben.collier.phd, where the site lives (repo: bcollier/ben.collier.phd).
`404.html` is a copy of `index.html`, so deep links like collier.phd/cv/ keep
their path. Served by GitHub Pages.

Mail for @collier.phd is Google Workspace and is unaffected: only the apex A
records and the `www` CNAME point at GitHub Pages.
