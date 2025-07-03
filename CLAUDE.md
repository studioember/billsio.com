# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a modern landing page for Bills io, a lightweight finance tool for small businesses. The site uses Tailwind CSS with a custom design system and serves as a waitlist signup page.

## Architecture

- **Static Site**: HTML file with Tailwind CSS styling
- **Build System**: Tailwind CSS with npm scripts
- **Deployment**: GitHub Pages (CNAME file indicates custom domain)
- **Form Handler**: Uses Formspree.io for email collection
- **Styling**: Tailwind CSS with custom components and animations
- **Icons**: Lucide React icons via CDN

## Key Files

- `index.html` - Main landing page with waitlist form
- `src/input.css` - Tailwind CSS input file with custom components
- `dist/output.css` - Generated CSS output (built file)
- `tailwind.config.js` - Tailwind configuration with custom theme
- `package.json` - Project dependencies and scripts
- `logo.png` - Company logo
- `CNAME` - Custom domain configuration for GitHub Pages

## Development Commands

- `npm install` - Install dependencies (first time setup)
- `npm run build` - Build CSS for production (minified)
- `npm run dev` - Watch for changes and rebuild CSS
- `npm run serve` - Start local development server on port 8000

## Development Notes

The site uses modern web technologies:
- Tailwind CSS v3.4+ with custom theme extensions
- Glassmorphism design with backdrop blur effects
- Custom animations (float, glow, fade-in, slide-up)
- Responsive design with mobile-first approach
- Custom brand colors and component classes
- Lucide icons for visual enhancement

## Custom Components

- `.btn-primary` - Primary button with gradient and hover effects
- `.input-field` - Input styling with focus states
- `.card-glass` - Glassmorphism card container
- `.gradient-bg` - Background gradient utility

## Design Features

- Animated floating background elements
- Glassmorphism effects with backdrop blur
- Custom purple brand color palette
- Smooth transitions and hover effects
- Feature preview icons with grid layout
- Modern typography with Inter font