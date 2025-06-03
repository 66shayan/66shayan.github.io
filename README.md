# Jekyll RTL Theme

A minimalistic Jekyll theme with RTL support, perfect for Persian/Arabic blogs.

## Features

- Clean, minimalistic design
- Full RTL support
- Responsive layout for all devices
- Custom font integration (Dana font family)
- Blog post listing with excerpts
- Archive page with posts grouped by date
- Customizable through _config.yml

## Installation

1. Fork this repository
2. Edit the `_config.yml` file to customize your blog settings
3. Replace the sample posts in `_posts` directory with your own content
4. Push to your GitHub repository
5. Enable GitHub Pages in your repository settings

## Customization

### Site Configuration

Edit the `_config.yml` file to change:

```yaml
# Site settings
title: "وبلاگ مینیمال"  # Your blog title
title_en: "Minimal Blog"  # English version of your title
description: "یک وبلاگ مینیمال با طراحی ساده و زیبا برای نوشته‌های فارسی"
description_en: "A minimal blog with simple and beautiful design for Persian writings"

# Author information
author:
  name: "نام نویسنده"  # Your name
  name_en: "Author Name"  # English version of your name
  email: "info@example.com"  # Your email

# Theme customization
theme_color: "#ff6719"  # Primary color
text_color: "#222"  # Main text color
light_text: "#757575"  # Secondary text color
background_color: "#fff"  # Background color
border_color: "#e6e6e6"  # Border color
```

### Creating Posts

Create new posts in the `_posts` directory with the following format:

```markdown
---
layout: post
title: "عنوان مطلب"
date: YYYY-MM-DD
read_time: 5
categories: [دسته‌بندی]
---

محتوای مطلب شما...
```

## Directory Structure

```
jekyll-rtl-theme/
├── _includes/       # Reusable components
├── _layouts/        # Page templates
├── _posts/          # Blog posts
├── assets/          # Static assets
│   ├── css/         # Stylesheets
│   ├── fonts/       # Font files
│   └── images/      # Images
├── _config.yml      # Site configuration
├── index.html       # Homepage
├── about.md         # About page
└── archive.html     # Archive page
```

## License

This theme is open source under the MIT license.
