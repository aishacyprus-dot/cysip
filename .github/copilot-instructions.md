# GitHub Copilot – Custom Instructions for CYSIP

## Project Overview
This repository hosts the static website for CYSIP (Circular Insulation Solutions), deployed via GitHub Pages. The site showcases sustainable insulation panels made from sheep wool waste.

## Technology Stack
- **Deployment**: GitHub Pages (main branch / root)
- **Content**: Static HTML, CSS, and JavaScript
- **Custom Domain**: www.cysip.com
- **Build Tool**: None (static files only, Jekyll processing disabled via `.nojekyll`)

## HTML Standards
- Use HTML5 doctype: `<!doctype html>`
- Include proper `<meta>` tags for charset (UTF-8) and viewport
- Ensure all HTML is semantic and accessible
- Use proper document structure with `<head>` and `<body>` sections
- Include descriptive `<title>` and `<meta name="description">` tags for SEO

## Styling Guidelines
- Keep CSS organized and maintainable
- Use responsive design principles for mobile compatibility
- Follow mobile-first approach with viewport meta tag
- Maintain consistent spacing and layout across pages

## Content Guidelines
- All content should reflect CYSIP's focus on circular economy and sustainability
- Company contact: joanna@cysip.com
- Brand name: CYSIP (all caps)
- Main theme: Sustainable insulation from sheep wool waste for modular building

## File Organization
- Entry point: `index.html` (primary landing page)
- Keep all static assets organized (images, CSS, JS in appropriate directories)
- Do not commit build artifacts or temporary files

## Deployment
- Changes to the `main` branch automatically deploy via GitHub Pages
- GitHub Actions workflow handles deployment (see `.github/workflows/pages.yml`)
- The `.nojekyll` file must remain to prevent Jekyll processing
- CNAME file manages custom domain configuration

## Best Practices
- Test all HTML changes locally before committing
- Ensure cross-browser compatibility
- Validate HTML using W3C validator
- Keep code clean and well-commented where necessary
- Optimize images and assets for web performance
- Maintain proper accessibility standards (WCAG guidelines)

## Security
- Never commit sensitive information or credentials
- Use HTTPS for all external resources
- Follow secure coding practices for any JavaScript

## Git Workflow
- Commit messages should be clear and descriptive
- Keep commits focused and atomic
- Test changes before pushing to main branch
