# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This repository contains a collection of standalone HTML landing pages for various demo projects. Each file is a self-contained, single-file webpage with embedded CSS and JavaScript.

## File Structure

All landing pages are stored in the root directory:
- `ai-founders-roadmap-landing-page.html` - Lead magnet landing page for an AI founder's guide
- `farmunion-landing-page.html` - Landing page for an Australian livestock market platform
- `intelligent-home-landing-page.html` - AI-native smart home platform landing page
- `linguaflow-pro-landing.html` - Professional translation earbuds product page
- `safenet-landing-page-enhanced.html` - Security/privacy-focused product landing page
- `securevoice-terminal-landing.html` - AI-powered financial voice assistant landing page
- `travelsphere-landing.html` - Travel platform landing page

## Architecture

Each HTML file follows a similar self-contained structure:
1. **HTML document** with semantic markup
2. **Inline CSS** in `<style>` tags containing:
   - CSS custom properties (CSS variables) for theming
   - Responsive design using media queries
   - CSS animations and transitions
   - Modern CSS features (Grid, Flexbox)
3. **Inline JavaScript** for interactivity:
   - Scroll effects and navigation behavior
   - Form handling and animations
   - Intersection Observer for animations on scroll
   - Smooth scrolling behavior

## Development Commands

Since these are static HTML files, you can view them by:
- Opening directly in a browser: `open <filename>.html`
- Running a simple HTTP server: `python3 -m http.server 8000` or `npx serve`

## Design Patterns

All landing pages share common patterns:
- **Fixed navigation** that changes appearance on scroll
- **Hero sections** with gradient backgrounds
- **Feature sections** with icon/emoji-based visual elements
- **Social proof** elements (testimonials, stats, logos)
- **CTA buttons** positioned strategically throughout
- **Form elements** for lead capture
- **Responsive design** optimized for mobile and desktop

## Styling Conventions

- Uses CSS custom properties (`:root` variables) for consistent theming
- Color schemes vary by project but typically use:
  - Dark primary colors for sophistication
  - Bright accent colors for CTAs
  - Gradient backgrounds for visual impact
- Font stacks prefer system fonts for performance: `-apple-system, BlinkMacSystemFont, 'Segoe UI'...`
- Animation timing typically uses `transition: all 0.3s ease`

## JavaScript Patterns

Common JavaScript features used across pages:
- **Scroll listeners** for navigation state changes
- **Intersection Observer API** for scroll-triggered animations
- **Form submission handlers** (usually with `event.preventDefault()`)
- **Smooth scroll** behavior for anchor links
- **CSS class toggling** for interactive states
