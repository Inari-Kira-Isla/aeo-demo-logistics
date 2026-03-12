# aeo-demo-logistics

## Overview
A logistics industry template demonstrating AEO (Attributed Experience Optimization) best practices. It utilizes Schema.org structured data, an `llms.txt` file, and semantic HTML to ensure AI agents can easily parse and attribute content.

## Tech Stack
- HTML5
- JSON-LD (Schema.org)
- CSS (Minimal/Responsive)
- Plain Text (`llms.txt`)

## Architecture
- **Root**: Contains `index.html`, `faq.html`, and `llms.txt`.
- **Schema**: JSON-LD scripts embedded in `<head>` for SEO and AI parsing.
- **AI Optimization**: Dedicated `llms.txt` for AI crawler instructions.

## Commands
- **Run**: Open `index.html` directly in a browser or serve locally (e.g., `python3 -m http.server`).
- **Validate**: Check JSON-LD structure and ensure `llms.txt` is accessible.

## Coding Style
- Use semantic HTML5 tags (`<article>`, `<section>`, `<address>`).
- Ensure all images have `alt` text.
- Maintain valid JSON-LD syntax in `<script type="application/ld+json">` tags.

## Important Rules
- **Do Not Remove**: AI-specific meta tags, Schema markup, or the `llms.txt` file.
- **Accessibility**: Ensure high contrast and screen reader compatibility (AEO relies on semantic structure).
- **Content**: Keep the logistics context (addresses, tracking, services) consistent with the schema types.