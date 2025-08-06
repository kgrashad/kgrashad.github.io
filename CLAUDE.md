# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a GitHub Pages static website (`kgrashad.github.io`) serving as a personal portfolio and presentation platform. The site contains financial tools for Uber drivers and business presentation slides.

## Architecture

**Static Site Structure:**
- Pure HTML/CSS/JavaScript with no build system or external dependencies
- All styles and scripts are inline for maximum portability
- Mobile-first responsive design optimized for GitHub Pages deployment

**Key Pages:**
- `income-statement.html` - Uber driver income statement interface with interactive payment functionality
- `safco-slides-aug2025.html` - Business presentation slideshow with keyboard navigation

## Development Approach

**No Build Process:**
- Files are served directly as-is from the repository
- No package.json, build tools, or preprocessing steps
- Changes are immediately reflected when pushed to GitHub Pages

**Code Style:**
- Inline CSS and JavaScript for self-contained pages
- Modern CSS features: Grid, Flexbox, custom properties, animations
- Semantic HTML with accessibility considerations
- Responsive breakpoints for mobile/tablet/desktop

## Testing and Deployment

**No Automated Testing:**
- Manual testing across different devices and browsers required
- Test responsive behavior at different screen sizes
- Verify keyboard navigation works in presentation slides

**GitHub Pages Deployment:**
- Changes pushed to `main` branch are automatically deployed
- No build step required - direct file serving
- Site accessible at `https://kgrashad.github.io`

## Key Technical Features

**Financial Statement Pages:**
- Mobile-optimized Uber/fintech-style interfaces
- Interactive payment and calculation functionality
- Professional branding and visual design

**Presentation Slides:**
- Custom slide navigation system
- Keyboard controls (arrow keys, spacebar)
- Professional presentation layout with animations