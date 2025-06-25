# Site settings
title: Astromars
description: A brief description of your site
author: Astromars
email: your.email@example.com
url: "https://docs.github.com/pages"
baseurl: "" # subpath of your site, e.g. /blog

# Build settings
markdown: kramdown
highlighter: rouge
permalink: pretty

# Jekyll plugins
plugins:
  - jekyll-feed
  - jekyll-sitemap
  - jekyll-seo-tag

# Theme (uncomment if using a specific theme)
# theme: minima
# remote_theme: pages-themes/minimal@v0.2.0

# Exclude files from processing
exclude:
  - Gemfile
  - Gemfile.lock
  - node_modules
  - vendor/bundle/
  - vendor/cache/
  - vendor/gems/
  - vendor/ruby/
  - README.md
  - LICENSE
  - .gitignore

# Include files that start with underscore
include:
  - _pages

# Collections (uncomment if needed)
# collections:
#   posts:
#     output: true
#     permalink: /:collection/:name/

# Default front matter
defaults:
  - scope:
      path: ""
      type: "posts"
    values:
      layout: "post"
      author: "Astromars"
  - scope:
      path: ""
      type: "pages"
    values:
      layout: "page"

# Social links (optional)
github_username: astromars
twitter_username: astromars
linkedin_username: astromars

# Google Analytics (optional)
# google_analytics: UA-XXXXXXXX-X

# Pagination (if using jekyll-paginate)
# paginate: 5
# paginate_path: "/page:num/"

# Timezone
timezone: UTC

# Encoding
encoding: utf-8

# Sass configuration
sass:
  style: compressed
  sass_dir: _sass

# GitHub Pages safe mode
safe: true
incremental: false
lsi: false

*Created with ❤️ by Woodyl7*
