# Leap Athletics website

This is the live site, ready to go as-is. There's no build step: `index.html` at the root is the whole site.

- `index.html`: all pages (Home, Shop, About, Club pricing, Contact, Waitlist). Markup and inline styles are at the top; the page logic is the `class Component` script at the bottom.
- `support.js`, `image-slot.js`, `_ds/`: runtime and design-system styles. Leave them alone.
- `assets/`, `uploads/`: photos, logos and the jump video.

## Hosting
GitHub repo → Cloudflare Pages. Build command empty, output directory `/`. Every push goes live.

## Not wired up yet
- Waitlist forms (Home close band, Waitlist page) and the Contact / Club pricing forms only show a success state. Connect them to an email service.
- Social links in the nav are placeholders (`#instagram`, `#tiktok`, `#linkedin`).
- "07 · The buzz" numbers are placeholders.

## Rules when editing
Change only what is asked. Keep the design exactly as it is: no grey text, minimum 13px text, solid hover states on everything clickable.
