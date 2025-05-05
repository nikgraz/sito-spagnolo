# sito-spagnolo
# Docs Directory

This directory is intended to hold the Jekyll site files.
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout repository
        uses: actions/checkout@v2

      - name: Build Jekyll site
        run: |
          cd docs
          bundle exec jekyll build

## Getting Started

Add your Jekyll source files here, such as:
- `_config.yml`
- `index.md` or `index.html`
- `_posts/` directory

Once the directory is set up, you can build the site with:

```bash
bundle exec jekyll build
undefined
