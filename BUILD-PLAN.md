# Venture 310 Landing Page — Build Plan

## Context

Conrad is a friend who owns Venture 310, a marketing agency in Dubai. Elliot wants to impress him by building a professional landing page before their call **today**. The demo serves two purposes:
1. **Deliverable** — Conrad gets a real landing page for his agency
2. **Sales tool** — Elliot demonstrates the speed and quality of Unpaste's system by iterating on the site live during the call (Conrad describes services → Elliot updates in real-time → Conrad sees changes)

Key constraints: No website exists yet. No logo file (will recreate wordmark in CSS). Services are vague (email marketing, video — will use smart placeholders that can be swapped on the call). Social proof uses placeholders. Brand guidelines exist and are solid.

---

## Phase 1 — Three HTML Design Mockups ✅

Three self-contained HTML files — each a full-viewport hero + services section.

### Direction A — "Editorial Magazine"
- Full-bleed green hero with wide-tracked serif headline
- Asymmetric layout, generous whitespace, thin 1px stone dividers
- Feels like a luxury magazine spread

### Direction B — "Bold Geometric"
- Split-screen hero (green left / cream right with stats)
- Strong geometric grid, high contrast, Gulf Teal accent
- Dubai skyline energy, contemporary feel

### Direction C — "Minimal Prestige"
- Ultra-clean, centered layout, wordmark as dominant element
- Maximum breathing room, Scandinavian restraint
- Feels expensive through what's NOT there

**Files:**
- `mockups/direction-a-editorial.html`
- `mockups/direction-b-bold.html`
- `mockups/direction-c-minimal.html`

---

## Phase 2 — Full Landing Page Build (after design approval)

### Sections:
1. **Hero** — Full viewport, green bg or image overlay. Headline + subheadline + CTA
2. **Services** — 3-4 cards with placeholder content (easy to swap during call)
3. **About / Story** — Split layout. Placeholder about Conrad's vision
4. **Results** — Placeholder stats + testimonial slots
5. **CTA Strip** — Green bg, cream text, compelling headline + button
6. **Footer** — Logo, contact, Instagram link, copyright

### Technical approach:
- Single HTML file with inline CSS + minimal vanilla JS
- Google Fonts via CDN (Cormorant Garamond + DM Sans)
- Fully responsive (mobile-first)
- CSS wordmark (VENTURE³¹⁰)
- HTML comments for fast live editing during call
- Smooth scroll, fade-in animations (300-500ms ease-out)

---

## Phase 3 — Hosting

Deploy to Vercel via CLI or `npx serve` + tunnel for shareable URL.

---

*Created: 2026-02-13*
