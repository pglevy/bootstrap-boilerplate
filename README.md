# simple-bootstrap
default jekyll site with bootstrap

## Steps
1. Start with simple jekyll site.
1. Download Bootstrap source files and copy `scss` and `dist/js` folders to `assets/bootstrap`.
1. Update `sass_dir` in `_config.yml` to `assets/bootstrap/scss`.
1. Create placeholder sass file `main.scss` in `assets/css`. (Note .scss file type. Remember to include front matter dashes. And import bootstrap source with `@import "bootstrap";`)

## Notes
- Stylesheet path for built site is `assets/css/main.css`.
- For js, start with slim jQuery using CDN. Then include Bootstrap bundled source (with Popper) locally with `assets/bootstrap/js/bootstrap.bundle.min.js`. (Remember to include .map file in source js folder.)
  - Use [Starter Template](https://getbootstrap.com/docs/4.5/getting-started/introduction/) from Bootstrap site to make `_default` layout.

## Things I may need to edit source code for
- spacers

## Basic branding variables to set
- $font-family-base:            $font-family-sans-serif !default;
- $font-size-base:              1rem !default;
- $primary:       $blue !default;
- $secondary:     $gray-600 !default;
- $link-color:                              theme-color("primary") !default;
- navs
