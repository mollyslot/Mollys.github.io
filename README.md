# molly.github.io
# Directory structure
.
├── _config.yml
├── _layouts/
│   ├── default.html
│   ├── post.html
│   └── page.html
├── _posts/
│   └── 2024-11-10-welcome-post.md
├── _includes/
│   ├── header.html
│   ├── footer.html
│   └── sidebar.html
├── assets/
│   ├── css/
│   │   └── style.css
│   └── images/
├── index.html
└── about.md

# _config.yml
title: Your Name
description: Your Blog Description
url: "https://yourusername.github.io"
github_username: yourusername
markdown: kramdown
permalink: /posts/:year/:month/:title/
plugins:
  - jekyll-feed
  - jekyll-seo-tag
  - jekyll-sitemap

# Navigation
header_pages:
  - about.md
  - publications.md
  - projects.md

# Theme settings
theme_settings:
  avatar: assets/images/avatar.jpg
  favicon: assets/favicon.ico
  grid_separator_color: "#DDDDDD"
