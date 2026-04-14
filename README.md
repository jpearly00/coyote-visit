# Coyote's at Moab Mercantile — Visit Site

Alt landing for `visit.moabcoyote.com`, one-shot generated using Nick Saraev's Cinematic Landing Page Builder prompt (Preset A — "Organic Tech") adapted for Moab desert brand.

## Stack
- Static HTML (single file `index.html`)
- Tailwind CSS via CDN with custom palette (moss / clay / cream / charcoal)
- Google Fonts: Plus Jakarta Sans, Outfit, Cormorant Garamond Italic, IBM Plex Mono
- GSAP 3 + ScrollTrigger via Cloudflare CDN
- Lucide icons via unpkg CDN
- Real Unsplash imagery

## Animations implemented per spec
- Hero staggered fade-up entrance (power3.out, 0.08 stagger)
- Navbar morph-on-scroll (transparent → cream/70 + backdrop-blur-xl)
- Diagnostic Shuffler (3 cards cycling every 3s with spring-bounce)
- Telemetry Typewriter (character-by-character feed with blinking cursor)
- Cursor Protocol Scheduler (animated SVG cursor → day → save)
- Philosophy parallax image + word-reveal
- Protocol sticky stacking (scale 0.92 + blur 12px under new card)
- EKG waveform (stroke-dashoffset loop)
- Spin-slow geometric motif, scan-sweep laser line, pulse-dot operational indicator

## Deploy
Repo: `jpearly00/coyote-visit` (GH Pages, public)
Domain: `visit.moabcoyote.com` (DNS via Wix API)

## Source prompt
See `../NickSaraev_GEMINI.md` — the spec Gemini 3.1 was demonstrated with. This site was built by Claude following the same spec.
