## Muscarella Lab Website

This repository contains the GitHub Pages site for the Muscarella Lab, built with Jekyll and the Minimal Mistakes theme.

## Local Development

This repo uses the `github-pages` gem and requires **Ruby 3.3** and **Bundler 2.5.20**.
Install Ruby 3.3 via Homebrew if needed: `brew install ruby@3.3`

1. Install the required Bundler version:

```bash
/opt/homebrew/opt/ruby@3.3/bin/gem install bundler:2.5.20
```

2. Install dependencies:

```bash
/opt/homebrew/opt/ruby@3.3/bin/bundle _2.5.20_ install
```

3. Build the site:

```bash
/opt/homebrew/opt/ruby@3.3/bin/bundle _2.5.20_ exec jekyll build
```

4. Serve locally:

```bash
/opt/homebrew/opt/ruby@3.3/bin/bundle _2.5.20_ exec jekyll serve
```

## Notes

- Main content pages live in `_pages/`.
- Navigation links are configured in `_data/navigation.yml`.
- Static files are in `assets/`.
