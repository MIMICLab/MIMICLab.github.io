# MIMIC Website

This repository contains the source for the MIMIC Lab website. The site is built with [Jekyll](https://jekyllrb.com/) using the [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) theme.

## Development

1. Install Ruby dependencies:
   ```bash
   bundle install
   ```
2. Serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```

GitHub Actions automatically upgrades RubyGems to 3.3.16 before building the
site to ensure compatibility with the Minimal Mistakes theme.

Site configuration lives in `_config.yml` and navigation links can be adjusted in `_data/navigation.yml`.

