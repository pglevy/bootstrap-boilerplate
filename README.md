# simple-bootstrap
default jekyll site with bootstrap

## Steps
1. Start with simple jekyll site.
1. Download Bootstrap source files and copy `scss` and `js` folders to `assets/bootstrap`.
1. Update `sass_dir` in `_config.yml` to `assets/bootstrap/scss`.
1. Create placeholder sass file `main.scss` in `assets/css`. (Note .scss file type. Remember to include front matter dashes. And import bootstrap source with `@import "bootstrap";`)

## Notes
- Stylesheet path for built site is `assets/css/main.css`.
- For js, start with slim jQuery using CDN. Then include Bootstrap bundled source (with Popper) locally with `assets/bs/js/bootstrap.bundle.min.js`. (Remember to include .map file in source js folder.)
