# Accord - Path Consult · Site notes

## Domain & email

Canonical URLs, Open Graph, `robots.txt`, and `sitemap.xml` use **`https://accordpathconsult.com/`**. Replace this domain everywhere if you use a different URL.

The contact form opens a **mailto** draft to **`consultations@accordpathconsult.com`**. Set up this mailbox (or change the address in `index.html` and in the JSON-LD block in the page `<head>`).

## Assets

| File | Purpose |
|------|---------|
| `public/logo.svg` | Header mark |
| `public/favicon.svg` | Browser tab icon |
| `public/hero.png` | Full-width hero photograph (scales, desk, office scene) |
| `public/og-image.png` | Optional separate OG asset (social tags currently use `hero.png`) |

Replace `public/hero.png` when you export a new hero; adjust `object-position` in `index.html` (`.hero-media`) if the focal point changes.

## Analytics

Add your snippet where the `<!-- ANALYTICS PLACEHOLDER -->` comment sits in `index.html`.

## Map

The contact “map preview” links to Google Maps search for **Dansoman, Accra, Ghana**. Replace with an embed or a pinned location URL when ready.
