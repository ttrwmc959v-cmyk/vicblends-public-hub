# VicBlends Public Hub

A polished, mobile-first single-page link hub for **VicBlends** — barber, educator, and creator behind the VicBlends Barber Academy and the "Stay Planted" movement.

This is a **fan-built promotional hub** of public links. All purchases, signups, and learning happen on the official destination sites — there is no checkout on this page.

## What's here

- `index.html` — the entire hub: brand mark (inline SVG sprout/leaf), audience stats, primary CTA to the Academy, social links (YouTube, Instagram, TikTok, Facebook), Planted shop link, business + academy support contacts, copy/share buttons, disclaimer.
- `favicon.svg` — green/white sprout favicon.
- `og-image.svg` — Open Graph share image (1200×630) used by `og:image` and `twitter:image`.
- `.nojekyll` — disables Jekyll on GitHub Pages so files starting with `_` (if any) are served as-is.

## Design

- **Palette:** clean green + white only — pale green-tinted background, white surfaces, deep green (`#0f5132`) for text and primary CTA, fresh leaf accent (`#2e9c5b`). No red anywhere.
- **Type:** Space Grotesk (display) + Inter (body), loaded from Google Fonts.
- **Logo mark:** custom inline SVG — a stem with two leaves (sprout) that ties to the "Stay Planted" tag.
- **Mobile-first** layout (max-width 560 px), generous tap targets, social-share friendly meta tags.

## Links wired up

- Academy / official site — https://vicblends.com
- YouTube — https://www.youtube.com/channel/UCR6Jv1wniCG_3gdCo_f8_qA
- Instagram — https://www.instagram.com/vicblends/
- TikTok — https://www.tiktok.com/@vicblends
- Facebook — https://www.facebook.com/vicblendsofficial/
- Planted merch / shop — https://theplantedcollective.com (labeled cautiously as "Planted-inspired merch & shop")
- Business inquiries — mailto:vicblends@wmeagency.com
- Academy support — mailto:support@vicblends.com

## Sharing

The "Copy link" and "Share" buttons use `window.location.href` so they'll just work once published to a real URL (e.g. GitHub Pages). `navigator.share` is used when available, with a clipboard fallback.

## Deploy

Static HTML/CSS/JS only. No build step. Push the folder to a `gh-pages` branch or main and enable GitHub Pages — `.nojekyll` is already included.
