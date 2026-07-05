# SEO / GEO

Applied by the `findable` skill.

## Applied
- `public/robots.txt` — allow all, points to sitemap.
- `public/sitemap.xml` — single-route SPA sitemap.
- `public/llms.txt` — AI-readable project summary ([llmstxt.org](https://llmstxt.org)).
- `public/humans.txt` — credits.
- `index.html` — fixed `lang` (`en` → `pt-BR`), added meta description, canonical, Open Graph, Twitter Card, and `WebApplication` JSON-LD.

## Notes
- Single-page SPA: sitemap has one route. Add entries if routing is introduced later.
- No server-side rendering, so social crawlers that don't execute JS only see the static `index.html` meta tags above (already covered).
