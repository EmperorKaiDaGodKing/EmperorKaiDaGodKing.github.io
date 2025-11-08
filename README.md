# EmperorKaiDaGodKing.github.io

Official GitHub Pages site for EmperorKaiDaGodKing.

## 🌐 Live Site

Visit the site at: [https://emperorkaidagodking.github.io](https://emperorkaidagodking.github.io)

## 📋 About

This repository hosts the GitHub Pages site for EmperorKaiDaGodKing. It features a professional landing page showcasing projects, portfolio, and contributions.

## 🚀 Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions whenever changes are pushed to the `main` branch.

### Automatic Deployment

The site uses a GitHub Actions workflow (`.github/workflows/deploy.yml`) that:
1. Triggers on push to the `main` branch
2. Can be manually triggered from the Actions tab
3. Builds and deploys the site to GitHub Pages

### Manual Deployment

You can manually trigger a deployment by:
1. Going to the "Actions" tab in this repository
2. Selecting the "Deploy to GitHub Pages" workflow
3. Clicking "Run workflow"

## 🛠️ Local Development

To view the site locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/EmperorKaiDaGodKing/EmperorKaiDaGodKing.github.io.git
   cd EmperorKaiDaGodKing.github.io
   ```

2. Open `index.html` in your web browser:
   ```bash
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   
   # On Windows
   start index.html
   ```

Alternatively, you can use a local web server:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

Then visit `http://localhost:8000` in your browser.

## 📁 Repository Structure

```
EmperorKaiDaGodKing.github.io/
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions deployment workflow
├── index.html                  # Main landing page
├── _config.yml                 # Jekyll configuration
└── README.md                   # This file
```

## 🔧 Configuration

### GitHub Pages Settings

To ensure GitHub Pages is properly configured:

1. Go to your repository settings
2. Navigate to "Pages" section
3. Under "Build and deployment":
   - **Source**: Select "GitHub Actions"
   - This allows the custom workflow to deploy the site

### Jekyll Configuration

The `_config.yml` file contains basic Jekyll configuration for the site. Customize it as needed:

```yaml
title: EmperorKaiDaGodKing's GitHub Domain
description: Official GitHub Pages site for EmperorKaiDaGodKing
author: EmperorKaiDaGodKing
```

## 🎨 Customization

### Updating the Site

1. Edit `index.html` to modify the content
2. Commit and push changes to the `main` branch:
   ```bash
   git add .
   git commit -m "Update site content"
   git push origin main
   ```
3. The site will automatically rebuild and deploy

### Styling

The site uses inline CSS in `index.html`. To modify the appearance:
- Edit the `<style>` section in `index.html`
- The site features a gradient purple theme with modern design elements
- Responsive design adapts to mobile devices

## 📝 Features

- ✨ Modern, professional design with gradient theme
- 📱 Fully responsive for mobile and desktop
- 🎭 Smooth animations and transitions
- 🔗 Direct links to GitHub profile
- 🎨 Clean, organized layout with feature sections
- ⚡ Fast loading and optimized performance

## 🤝 Contributing

This is a personal portfolio site. However, if you notice any issues or have suggestions, feel free to open an issue.

## 📄 License

© 2025 EmperorKaiDaGodKing. All rights reserved.

## 🔗 Links

- **GitHub Profile**: [https://github.com/EmperorKaiDaGodKing](https://github.com/EmperorKaiDaGodKing)
- **Live Site**: [https://emperorkaidagodking.github.io](https://emperorkaidagodking.github.io)