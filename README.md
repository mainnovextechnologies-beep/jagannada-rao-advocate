# Advocate S.S.S.V. Jagannadha Rao — React + Vite

## Run locally
1. Install Node.js (LTS).
2. Extract the ZIP and open this folder in a terminal.
3. Run `npm install`
4. Run `npm run dev`
5. For production build, run `npm run build`; preview with `npm run preview`.

## Before production launch
- Generate `sitemap.xml` after the final production domain is known. Include only canonical URLs that actually return HTTP 200; do not publish a placeholder-domain sitemap.
- Add the actual production canonical URL and `og:url` in `index.html` once the final domain is known.
- `robots.txt` references the sitemap in a comment only until the real domain is configured.
- The portrait in the hero is intentionally an abstract legal emblem, not a fabricated photograph. Replace it with an approved advocate portrait and descriptive alt text if supplied.
- Verify the exact office pin/address and opening hours with the advocate before launch; current map centers on Murali Nagar as requested.
- The WhatsApp form opens a prefilled message; it does not transmit until the visitor sends it in WhatsApp.
- JSON-LD contains only the supplied location-level address and phone. Confirm that all fields match the official business profile before publishing.

## SEO note
This implementation provides crawlable rendered page text, title/description, Open Graph basics, LegalService JSON-LD, mobile layout and sitemap starter. No website can guarantee first position in Google. Exact-name, location and practice-area visibility also depend on the live domain, Google Business Profile consistency, crawl/index status, legitimate references and useful content. A React SPA may benefit from prerendering/SSR for more reliable initial HTML delivery if indexing is weak.
