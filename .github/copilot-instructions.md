# aeo-demo-logistics

## Project
AEO demo template for the logistics industry using HTML with Schema.org, llms.txt, FAQ, and AI-friendly markup.

## Conventions
- Use semantic HTML5 elements (header, main, article, section, footer)
- Include Schema.org JSON-LD structured data in <script type="application/ld+json"> tags
- Place llms.txt in root directory
- Use proper meta tags for SEO and AEO
- Keep FAQ content in structured format
- Use accessible HTML with proper ARIA attributes where needed

## Naming
- Use lowercase with hyphens for file names: `logistics-service.html`
- Use descriptive, SEO-friendly URLs: `/shipping-solutions.html`
- Name Schema.org types using exact Schema.org vocabulary

## Architecture
- Single-page or multi-page static HTML site
- Structured data separated into JSON-LD blocks
- Content-first approach with semantic markup
- FAQ section using proper FAQPage schema

## Commands
- No build commands required (static HTML)
- Validate structured data using Google's Rich Results Test
- Ensure llms.txt follows llms.txt specification

## Do Not
- Do not use client-side JavaScript for core content delivery
- Do not omit Schema.org markup on pages with structured content
- Do not use non-semantic div/span for content that has semantic meaning
- Do not place llms.txt in subdirectories; must be in root
- Do not use generic or placeholder content in structured data