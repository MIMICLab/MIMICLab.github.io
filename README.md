# MIMIC Website

This repository contains the source for the MIMIC Lab website. The site is built with [Jekyll](https://jekyllrb.com/) using the [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) theme.


This repository is automatically built via GitHub Actions using Ruby 3.1 and RubyGems 3.3.22.

## Development

1. Install Ruby dependencies:
   ```bash
   bundle install
   ```
2. Serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```

Site configuration lives in `_config.yml` and navigation links can be adjusted in `_data/navigation.yml`.

