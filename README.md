# 兔猫的博客

一个采用苹果设计风格的现代博客，使用Jekyll构建并托管在GitHub Pages上。

## 特色功能

- 🎨 **苹果风格设计**：简洁现代的界面，流畅的动画效果
- 📱 **响应式设计**：在所有设备上完美运行
- 🌙 **深色模式支持**：基于系统偏好的自动深色模式
- 📝 **完整博客功能**：文章、分类、标签、归档和RSS订阅
- ⚡ **快速性能**：针对速度和核心Web指标进行优化
- ♿ **无障碍访问**：遵循无障碍最佳实践构建
- 🔍 **SEO优化**：元标签、结构化数据和站点地图

## Quick Start

### Local Development

1. Install Ruby and Jekyll:
   ```bash
   # On macOS
   brew install ruby
   gem install jekyll bundler

   # On Windows
   # Download and install Ruby from https://rubyinstaller.org/
   gem install jekyll bundler
   ```

2. Clone and setup:
   ```bash
   git clone https://github.com/rabbicat-cx/rabbicat-cx.github.io.git
   cd rabbicat-cx.github.io
   bundle install
   ```

3. Run locally:
   ```bash
   bundle exec jekyll serve
   ```

4. Open http://localhost:4000 in your browser

### GitHub Pages Deployment

This blog is configured to work with GitHub Pages out of the box:

1. Push your changes to the `main` branch
2. Enable GitHub Pages in repository settings
3. Your site will be available at `https://rabbicat-cx.github.io`

## Writing Posts

Create new posts in the `_posts` directory with the format:
```
YYYY-MM-DD-title.md
```

Example post structure:
```markdown
---
layout: post
title: "Your Post Title"
date: 2024-01-25 10:00:00 +0000
categories: [Category1, Category2]
tags: [tag1, tag2, tag3]
author: RabbiCat
---

Your post content here...
```

## Customization

### Site Configuration

Edit `_config.yml` to customize:
- Site title and description
- Social media links
- Author information
- SEO settings

### Styling

The design system is built with CSS custom properties in `assets/css/main.scss`:
- Colors and themes
- Typography scale
- Spacing system
- Component styles

### Adding Pages

Create new pages by adding `.md` or `.html` files in the root directory with front matter:
```markdown
---
layout: page
title: "Page Title"
permalink: /page-url/
---

Page content here...
```

## Design System

This blog uses an Apple-inspired design system with:

- **Typography**: Inter font family with a modular scale
- **Colors**: Carefully chosen palette with dark mode support
- **Spacing**: 8-point grid system for consistent layouts
- **Components**: Reusable UI components with smooth animations

## Browser Support

- Chrome/Edge 88+
- Firefox 85+
- Safari 14+
- Mobile browsers with modern CSS support

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally
5. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## Credits

- Design inspired by Apple's Human Interface Guidelines
- Built with [Jekyll](https://jekyllrb.com/)
- Hosted on [GitHub Pages](https://pages.github.com/)
- Typography using [Inter](https://rsms.me/inter/) font family