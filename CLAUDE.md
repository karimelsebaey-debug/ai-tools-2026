# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a single-file static Arabic-language (RTL) web presentation about the top 5 AI tools of 2024. There is no build system, package manager, or test framework — the entire project is `index.html`.

## Structure

`index.html` contains all HTML, CSS, and JavaScript inline. The page presents a slideshow of five AI tools (ChatGPT, Claude, Google Gemini, Perplexity, DeepSeek) with:

- **CSS**: Embedded in `<style>` — dark theme using `#0f172a`/`#1e293b` backgrounds with teal (`#5eead4`) and sky-blue (`#38bdf8`) accent colors. Each tool has a unique accent color class (`.chatgpt`, `.claude`, `.gemini`, `.perplexity`, `.deepseek`).
- **JavaScript**: Embedded in `<script>` at the bottom — manages slide transitions, auto-advance (8-second interval), keyboard navigation (arrow keys), and IntersectionObserver-based fade-in effects.
- **External dependency**: Font Awesome 6.4.0 loaded from cdnjs (CDN-only, no local copy).

## Development

Open `index.html` directly in a browser — no server required. All changes are immediately visible on refresh.

## Conventions

- The document uses `dir="rtl"` and `lang="ar"` — all user-facing text is in Arabic.
- Navigation buttons are reversed from LTR convention: the right-arrow button (`prev-btn`) goes to the previous slide, left-arrow (`next-btn`) goes to the next slide, matching RTL reading direction.
- `currentSlide` is a zero-based index; slide indicators use `data-slide` attributes that are one-based.
