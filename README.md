MASK INTELLIGENCE BLOG: 

🎯 Project Overview

Mask Intelligence is a professional digital solutions blog built with Jekyll and GitHub Pages. This repository serves as both a business website and a content hub for sharing insights on web development, digital transformation, and intelligent business solutions.

🏗️ Technology Stack

· Framework: Jekyll (Minimal Mistakes theme)
· Hosting: GitHub Pages
· CSS: Custom SCSS with CSS Variables
· Forms: Formspree integration
· Icons: Font Awesome 6
· Feed: Atom/RSS (Auto-generated)

📁 Repository Structure

```
mask-intelligence-blog/
├── _data/                    # Site data (navigation, authors)
│   └── navigation.yml        # Main & footer navigation
├── _includes/               # Reusable components
│   ├── footer.html          # Custom footer (Formspree + RSS)
│   ├── social-share.html    # Social sharing buttons
│   └── head/custom.html     # Custom CSS/JS injections
├── _layouts/               # Page templates
│   ├── default.html        # Base layout
│   └── post.html          # Blog post layout
├── _pages/                # Static pages
│   ├── about.md           # About Mask Intelligence
│   ├── services.md        # Services offered
│   ├── contact.md         # Contact information
│   └── subscribe.md       # Subscription options
├── _posts/               # Blog posts
│   └── 2025-01-19-unveiling-digital-potential.md
├── assets/
│   ├── css/
│   │   └── main.scss     # Custom styles
│   └── images/           # Site images
├── _config.yml           # Jekyll configuration
└── index.html           # Homepage
```

🚀 Quick Start

1. Local Development

```bash
# Install Ruby and Jekyll
gem install bundler jekyll

# Clone repository
git clone https://github.com/maskintelligence-gif/mask-intelligence-blog.git

# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve

# Visit http://localhost:4000
```

2. GitHub Pages Deployment

· Automatic: Push to main branch
· URL: https://maskintelligence-gif.github.io/mask-intelligence-blog/
· Build time: ~1-2 minutes after push

🎨 Customization Guide

Colors (Edit /assets/css/main.scss)

```scss
:root {
  --primary-color: #2563eb;      /* Brand blue */
  --accent-color: #f59e0b;       /* Accent orange */
  --text-color: #1f2937;         /* Dark text */
  --background-color: #ffffff;   /* Light background */
}
```

Navigation (Edit /_data/navigation.yml)

```yaml
main:
  - title: "Services"
    url: /services/
  - title: "Blog"
    url: /posts/
  - title: "Contact"
    url: /contact/
```

Services (Edit /_pages/services.md)

Update the services list and pricing in the markdown file.

📧 Form Integrations

1. Formspree (Newsletter/Contact)

· Endpoint: https://formspree.io/f/xldqaaoe
· Dashboard: https://formspree.io
· Emails sent to: maskintelligence@gmail.com

2. Form Setup

```html
<form action="https://formspree.io/f/xldqaaoe" method="POST">
  <input type="hidden" name="_subject" value="New Message">
  <input type="email" name="email" required>
  <button type="submit">Send</button>
</form>
```

🔗 Social Media & RSS

Connected Platforms:

· Facebook: https://facebook.com/profile.php?id=61586114142835
· LinkedIn: https://linkedin.com/in/mask-intelligence-603348378
· GitHub: https://github.com/maskintelligence-gif
· Email: maskintelligence@gmail.com
· Phone: +256 791 715 573

RSS Feed:

· URL: /feed.xml
· Feedly: Pre-configured link in footer
· Auto-updates: With each new post

📝 Adding New Content

Blog Posts:

```bash
# Create new post
_posts/YYYY-MM-DD-title.md

# Front matter template:
---
title: "Post Title"
date: YYYY-MM-DD
categories: [Category]
tags: [tag1, tag2]
---
```

Static Pages:

```bash
# Create new page
_pages/page-name.md

# Layout options: single, splash, post
```

🛠️ Maintenance

Regular Updates:

1. Update services/pricing in services.md
2. Add portfolio/case studies to _posts/
3. Test all forms monthly
4. Check broken links quarterly

Backup:

· Automatic: GitHub repository
· Manual: Download ZIP from GitHub
· Content: All in markdown files

📊 Analytics & SEO

Recommended Integrations:

1. Google Analytics: Add to _includes/head/custom.html
2. Search Console: Submit sitemap sitemap.xml
3. Meta Tags: Configure in _config.yml

SEO Checklist:

· Responsive design
· Semantic HTML
· Alt text for images
· Meta descriptions
· XML sitemap
· RSS feed

🤝 Contributing

1. Fork the repository
2. Create branch: git checkout -b feature/description
3. Commit changes: git commit -m 'Add feature'
4. Push: git push origin feature/description
5. Pull Request

📞 Support

Technical Issues:

· GitHub Issues: https://github.com/maskintelligence-gif/mask-intelligence-blog/issues
· Email: maskintelligence@gmail.com

Business Inquiries:

· WhatsApp: +256 791 715 573
· Email: maskintelligence@gmail.com
· Website: https://mask-intelligence.web.app

📄 License

· Theme: MIT (Minimal Mistakes)
· Content: © 2013-2025 Mask Intelligence
· Code: Custom modifications proprietary to Mask Intelligence

🏆 Credits

· Theme: Michael Rose (Minimal Mistakes)
· Development: Mask Intelligence Team
· Icons: Font Awesome
· Hosting: GitHub Pages

---

Mask Intelligence – Unveiling Digital Potential Through Intelligent Solutions

Last Updated: {{ site.time | date: '%B %d, %Y' }}

---

📋 Deployment Status

https://img.shields.io/github/deployments/maskintelligence-gif/mask-intelligence-blog/github-pages?label=GitHub%20Pages
https://img.shields.io/badge/Jekyll-4.2.2-blue
https://img.shields.io/badge/License-Proprietary-lightgrey

Live Site: https://maskintelligence-gif.github.io/mask-intelligence-blog/
Business Site:https://mask-intelligence.web.app

```
