# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview
This is a Slidev presentation project that uses Vue.js for building interactive slide decks. The main presentation content is located in the `8-4-25` directory.

## Commands

### Development
```bash
cd 8-4-25
npm install    # Install dependencies
npm run dev    # Start development server (opens browser)
```

### Build & Export
```bash
cd 8-4-25
npm run build   # Build for production
npm run export  # Export slides to PDF or other formats
```

## Architecture

### Core Structure
- `8-4-25/slides.md` - Main presentation file using Slidev markdown format
- `8-4-25/pages/` - Additional slide pages that can be imported
- `8-4-25/components/` - Vue components (e.g., Counter.vue) used in slides
- `8-4-25/snippets/` - Code snippets for presentation

### Technology Stack
- **Slidev** - Presentation framework for developers
- **Vue 3** - Component framework
- **Themes**: Uses `@slidev/theme-seriph` theme

### Key Configuration
- Slides support MDC syntax, transitions, and drawings
- The presentation uses the `seriph` theme with slide transitions
- Components can be directly embedded in markdown slides
- Optimized for 1920x1080 resolution (Full HD) with 16:9 aspect ratio for Zoom presentations