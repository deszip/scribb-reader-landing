# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Minimal Astro 5.x landing page project (spiffy-star).

## Commands

```bash
npm run dev      # Start dev server at localhost:4321
npm run build    # Build production site to ./dist/
npm run preview  # Preview production build locally
```

## Architecture

- **Framework**: Astro 5.x with strict TypeScript
- **Routing**: File-based routing in `src/pages/` - each `.astro` or `.md` file becomes a route
- **Static assets**: Place in `public/` directory
- **Components**: Place in `src/components/` (not yet created)
- **Configuration**: `astro.config.mjs` for Astro settings
