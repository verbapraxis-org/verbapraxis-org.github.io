# Verba Praxis — Site Directory

Each site is a single self-contained `index.html` file (inline CSS + JS, no framework).
All sites are bilingual ES/EN, include a WhatsApp link, and a contact form.

To switch the active version, update the directory reference from `site1` to any `siteN`.

---

## Site Index

| ID | Directory | Name | Concept |
|----|-----------|------|---------|
| 1  | `site1/`  | Lexicon | Typographic Monument |
| 2  | `site2/`  | Solstice | Dark Luxury |
| 3  | `site3/`  | Ma | Japanese Negative Space |
| 4  | `site4/`  | Atlas | Cartographic |
| 5  | `site5/`  | Manifesto | Brutalist |
| 6  | `site6/`  | Vitrine | Parisian Luxury |
| 7  | `site7/`  | Studio | Glassmorphism |
| 8  | `site8/`  | Palimpsest | Organic / Handcrafted |
| 9  | `site9/`  | Meridian | Magazine Grid |
| 10 | `site10/` | Umbral | Cinematic Narrative |
| 11 | `site11/` | Flat | Clean Flat Design |
| 12 | `site12/` | Modern | Contemporary SaaS |
| 13 | `site13/` | Institutional — Law Firm | Formal Legal |
| 14 | `site14/` | Institutional — Consultancy | McKinsey-style |
| 15 | `site15/` | Institutional — Embassy | Diplomatic / Official |
| 16 | `site16/` | Entrepreneur | Startup / Personal Brand |
| 17 | `site17/` | University | Academic / Scholarly |
| 18 | `site18/` | Colleague | Warm Professional B2B |
| 19 | `site19/` | Duolingo | Playful Professional |
| 20 | `site20/` | Cambridge | University Press Authority |

---

## Design Specifications

### site1 — Lexicon · Typographic Monument
- **Palette:** `#F5F0E8` bg · `#1A1A1A` text · `#C8A96E` gold · `#E8E0D0` secondary
- **Fonts:** Playfair Display + IBM Plex Mono
- **Layout:** Single scroll, oversized letterforms as decorative objects
- **Hero:** Rotating bilingual word pair (ES left / EN right) divided by vertical gold hairline
- **Nav:** Vertical strip on left edge with section dot indicators
- **Animation:** `clip-path` reveals on scroll, rotating word pairs
- **Logo:** "VERBA PRAXIS" small caps, two weights, gold period
- **Tone:** Editorial, high-art, typographic monument

---

### site2 — Solstice · Dark Luxury
- **Palette:** `#0C0C0E` bg · `#F0EDE8` text · `#C9A96E` gold · `#1A1A22` card
- **Fonts:** DM Serif Display + DM Sans
- **Layout:** Full-viewport hero, dark scroll sections with gold accents
- **Hero:** Large DM Serif Display headline, radial gold glow behind
- **Animation:** Gold line draws under logo on load, `translateY` fade-ins, hero parallax
- **Logo:** "VERBA PRAXIS" DM Serif Display with thin gold underline rule
- **Tone:** Premium dark mode — luxury watch brand, high-end law firm at night

---

### site3 — Ma · Japanese Negative Space
- **Palette:** `#FAFAF8` bg · `#2C2C2C` text · `#B5451B` vermillion · `#D4CFC4` secondary
- **Fonts:** Noto Serif + Zen Kaku Gothic New
- **Layout:** Ultra-narrow 560px max, vast whitespace (120px+ between sections)
- **Hero:** ES/EN hover reveal — Spanish visible, English fades in on hover
- **Animation:** Opacity only — zero movement, zero transforms
- **Logo:** Two-line stacked VERBA / PRAXIS with vermillion vertical line accent on left
- **Tone:** Japanese minimalism — Muji, tea ceremony, extreme restraint

---

### site4 — Atlas · Cartographic
- **Palette:** `#F2E9D8` parchment · `#2B3A4A` navy · `#C4782A` amber · `#7A8C6E` sage
- **Fonts:** Libre Baskerville + Source Sans 3 + Courier Prime
- **Layout:** SVG language-network map in hero, editorial 2-col grid below
- **Hero:** Inline SVG with animated nodes (ES, EN, Legal, Técnico, Audiovisual) connected by `stroke-dashoffset` lines
- **Decoration:** Compass rose SVG fixed bottom-right, 60s CSS rotation; parchment CSS texture
- **Animation:** SVG line draws on scroll, `IntersectionObserver` staggered reveals
- **Logo:** Compass motif + Libre Baskerville wordmark
- **Tone:** Cartographic atlas, National Geographic editorial

---

### site5 — Manifesto · Brutalist
- **Palette:** `#FFFFFF` bg · `#000000` text · `#FF2D00` red
- **Fonts:** Space Grotesk + Space Mono
- **Layout:** Deliberate tension grid, heavy 4px borders, text bleeding off edges
- **Hero:** Massive headline, deliberate misalignment; diagonal red stripe `clip-path` divider
- **Ticker:** Scrolling marquee at top (red bg, white text, service names)
- **Animation:** Zero easing, zero transitions — instant hover state switches
- **Logo:** VERBA / PRAXIS stacked, 8px red underline
- **Tone:** Brutalist web — confrontational, raw, honest

---

### site6 — Vitrine · Parisian Luxury
- **Palette:** `#FAF7F2` ivory · `#1C1C1C` text · `#8C6D46` cognac · `#D4B483` light cognac
- **Fonts:** Cormorant Garamond + Jost
- **Layout:** Asymmetric 35% fixed sidebar / 65% scrollable main content
- **UX:** Slide-in contact panel from right edge (no modal), overlay backdrop
- **Animation:** 400ms `cubic-bezier(0.25, 0.1, 0.25, 1)` luxury ease, `clip-path` horizontal reveals
- **Logo:** Two-line stacked "VERBA / PRAXIS" with cognac rule between words
- **Tone:** Parisian haute couture atelier, Cormorant italic headlines

---

### site7 — Studio · Glassmorphism
- **Palette:** `#0A0F1E` deep navy · `#FFFFFF` text · `#6E56CF` purple · `#2DD4BF` teal
- **Fonts:** Plus Jakarta Sans
- **Layout:** Frosted glass panels over animated mesh gradient background
- **Background:** Multiple radial gradient orbs shifting with CSS `@keyframes` (no WebGL)
- **Nav:** Fixed bottom dock (macOS style) with JS proximity-based magnification
- **Animation:** GPU-optimized scroll reveals, continuous mesh gradient loop
- **Logo:** "VP" monogram circle with purple→teal gradient fill
- **Tone:** Modern tech studio, Apple Vision Pro meets creative agency

---

### site8 — Palimpsest · Organic / Handcrafted
- **Palette:** `#F7F3EC` parchment · `#2A2318` dark brown · `#8B4513` rust · `#4A6741` forest green
- **Fonts:** Lora + Caveat + Libre Caslon Display
- **Layout:** Manuscript journal — main column with left margin for handwritten Caveat annotations
- **Decoration:** Vertical rust margin rule line; page number labels in Caveat
- **Animation:** Organic `cubic-bezier`, SVG underline draws on scroll, slight rotations on handwriting elements
- **CTA:** Ink-fill button — `::before` scales `scaleX(0→1)` on hover
- **Logo:** "Verba Praxis" in Lora with SVG brush stroke underline in rust
- **Tone:** Letterpress manuscript, artisanal journal, handcrafted quality

---

### site9 — Meridian · Magazine Grid
- **Palette:** `#FFFFFF` bg · `#111111` text · `#E63946` red · `#457B9D` blue
- **Fonts:** Bebas Neue + Merriweather + Inter
- **Layout:** 6-column asymmetric magazine grid hero, 3-column editorial below, column rules throughout
- **Masthead:** Bebas Neue "VERBA PRAXIS" huge and centered (broadsheet style)
- **Ticker:** Red scrolling marquee at top
- **Animation:** `clip-path` print-sweep (left→right) reveals on scroll
- **Logo:** Bebas Neue magazine masthead
- **Tone:** International broadsheet — The Guardian, Le Monde, The Economist

---

### site10 — Umbral · Cinematic Narrative
- **Palette:** `#09090B` near-black · `#FAFAFA` near-white · `#A78BFA` violet · `#34D399` emerald
- **Fonts:** Fraunces + Figtree
- **Layout:** Full-viewport scenes (100vh min-height each), 9 scenes total
- **Hero:** Morphing word pairs (ES→EN) via `clip-path` split animation on scroll
- **Scenes:** About → Services (violet) → Who it's for → Mentoring (emerald) → Process → Testimonials → FAQ → Contact
- **Animation:** Scroll-triggered scene tint transitions, staggered `translateY` reveals, cursor glow effect
- **Logo:** "VERBA PRAXIS" fades and settles from blurred/scaled state on load
- **Tone:** Art film opening titles, dark atmospheric narrative

---

### site11 — Flat · Clean Flat Design
- **Palette:** `#FFFFFF` bg · `#1E293B` text · `#3B82F6` blue · `#F1F5F9` light · `#E2E8F0` borders
- **Fonts:** Inter only (weights 400–800)
- **Layout:** Standard top-nav + hero + 3-col feature grid + services + contact
- **Rule:** Zero box-shadows, zero text-shadows, zero gradients — pure flat color fills
- **Animation:** 150ms `background-color`/`color` transitions on hover only; `opacity` scroll reveals
- **Logo:** "VP" flat blue square + "Verba Praxis" Inter SemiBold
- **Tone:** Material Design without elevation, clean corporate tool

---

### site12 — Modern · Contemporary SaaS
- **Palette:** `#FAFAFA` bg · `#0F172A` text · `#6366F1` indigo · `#F472B6` pink · `#E0E7FF` light
- **Fonts:** Outfit (300–800)
- **Layout:** Hero with gradient pill badge + alternating 2-col feature sections + floating cards
- **Accents:** Indigo→pink gradient on text (`-webkit-background-clip: text`), badges, and borders
- **Animation:** Cards float in from `translateY(40px) opacity:0`; hover elevates shadow
- **Nav:** Sticky with `backdrop-filter: blur(12px)`
- **Logo:** "Verba Praxis" Outfit Bold with gradient underline
- **Tone:** Linear.app, Vercel, modern SaaS landing page

---

### site13 — Institutional · Law Firm
- **Palette:** `#0A1628` dark navy · `#F8F6F1` cream · `#B8962E` gold · `#1C2E4A` card navy
- **Fonts:** EB Garamond + Source Sans 3
- **Layout:** Dark navy header + cream content areas; fixed left sidebar (credentials + SVG seal)
- **Decoration:** SVG circular seal (textPath around circumference, VP monogram); Latin phrases decorative band (Fides Publica, In Dubio Pro Reo, Veritas et Iustitia); document types table
- **Animation:** Minimal — gold `scaleX` underline on nav hover, opacity fade-ins only
- **Logo:** "VERBA PRAXIS" EB Garamond + "Traductores Públicos Matriculados" subtitle + gold seal
- **Tone:** Prestigious Argentine law firm, official government legal office

---

### site14 — Institutional · Consultancy
- **Palette:** `#FFFFFF` bg · `#1A1A2E` navy · `#0057B8` blue · `#F4F4F4` gray · `#E8ECF0` borders
- **Fonts:** DM Sans + DM Serif Display (headers only)
- **Layout:** Clean white, large decorative section numbers (01, 02...), data-forward stat highlights
- **Features:** JS count-up animation on stats; service packages with scope/deliverables/timeline; Insights article cards
- **Animation:** Clean `translateY` slide-in card reveals on scroll
- **Logo:** "VERBA PRAXIS" DM Sans Bold with geometric horizontal rule
- **Tone:** BCG, McKinsey, Deloitte — consultancy gravitas

---

### site15 — Institutional · Embassy
- **Palette:** `#FFFFFF` bg · `#1C3557` diplomatic navy · `#8B0000` crimson · `#C9B037` gold · `#F0F0EE` off-white
- **Fonts:** Libre Baskerville + Open Sans
- **Layout:** Thin utility bar → formal header → full-width navy nav band → ART. numbered document sections
- **Decoration:** SVG circular seal with textPath ("VERBA PRAXIS · TRADUCTORES PÚBLICOS · MATRICULADOS ·"), laurel branches, star; authentication stamps (gold-bordered, rotated); faint watermark SVG in background
- **Animation:** One-time 360° seal rotation on page load; hover underlines only
- **Logo:** Circular SVG seal (coat-of-arms style) + "VERBA PRAXIS" + "TRADUCTORES PÚBLICOS MATRICULADOS"
- **Tone:** Argentine consulate, Ministry of Foreign Affairs, official diplomatic document

---

### site16 — Entrepreneur · Startup / Personal Brand
- **Palette:** `#FFFBF0` warm white · `#1A1A1A` text · `#FF6B35` orange · `#FFE5D9` light orange
- **Fonts:** Cabinet Grotesk + Satoshi (Fontshare CDN)
- **Layout:** Bold asymmetric hero, founder-voice copy, testimonial speech bubbles, FAQ accordion
- **Animation:** Spring CTA hover `cubic-bezier(0.34, 1.56, 0.64, 1)` overshoot; floating badge pulse; SVG squiggly underline draws on logo and section titles
- **Logo:** "Verba Praxis" Cabinet Grotesk ExtraBold + animated squiggly SVG underline in orange
- **Tone:** Confident solo founder or boutique agency principal — warm, energetic, direct

---

### site17 — University · Academic / Scholarly
- **Palette:** `#FFFFFF` bg · `#1B2A4A` navy · `#4B7BEC` blue · `#F7F8FC` light · `#E9EEF6` borders
- **Fonts:** Crimson Pro + Inter
- **Layout:** Tab navigation (5 tabs, JS show/hide); 65% main + 35% sticky sidebar
- **Tabs:** Inicio · Servicios · Mentoría · Sobre Nosotros · Contacto
- **Decoration:** Academic shield SVG (VP monogram, laurel paths, arc text) in header
- **Services:** Formal programme descriptions with code (VP-TL-001 etc.), objectives, document types, for-whom, modality
- **Animation:** Subtle scroll reveal; tab transitions; FAQ accordion
- **Logo:** SVG academic seal + "VERBA PRAXIS" + "Servicios de Traducción e Idiomas"
- **Tone:** Harvard Extension, Cambridge Language Centre, respected university department

---

### site18 — Colleague · Warm Professional B2B
- **Palette:** `#F9F7F4` warm off-white · `#2D2926` warm dark · `#5C8A6E` green · `#E8F4EC` light green
- **Fonts:** Nunito (800,700,600) + Nunito Sans (400,600)
- **Layout:** Rounded cards (20px+ radius), warm backgrounds, peer-to-peer headings
- **UX:** Argentine "vos" register in ES; visible process journey with connecting animated line; form progress bar (green fills as fields complete); WhatsApp as primary contact
- **Animation:** Spring bounce `cubic-bezier(0.34, 1.56, 0.64, 1)` on all CTAs and cards; staggered scroll reveals
- **Logo:** "Verba Praxis" Nunito ExtraBold + speech bubble SVG icon
- **Tone:** Trustworthy colleague who happens to be a professional — approachable, genuine, human

---

### site19 — Duolingo · Playful Professional
- **Palette:** `#FFFFFF` bg · `#1CB0F6` blue · `#58CC02` green · `#FFC800` yellow · `#FF4B4B` coral · `#F7F7F7` gray
- **Fonts:** Nunito (900–400) + Open Sans
- **Layout:** Card-based modular layout; rounded corners throughout; colored 6px top strip per service card
- **Color coding:** Legal=blue · Technical=yellow · Audiovisual=coral · Mentoring=green · Advisory=purple
- **Decoration:** Rainbow decorative progress bar fills on page load; overlapping circles SVG logo (green+blue)
- **Animation:** Card hover `translateY(-6px)` with spring overshoot; smooth color fills
- **Rule:** NO gamification (no streaks, XP, points, leaderboards, mascot)
- **Tone:** Duolingo's visual warmth adapted for professional B2B — accessible, friendly, business-appropriate

---

### site20 — Cambridge · University Press Authority
- **Palette:** `#FFFFFF` bg · `#003266` Cambridge blue · `#7E1F86` Cambridge purple · `#F5F0FF` light purple · `#E8EEF5` light blue
- **Fonts:** Libre Baskerville + Source Sans 3
- **Layout:** Full-width Cambridge-blue category nav; 65% main content + 35% sidebar; scholarly article format
- **Features:** DOI-style service identifiers (VP-TL-001 through VP-EA-005); formal catalogue entries with abstracts, scope notes, ideal respondent; Insights section; sidebar with credentials and Related Services
- **Animation:** NONE except purple `::after scaleX` underline reveal on hover only (academic restraint)
- **EN locale:** British spelling (Catalogue, localisation, programme, colour)
- **Logo:** Coat-of-arms SVG (shield, crown, VP monogram) + "VERBA PRAXIS" Libre Baskerville + "Est. MMXXVI" small caps
- **Tone:** Cambridge University Press, Oxford University Press — gold standard of academic publishing

---

## Common Requirements (all sites)

- Single self-contained `index.html` — all CSS and JS inline
- **Bilingual:** ES/EN toggle via JS locale object, no page reload
- **WhatsApp:** `https://wa.me/5492215972410`
- **Email:** `verbapraxis@outlook.com`
- **Contact form:** name, email, subject, message — success message on submit, no backend
- **Services:** Legal Translation (sworn) · Technical Translation (sworn) · Audiovisual Translation · English Mentoring · English Advisory
- **Mentoring focus:** Professional performance · Job interviews · Pronunciation · Travel fluency
- **CTA:** "Agenda tu sesión de diagnóstico" / "Schedule your diagnostic session"
- **Responsive:** Mobile-friendly, hamburger nav
- **No external images:** SVG inline only
- **Fonts:** Google Fonts CDN (except site16: Fontshare CDN)
