# Reference Site Analysis: Carina Renner
Date: 2026-03-15

Client: Carina Louise Renner (Pro S/.120)
Profile: Multidisciplinary Artist, Vocalist, Sound Healer
Key Request: Audio player for music tracks/demo reels

---

## SITE 1: rodrigoponce.com (Music Composer)

### Platform
- **Bandzoogle** (musician-specific website builder)
- Custom theme: "Breakbeat" variant C

### Color Palette
| Role | Value | Hex Approx |
|------|-------|------------|
| Page background | `hsl(207, 33%, 94%)` | `#E3EBF0` (light blue-gray) |
| Text/headings | `hsl(0, 0%, 0%)` | `#000000` (black) |
| Nav links | `hsl(0, 0%, 100%)` | `#FFFFFF` (white on dark bg) |
| Player accent | `hsl(0, 99%, 64%)` | `#FE4747` (coral red) |
| Theme background | `hsl(0, 0%, 0%)` | `#000000` (black header/nav) |
| CTA subheading | `hsl(0, 59%, 21%)` | `#561016` (dark red) |
| Image filter | `hsla(0, 0%, 60%, 0.22)` | Gray overlay 22% opacity |
| Button color | `hsl(0, 0%, 0%)` | `#000000` (outline style) |

**Palette Summary:** High-contrast monochrome (black/white/light gray) with a single coral-red accent for the music player. Very cinematic, minimal.

### Typography
| Element | Font | Size | Weight |
|---------|------|------|--------|
| Page title/logo | **Staatliches** | 33px | Regular |
| Body/headings/menu | **Assistant** | 17px body, 30px headings | Regular, Semibold, Bold |
| Feature titles | Assistant | 51px | — |
| CTA heading | — | 86px | — |
| CTA subheading | — | 26px | — |
| Line height (body) | — | 1.6 | — |
| Line height (heading) | — | 1.1 | — |

**Font Strategy:** Two-font system. Staatliches (display/condensed sans) for branding, Assistant (clean geometric sans) for everything else. All-caps for major headings.

### Layout Patterns
- **Hero:** Split-screen asymmetric — text left (60%), image carousel right (40%)
  - Left: "MUSIC COMPOSER" large heading + "Film Scorer and Guitarist" subtitle + "REELCRAFT" CTA button
  - Right: Auto-rotating photo slideshow (5 images, concert/portrait photos)
  - Background: light blue-gray with subtle music sheet watermark texture
- **Page frame:** 2% border around entire page content (like a picture frame effect)
- **Section gaps:** 2% between sections
- **Header height:** 85% of viewport for hero
- **Project grid:** Regular 3-column grid, image-dominant cards with titles below
- **Bio section:** Text block with inline image, narrative style
- **Events table:** Full-width chronological list with date/event/location columns, paginated
- **Overall:** Full-width sections, no max-width container visible

### Audio Player (KEY FEATURE)
- **Type:** Custom Bandzoogle built-in player (NOT embedded SoundCloud/Spotify)
- **Layout:** Playlist-style with numbered track list
- **Controls:** Play/pause, previous/next track, progress scrubber, time display (current/total)
- **Track display:** Ordered list showing: track number, clickable title, duration, share button per track
- **Persistent bottom bar:** Coral-red (#FE4747) sticky bar at bottom of viewport showing current track name + play/pause + skip controls
- **Track count:** 10 tracks (Music Reel, Tempest, Dizziness, Mara's Gamble, etc.)
- **Color:** Coral red accent on dark background for the sticky bar; playlist itself on page background
- **Share feature:** Per-track social share (4 icons per track)

### Interactive Elements
- **Hero image carousel:** Auto-rotating photos with crossfade
- **Sticky player bar:** Persists at bottom while scrolling (coral red)
- **Project cards:** Gray overlay filter on hover (hsla 0,0%,60%, 22% opacity)
- **Navigation:** Horizontal top bar, white text on black, dropdown for Photos and Contact
- **CTA button:** Outline style, square corners, black border
- **Events pagination:** First/Prev/Next/Last navigation

### Photo Treatment
- No border-radius (square/rectangular images)
- Subtle gray overlay filter on project thumbnails
- Full-bleed images in hero carousel
- Performance/concert photography style

### Navigation
- **Style:** Horizontal top bar, sticky
- **Background:** Black
- **Links:** White text, uppercase, spaced
- **Items:** Home, Latest Tracks, Music Samples, Bio, Shows, Photos (dropdown), Contact (dropdown)
- **Logo:** Custom monogram "RP" + "Rodrigo Ponce Aparicio" text, top-left

### Footer
- **Background:** Black
- **Content:** Social media icons (Email, Instagram, Spotify, YouTube, Facebook)
- **Attribution:** "Powered by Bandzoogle"
- **Style:** Minimal, icon-only social links centered

### Mobile Approach
- Bandzoogle responsive framework
- Mobile nav becomes hamburger menu (black background)
- Single-column layout for all sections
- Player controls remain accessible

### Standout Features
1. **Persistent coral-red music player bar** at bottom of page — always visible
2. **Music sheet watermark texture** on hero background — subtle, thematic
3. **Page frame/border effect** (2% border) — gives a "gallery" feel
4. **Image carousel in hero** with crossfade transitions
5. **Integrated playlist** with per-track sharing

---

## SITE 2: hunterguidroz.com (Voice Actor)

### Platform
- **WordPress** with **Astra** theme + **Beaver Builder** page builder
- Custom styling with CSS variables

### Color Palette
| Role | CSS Variable | Hex | Description |
|------|-------------|-----|-------------|
| Primary dark | `--ast-global-color-0` | `#370D17` | Dark maroon/burgundy |
| Secondary | `--ast-global-color-1` | `#4F623F` | Muted olive green |
| Accent | `--ast-global-color-2` | `#95B8C0` | Slate/sage blue |
| Light accent | `--ast-global-color-3` | `#E1EBC6` | Pale yellow-green |
| Background | `--ast-global-color-4` | `#ECE6DF` | Warm cream/beige |
| CTA/highlight | `--ast-global-color-5` | `#DD8444` | Burnt orange |
| Text | `--ast-global-color-6` | `#111111` | Near black |
| Footer bg | — | `#EB7D2F` | Bright orange |
| Focus ring | — | `#046BD2` | Blue (accessibility) |

**Palette Summary:** Warm, earthy, retro-70s vibe. Cream base, dark maroon for contrast sections, burnt orange for CTAs and footer, olive green for hovers, sage blue for accents. Very intentional retro color story.

### Typography
| Element | Font | Size | Weight |
|---------|------|------|--------|
| Headings | **Thorce** (custom display) | H1: 62px, H2: 46px, H3: 33px | Bold |
| Body text | **Poppins** | 16px base | 400, 500, 600, 700 |

**Font Strategy:** "Thorce" is a custom retro/hand-drawn display font with an organic, playful quality — all headings use it giving a strong personality. Poppins for readability in body text. The Thorce font is THE defining visual element.

### Layout Patterns (20 sections, top to bottom)
1. **Header:** Logo left, nav center, social icons + CTA button right
2. **Hero:** 2-column — large heading + contact info + audio demos (left), hero photo with retro border treatment (right)
3. **Marquee ticker:** Full-width scrolling text bar — "24 hr turnaround | Multiple revisions | Versatile and Flexible voice" repeating infinitely
4. **About/Bio:** 2-column — photos with retro borders (left), heading + bio text (right)
5. **Experience/Training:** "Excuse me while I brag" — credential logos/badges
6. **Studio:** Photo + equipment list (CAD E100S mic, Focusrite Scarlett 2i2, ATH-M30x, Adobe Audition)
7. **Services grid:** "Voice Acting that suits your needs" — 3x3 grid of rounded pill cards (Video Games, Animation, Commercials, E-Learning, Audiobooks, Documentary, Radio, ADR, Dubbing)
8. **How It Works:** 3 numbered steps with photos — Book a Call, Listen to Preview, Voice Delivered
9. **Testimonial:** "You heard it here first" — single quote in rounded card on light green background
10. **CTA banner:** Dark teal/blue full-bleed photo background + "Book a call today" button
11. **FAQ accordion:** "Answering your questions" — expandable +/- items with retro stripe border container
12. **Footer:** 3-column on bright orange — copyright + nav links (left), logo + social icons (center), agent info (right)

### Audio Player (KEY FEATURE)
- **Type:** WordPress native `<audio>` elements with custom styling
- **Placement:** Integrated into hero section, inside a dark maroon (#370D17) rounded card
- **3 demo reels:**
  - Commercial Demo (HunterGuidroz_CommercialDemo.mp3)
  - Video Game Demo (VideoGameDemo_HunterGuidroz.mp3)
  - Animation Demo (AnimationDemo_HunterGuidroz.mp3)
- **Controls:** Standard HTML5 audio — play/pause, scrubber, time, volume, download
- **Visual:** White/light controls on dark maroon background, each demo labeled with Thorce heading font
- **NOT a playlist:** Three separate, independent audio players stacked vertically
- **No persistent/sticky bar**

### Interactive Elements
- **Marquee/ticker:** Infinite horizontal scroll with emoji icons between text items
- **Scroll animations:** Photos use `fl-animation fl-zoom-in` (zoom-in on scroll into view, 2s duration)
- **Hover effects:**
  - Links: color changes to olive green (#4F623F)
  - Buttons: bg changes to olive green
  - Menu items: color changes to sage blue (#95B8C0)
  - Social icons: `transform: scale(1.1)` on hover
- **FAQ accordion:** Click to expand/collapse with +/- toggle
- **Lightbox:** Image gallery with zoom-in/zoom-out animation (0.4s), blur + saturation backdrop
- **Scroll-to-top button:** Fixed position, dark maroon background, appears on scroll

### Photo Treatment (SIGNATURE ELEMENT)
- **Retro stripe borders:** Photos are wrapped in rounded-rectangle containers with decorative multi-colored stripe borders (orange, olive green, sage blue, dark maroon) running as parallel lines — like vintage 70s design
- **Border-radius:** Large rounded corners (appears ~20-30px) on photo containers
- **Multiple photos per section:** Overlapping/staggered placement (one large, one small offset)
- **Image style:** Casual, personality-forward, multiple outfits/settings

### Navigation
- **Style:** Horizontal top bar
- **Layout:** Email + phone left, nav links center, social icons + "Get Started" button right
- **"Get Started" CTA:** Burnt orange background, rounded corners
- **Mobile:** Hamburger toggle, responsive breakpoints at 922px and 544px
- **Items:** Home, Blog, Voiceover Services (dropdown), Design Services (dropdown)

### Footer
- **Background:** Bright orange (#EB7D2F)
- **Layout:** 3-column grid
  - Left: Copyright, "Listen to demos" link, "Contact" link
  - Center: Logo (custom heart-microphone icon) + "HUNTER GUIDROZ" text + social icons (LinkedIn, Twitter, Instagram) + email
  - Right: "AGENTS" heading (Thorce font) + Linda McAlister Talent Agency info
- **Padding:** 45px top/bottom
- **Text:** White/off-white on orange

### Mobile Approach
- Responsive breakpoints: 922px (tablet), 544px (mobile)
- Single-column stacking
- Mobile header with hamburger menu
- Images resize proportionally
- Marquee continues on mobile
- FAQ accordion works well on small screens

### Standout Features
1. **Retro stripe photo borders** — multi-colored parallel lines framing rounded photos, very distinctive
2. **Custom "Thorce" display font** — gives entire site a hand-drawn, organic personality
3. **Marquee ticker** — adds energy and movement, communicates key selling points
4. **Dark maroon audio demo card** in hero — audio demos front-and-center, immediately accessible
5. **Warm, cohesive 70s color palette** — every color works together
6. **Services pill grid** — clean 3x3 grid of rounded, light-green pill-shaped cards
7. **Staggered photo placement** — overlapping photos at different sizes creates visual depth

---

## FEATURE CLASSIFICATION FOR CARINA

### QUICK WIN (Achievable in Pro tier)

| Feature | Source | Implementation |
|---------|--------|---------------|
| Warm earthy color palette | Hunter | CSS variables: turquoise/purple/pink per Carina's request, gemstone tones |
| Custom display font for headings | Hunter (Thorce) | Use a display/handwritten font (e.g., Playfair Display, Cormorant) for artistic feel |
| Poppins or similar clean body font | Hunter | Font swap in config |
| Split-hero layout (text + photo) | Both | Standard 2-col hero |
| Dark card for audio demos | Hunter | Dark bg container with border-radius for audio section |
| 3 stacked audio players | Hunter | HTML5 `<audio>` elements with custom CSS — straightforward |
| Services/skills pill grid | Hunter | CSS grid with rounded cards |
| Testimonial section | Hunter | Styled quote card |
| FAQ accordion | Hunter | CSS/JS accordion component |
| Numbered "How it works" steps | Hunter | Simple numbered list with styling |
| Social icons with hover scale | Hunter | CSS transform on hover |
| Scroll-to-top button | Hunter | Standard fixed-position button |
| Warm orange/gemstone CTA buttons | Hunter | Button color from palette |
| All-caps display headings | Both | text-transform: uppercase on headings |
| Large hero heading (60px+) | Both | Font-size adjustment |

### PREMIUM UPSELL (Beyond Pro tier — custom development)

| Feature | Source | Why It's Premium | Estimated Effort |
|---------|--------|-----------------|-----------------|
| **Persistent sticky audio player bar** | Rodrigo | Custom JS audio controller that persists across scroll, with progress bar, track switching. Not a simple `<audio>` tag. | 4-6 hrs |
| **Full playlist with 10+ tracks** | Rodrigo | Track list UI, numbered queue, per-track share, next/prev logic. Requires custom audio engine. | 6-8 hrs |
| **Retro stripe photo borders** | Hunter | Custom CSS/SVG decorative borders with multiple colored parallel lines around photos. Requires hand-crafted SVG or complex border-image. | 3-4 hrs |
| **Marquee/ticker animation** | Hunter | Infinite scroll CSS animation with duplicated content for seamless loop. | 2-3 hrs |
| **Image carousel in hero** | Rodrigo | Auto-rotating crossfade slideshow with multiple photos. | 2-3 hrs |
| **Page frame/border effect** | Rodrigo | Consistent border around all content — affects entire layout structure. | 1-2 hrs |
| **Scroll-triggered zoom-in animations** | Hunter | Intersection Observer + CSS animations per element. | 2-3 hrs |
| **Photo lightbox with blur backdrop** | Hunter | Custom lightbox with zoom animation + backdrop-filter. | 2-3 hrs |
| **Music sheet watermark texture** | Rodrigo | Custom background texture/pattern — requires design asset. | 1-2 hrs |
| **Staggered/overlapping photo layouts** | Hunter | Complex absolute/relative positioning, responsive adjustments. | 3-4 hrs |
| **Events/shows calendar table** | Rodrigo | Paginated event listing with date formatting. | 3-4 hrs |

---

## RECOMMENDATION FOR CARINA'S PRO BUILD

### What to include (Pro tier):
1. **3 audio players** in a dark-themed card section (like Hunter's hero demo card) — HTML5 `<audio>` with custom-styled controls
2. **Gemstone color palette:** turquoise (#06B6D4 or #0D9488), amethyst purple (#8B5CF6), rose pink (#EC4899), with warm cream background (#F5F0EB)
3. **Display heading font** (artistic/editorial) + clean body font
4. **Split hero** with large heading + subtitle + photo
5. **Skills/services grid** in rounded pill cards
6. **Testimonial card** section
7. **Bio section** with photo
8. **Contact/CTA** section

### What to pitch as upgrade:
- "Quieres un reproductor de audio que se quede fijo mientras navegas por la pagina, como en rodrigoponce.com? Eso es un feature custom que podemos agregar por S/.XX"
- "Los bordes retro con lineas de colores alrededor de tus fotos como en hunterguidroz.com requieren diseno custom"
- "El ticker/marquee animado con tus servicios es un upgrade visual genial para tu perfil de artista"
