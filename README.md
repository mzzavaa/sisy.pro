# SISY Pro

Premium membership landing page for [sisy.pro](https://sisy.pro).

## Development

```bash
brew install hugo
hugo server -D
```

Open http://localhost:1313

## Design System

Matches sisy.world:
- **Fonts**: Inter (body) + Playfair Display (headings)
- **Icons**: Lucide via CDN
- **Dark mode**: `data-theme="dark"` on `<html>` with localStorage persistence
- **CSS**: Single file `static/css/style.css` with CSS custom properties
- **Colors**: Accent `#b44d8c` / `#d4699e` (dark), BG `#fdf6f9` / `#1a1020` (dark)

## Sections

1. Hero — "Unlock your full expert potential"
2. Pricing — Starter (Free) / Pro (9 EUR/mo) / Elite (29 EUR/mo)
3. Features — Deep-dive on Pro/Elite features
4. Testimonials — Social proof placeholders
5. FAQ — Accordion with common questions
6. CTA — Final conversion push
7. Footer — Full SISY ecosystem links

## Deployment

GitHub Pages via `.github/workflows/deploy.yml` on push to `main`.
