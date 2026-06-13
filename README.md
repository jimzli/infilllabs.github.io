<div align="center">
  <img src="assets/logo.svg" alt="infill labs logo" width="130">
  <h1>infill labs</h1>
  <p><em>Solid Engineering</em></p>
</div>

Source for [infilllabs.io](https://infilllabs.io) — a minimal single-page site
built with [Jekyll](https://jekyllrb.com) and hosted on GitHub Pages.

## Development

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Details

- **Single page** rendered from `index.html` through `_layouts/default.html`.
- **Styling** lives in `assets/css/style.scss`; the palette is driven by CSS
  variables with an automatic light/dark theme (plus a manual toggle).
- **Output is minified** — HTML via the `_layouts/compress.html` layout and CSS
  via Sass `compressed` output.

## Deployment

Pushing to `main` triggers the GitHub Pages build. The custom domain is set in
`CNAME`.

## Contact

Say hello — [hello@infilllabs.io](mailto:hello@infilllabs.io).
