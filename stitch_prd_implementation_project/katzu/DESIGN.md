---
name: Katzu
colors:
  surface: '#14121f'
  surface-dim: '#14121f'
  surface-bright: '#3a3747'
  surface-container-lowest: '#0e0c1a'
  surface-container-low: '#1c1a28'
  surface-container: '#201e2c'
  surface-container-high: '#2a2837'
  surface-container-highest: '#353342'
  on-surface: '#e5e0f4'
  on-surface-variant: '#cac4d5'
  inverse-surface: '#e5e0f4'
  inverse-on-surface: '#312f3e'
  outline: '#948e9e'
  outline-variant: '#494553'
  surface-tint: '#cdbdff'
  primary: '#cdbdff'
  on-primary: '#360990'
  primary-container: '#997df7'
  on-primary-container: '#2f0084'
  inverse-primary: '#6548c0'
  secondary: '#d5baff'
  on-secondary: '#3d1e6c'
  secondary-container: '#543684'
  on-secondary-container: '#c6a5fc'
  tertiary: '#f1b4dc'
  on-tertiary: '#4b2141'
  tertiary-container: '#b780a5'
  on-tertiary-container: '#441a3a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e7deff'
  primary-fixed-dim: '#cdbdff'
  on-primary-fixed: '#20005f'
  on-primary-fixed-variant: '#4d2da6'
  secondary-fixed: '#ecdcff'
  secondary-fixed-dim: '#d5baff'
  on-secondary-fixed: '#270057'
  on-secondary-fixed-variant: '#543684'
  tertiary-fixed: '#ffd7ef'
  tertiary-fixed-dim: '#f1b4dc'
  on-tertiary-fixed: '#330b2b'
  on-tertiary-fixed-variant: '#653758'
  background: '#14121f'
  on-background: '#e5e0f4'
  surface-variant: '#353342'
  background-pure: '#000000'
  surface-card: '#1A1826'
  surface-card-subtle: '#221F33'
  text-primary: '#F2F0F7'
  text-secondary: '#A8A3BD'
  text-muted: '#6E6887'
  status-success: '#7FD9A8'
  status-learning: '#F0C674'
  status-error: '#E89B9B'
  article-der: '#7EA6FF'
  article-die: '#F5B8E0'
  article-das: '#7FD9A8'
typography:
  display-lg:
    fontFamily: Source Serif 4
    fontSize: 34px
    fontWeight: '600'
    lineHeight: 44px
  display-lg-mobile:
    fontFamily: Source Serif 4
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-lg:
    fontFamily: Source Serif 4
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Source Serif 4
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  headline-sm:
    fontFamily: Source Serif 4
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 26px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  space-2xs: 0.125rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-base: 1rem
  space-lg: 1.25rem
  space-xl: 1.5rem
  space-2xl: 2rem
  space-3xl: 2.5rem
  space-4xl: 3rem
  margin-mobile: 1.25rem
  gutter-mobile: 0.75rem
---

## Brand & Style

### Brand Personality & Philosophy
This design system defines an Arabic-first conversational German learning experience orchestrated by a deadpan, self-aware feline avatar. The persona balances dry, sarcastic humor with genuine encouragement—roasting the eccentricities of German grammar rather than the user's intelligence. The emotional atmosphere is low-pressure, focused, and midnight-sleek, replacing anxious academic pressure with intimate late-night study energy.

### Aesthetic Direction: AMOLED Midnight Tactility
The style synthesizes high-contrast dark-mode minimalism with refined tactile layers and ambient luminescence:
- **Pure AMOLED Black Backdrop:** Creates infinite depth and edge-to-edge optical continuity on mobile OLED displays.
- **Deep Muted Surfaces:** Charcoal-violet container slabs float over the pitch-black void, providing resting planes for content without glare.
- **Selective Bioluminescence:** Vibrant violet and magenta neon halos are reserved strictly for character focal points, interactive voice waveforms, and high-frequency active touchpoints.
- **Bilingual Typographic Tension:** Crisp geometric sans-serif shapes handle functional Arabic interface chrome and mechanics, contrasted against the authoritative, historical presence of literary serifs for German vocabulary and structural phrases.

## Colors

### The Midnight Palette Architecture
The palette is engineered for prolonged low-light focus, high contrast accessibility, and subtle emotional feedback.

- **Background (`#000000`):** True AMOLED black anchors the canvas across all views, eliminating visual border friction on modern edge-to-edge displays and saving battery during prolonged voice sessions.
- **Surfaces (`#1A1826`, `#221F33`):** Tinted obsidian slate surfaces supply structure without high-contrast light bleed. Secondary surfaces provide micro-contrast for grouped nested lists and interactive inputs.
- **Primary Accent (`#8B6FE8`):** A saturated medium amethyst functioning as the primary interactive driver. It commands buttons, toggles, voice playback indicators, and active navigational indicators.
- **Character Glow Halos (`#C9A8FF` → `#F5B8E0`):** Reserved for character states, active microphone audio pulses, and high-impact completion moments. Never applied indiscriminately to standard administrative UI.
- **Feedback & Grammatical Tints:**
  - `status-success` (`#7FD9A8`): Muted jade indicates correct pronunciation, mastered vocabulary, and completed daily milestones.
  - `status-learning` (`#F0C674`): Warm honey represents items in progress, hints, and grammatical mnemonics.
  - `status-error` (`#E89B9B`): Dusky rose signifies grammatical corrections and pronunciation slips, providing visibility without punitive visual aggression.
- **German Grammatical Genders:**
  - Masculine (`der`): Ice Slate Blue (`#7EA6FF`)
  - Feminine (`die`): Orchid Blossom (`#F5B8E0`)
  - Neuter (`das`): Mint Sage (`#7FD9A8`)

## Typography

### Typographic Hierarchy & Bidirectional Rules
The system deploys an intentional split-font methodology tailored for Arabic native speakers learning the structural mechanics of the German language:

1. **German Lexicon & Headlines (`Source Serif 4`):**
   - Imbues German sentences, nouns, and core prompts with typographic authority, historical weight, and clear letterform distinction (critical for capitalized nouns and complex compound words).
   - All German and English phrasing strictly enforces Left-to-Right (`ltr`) text directionality, regardless of parent screen mirroring.

2. **System Chrome & Arabic Phrasing (`Inter` paired with Arabic glyph coverage):**
   - Provides clean, neutral legibility for conversational instructions, UI labels, feedback messages, metrics, and navigation items.
   - Screen geometry adheres to Right-to-Left (`rtl`) layout rules by default.

3. **Punctuation & Bidirectional Wrapping:**
   - Mixed lines (e.g., German vocabulary embedded inside an Arabic sentence) rely on explicit isolation tags (`<bdi>` or Unicode isolates `U+2067`) to eliminate punctuation reversal at phrase boundaries.

## Layout & Spacing

### Grid & Layout Principles
The layout uses an 8dp baseline grid (with 4dp micro-increments) tailored for single-hand Android ergonomic flow.

- **Mobile Viewports (under 600dp):** Content aligns within a fluid single-column framework with fixed side margins of `20dp` (`1.25rem`), expanding to `24dp` on larger handheld panels.
- **RTL Screen Mirroring:**
  - Back buttons, scenario progressions, list accessory carets, and conversational avatars flip horizontally to conform to natural Arabic reading flow.
  - Media playback bars, audio waveform timers, and standalone German text blocks remain locked in LTR progression.
- **Vertical Stack Composition:** Interactive conversation views compress empty gutters to preserve maximum viewport height for voice transcriptions and responsive bottom-docked microphone controls.

## Elevation & Depth

### Tonal Stratification & Optical Light
Rather than high-contrast dropshadows, depth across this dark surface is established via subtle surface lightness gradation, ambient radiance, and translucent ghost borders.

- **Layer 0 (Background):** Pure `#000000`. Base plane.
- **Layer 1 (Card & Bottom Sheet Resting State):** `#1A1826` with an ultra-thin `1px` border of `rgba(242, 240, 247, 0.08)`.
- **Layer 2 (Elevated & Active States):** `#221F33` with an active tint border of `rgba(139, 111, 232, 0.24)`.
- **Character Halos & Mic Field:** A soft dual-stop radial diffusion using `rgba(201, 168, 255, 0.25)` blurring outward to `rgba(245, 184, 224, 0.0)` creates an ethereal spotlight behind the mascot sticker without compromising text readability.
- **Sheet Overlays:** Modals and bottom sheets project a backdrop blur of `16px` over `#00000088` to keep the background context intact while focusing input attention.

## Shapes

### Shape Hierarchy & Radii
The geometry emphasizes organic curves with high-comfort radii that echo the friendly, non-traditional feline mascot.

- **Primary Cards & Hero Modules:** `20px` (`1.25rem`) corner radius. Used for hero scenarios, daily overview banners, and interactive conversation corrective notices.
- **Standard List Items & Interactive Rows:** `16px` (`1rem`) corner radius. Applied to practice vocabulary items, grammar index entries, and settings groups.
- **Pills, Chips & Action Buttons:** Full circular radius (`9999px`). Applied to primary CTA buttons (`ابدأ`), grammar tags, CEFR level selectors, audio triggers, and speech inputs.
- **Sticker Asset Framing:** Sticker images must preserve their physical die-cut white outline intact without rectangular bounding boxes or programmatic clip paths.

## Components

### Buttons
- **Primary CTA:** Full-width pill (`height: 52px`), filled with `#8B6FE8`, text `#F2F0F7` in `label-lg`. Pressed state drops brightness to `#7659D4`.
- **Secondary Ghost Pill:** Outlined with `1.5px` border of `rgba(139, 111, 232, 0.4)`, transparent surface, text `#F2F0F7`.
- **Voice Mic Action:** Giant floating circle (`72dp` to `80dp`) with animated pulsing glow gradient (`#C9A8FF` to `#F5B8E0`). Displays active speech-wave animations during recording.

### Interactive Voice Bubble
- **Coach / Mascot Bubble:** Aligned to the start (right side in RTL), `#1A1826` fill, `20px` radius with a squared tap corner at top-start. German dialogue renders in `headline-md` serif with accent-colored audio playback buttons. Arabic translations display beneath in `body-sm` `#A8A3BD`.
- **User Voice Bubble:** Aligned to the end (left side in RTL), tinted `#25203B` fill, subtle `#8B6FE8` border outline.

### Diagnostic Correction Cards
- Rendered in a muted rose background (`rgba(232, 155, 155, 0.12)`) bounded by a delicate `1px` border of `#E89B9B`. Displays the user's erroneous phrase struck through, followed by the corrected German phrase in bold serif and a concise, dry explanation in Arabic.

### Chips & Tags
- **Article Indicator Badges:** Compact pills with small uppercase bold labels (`der`, `die`, `das`) colored according to their established grammatical hue with an 85% opacity surface tint.
- **Level Selector Pills:** Segmented pill container grouping `A1`, `A2`, `B1`, `B2`. Active level receives `#8B6FE8` solid fill; locked items carry a `50%` opacity filter and lock iconography.

### Form Inputs
- **Text Fields:** Height `52px`, pill or `16px` radius, background `#1A1826`, border `1px` solid `rgba(242, 240, 247, 0.12)`. Active focus transition illuminates border with `#8B6FE8` and a subtle outward glow.