# Xiangxiang Chu Personal Website

This repository hosts the GitHub Pages site for Xiangxiang Chu (初祥祥), including research profile, publications, CV, AMAP-ML team information, news, and media coverage.

The site is based on Jekyll and AcademicPages/Minimal Mistakes, with local content and styling customized for the current profile.

## Local Development

Use the checked-in wrapper so this older Jekyll stack works with modern Ruby:

```bash
bin/jekyll-local build --config _config.yml,_config.dev.yml
bin/jekyll-local serve --host 127.0.0.1 --port 4000 --config _config.yml,_config.dev.yml
```

With the Miniforge environment created for this workspace:

```bash
conda run -n jekyll-site bin/jekyll-local build --config _config.yml,_config.dev.yml
conda run -n jekyll-site bin/jekyll-local serve --host 127.0.0.1 --port 4000 --config _config.yml,_config.dev.yml
```

## Quality Checks

Before publishing content changes, run:

```bash
git diff --check
conda run -n jekyll-site bin/jekyll-local build --config _config.yml,_config.dev.yml
```

For visible page changes, also inspect the generated site locally at `http://127.0.0.1:4000/`.
