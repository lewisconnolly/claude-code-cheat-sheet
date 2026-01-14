# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a single-page static HTML reference cheat sheet for Claude Code. No build system, dependencies, or tests.

## File

- `claude-code-cheatsheet.html` - Self-contained HTML with inline CSS. Dark theme using CSS custom properties. Uses Google Fonts (JetBrains Mono, Space Grotesk).

## Editing Guidelines

- Maintain the existing color scheme defined in `:root` CSS variables
- Keep all styles inline (no external CSS files)
- Preserve responsive breakpoints at 900px
- Use semantic section classes (`orange`, `cyan`, `purple`, `blue`, `pink`, `yellow`) for consistent theming