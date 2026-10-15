---
name: Marg Navigator
colors:
  surface: '#2f0205'
  surface-dim: '#2f0205'
  surface-bright: '#622627'
  surface-container-lowest: '#270003'
  surface-container-low: '#3b080c'
  surface-container: '#400c10'
  surface-container-high: '#4e1719'
  surface-container-highest: '#5c2123'
  on-surface: '#ffdad8'
  on-surface-variant: '#dac1be'
  inverse-surface: '#ffdad8'
  inverse-on-surface: '#561d1f'
  outline: '#a28c89'
  outline-variant: '#544341'
  surface-tint: '#ffb3ad'
  primary: '#ffb3ad'
  on-primary: '#5b1917'
  primary-container: '#4a0c0c'
  on-primary-container: '#cd716a'
  inverse-primary: '#964641'
  secondary: '#ffb4a5'
  on-secondary: '#650a00'
  secondary-container: '#8a1c09'
  on-secondary-container: '#ff9a86'
  tertiary: '#ffb3ad'
  on-tertiary: '#68000a'
  tertiary-container: '#510006'
  on-tertiary-container: '#f5514e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb3ad'
  on-primary-fixed: '#3e0405'
  on-primary-fixed-variant: '#792f2b'
  secondary-fixed: '#ffdad3'
  secondary-fixed-dim: '#ffb4a5'
  on-secondary-fixed: '#3f0400'
  on-secondary-fixed-variant: '#8a1c09'
  tertiary-fixed: '#ffdad7'
  tertiary-fixed-dim: '#ffb3ad'
  on-tertiary-fixed: '#410004'
  on-tertiary-fixed-variant: '#930013'
  background: '#2f0205'
  on-background: '#ffdad8'
  surface-variant: '#5c2123'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 36px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
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
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1rem
  margin-tablet: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system establishes an academic yet vibrant and accessible guidance interface tailored for Indian secondary and higher-secondary students (Grades 8–12, collegiate aspirants, and their guardians). It blends academic credibility with aspirational momentum. 

### Visual Identity & Movement
The design movement is **Modern Tactile-SaaS with Warm Editorial Highlights**. It deliberately moves away from dry, bureaucratic educational portals and intimidating exam dashboards, delivering instead an encouraging, structured, and modern digital mentor. The visual environment prioritizes:
- **Academic Credibility:** Structured layouts, authoritative deep framing, and clear institutional cues that reassure parents and educators.
- **Youthful Optimism:** Luminous accent energy points paired with encouraging milestones that reward micro-progress and demystify complex academic decisions.
- **Clarity & Cognitive Ease:** High legibility, uncluttered multi-tier cards, and generous tap targets designed for entry-level smartphones and high-stress decision periods (e.g., board exams, stream selection, college entrances).

## Colors

The palette balances institutional trust with optimistic milestone tracking:

- **Primary (`#4A0C0C` - Deep Crimson Slate):** Used for structural navigation headers, primary titles, high-emphasis text, and bedrock interface architecture. Conveys authority, grounding, and seriousness of purpose.
- **Secondary (`#C4462F` - Optimistic Rust/Saffron):** Signifies aspiration, call-to-action moments, high-compatibility match indicators, and active pathway transitions. Injected deliberately to evoke energy without visual fatigue.
- **Tertiary (`#D63B3B` - Electric Red-Teal Alternate):** Dedicated to verified credentials, completed milestones, psychometric balance metrics, and active mentorship statuses.
- **Neutral Surface Palette:**
  - Background Canvas: Dark immersive surface theme
  - Card & Modal Surfaces: Deep container variants
  - Borders & Dividers: Muted structural lines
  - Body & Auxiliary Text: Grounded neutral tones

## Typography

The typography couples the friendly, geometric geometry of **Plus Jakarta Sans** for headlines and high-level milestones with the utilitarian legibility of **Inter** for data tables, descriptions, assessment questions, and career pathway trees.

- **Plus Jakarta Sans (Headings & Metrics):** Provides open apertures and curved friendliness, preventing the app from feeling overly bureaucratic or stressful.
- **Inter (Body & Controls):** Delivers clean readability across lower-density screens and ensures numerical legibility for entrance exam rankings, course durations, and fee metrics.
- Keep letter spacing tight on large display headers (-0.02em) and slightly spaced (+0.02em) on micro-caps/metadata labels.

## Layout & Spacing

The layout is built around a mobile-first fluid grid optimized for portrait interactions, one-handed navigation, and variable device viewports common across budget Android hardware.

### Layout Principles
- **Grid Architecture:** 4-column fluid layout on mobile screens (<600px) with `0.75rem` gutters and `1rem` safe-edge margins. Expands to 8 columns on tablet viewports (600px–1024px) with `1.5rem` outer margins.
- **Vertical Rhythm:** 4px baseline sub-grid (`0.25rem`). Component stacks, roadmaps, and questionnaire prompts conform strictly to multiples of 4px.
- **Thumb-Zone Optimization:** Bottom navigation bars, primary CTAs (e.g., "Take Assessment", "Book Slot"), and multi-select stream chips must rest within the comfortable lower 40% of the viewport.

## Elevation & Depth

Visual hierarchy is maintained through crisp, low-contrast boundary lines combined with tinted ambient drop shadows adapted for the dark theme environment.

- **Base Canvas:** Immersive dark base canvas provides the foundational layer.
- **Card Surfaces:** Layer 1 surfaces rely on a subtle boundary outline reinforced with ambient shadows.
- **Floating Modals & Counselor Drawers:** Raised surface elevated via soft tonal layering.
- **Pathways & Progression Lines:** Roadmaps utilize subtle debossed tracks overlaid with solid connection segments to denote current and completed milestones.

## Shapes

The design system adopts a **Rounded (Level 2)** shape standard:
- Standard interactive elements (inputs, standard buttons, counselor cards) use `0.5rem` (`rounded-md`).
- Primary content containers, guidance panels, and pathway hubs use `1rem` (`rounded-lg`).
- High-level modal drawers and student highlight summaries use `1.5rem` (`rounded-xl`).
- Micro-badges, stream selector pills, and psychometric tags use fully rounded pill contours (`9999px`) to invite active physical interaction and tapping.

## Components

### Buttons & Interactive CTAs
- **Primary Buttons:** High-density `#4A0C0C` background with crisp text, `0.5rem` border-radius, `48px` minimum height for accessible touch targets.
- **Accent Action CTAs:** Solid `#C4462F` with white text, reserved exclusively for high-intent career decisions.
- **Secondary / Ghost Buttons:** Transparent background with border and primary typography.

### Stream Selector Pills & Badges
- **Stream Pills:** Horizontal scrollable or wrap-segmented pills (`9999px` radius).
  - *Inactive:* Surface container background, border, auxiliary label.
  - *Active:* Primary background, white label, with category accent indicators.
- **Psychometric Fit Badges:** Pill-shaped tags displaying match confidence styled with soft alpha tint fills and bold colored text.

### Verification Tags & Counselor Booking Slots
- **School Mentor Verification Tags:** Inline micro-components featuring an outlined shield check icon, accent icon fill, and label text.
- **Counselor Booking Slots:** Compact card grid items with 2-line structure (Time, Date). Unselected slots use standard borders; selected slots toggle to active accent rings.

### Career Pathway Roadmaps
- Vertical timeline tracks utilizing a central 2px dashed spine.
- Completed nodes show a solid accent badge containing a checkmark; active target nodes show a pulsing ring; future stages are rendered with muted borders.
- Milestones feature compact cards detailing entry exams and required subject combinations.

### Student Progress Cards
- Container cards with borders and `1rem` corner rounding.
- Features dual-metric progress rings or segmented bar indicators using primary and secondary theme accents for assessment completion and career exploration depth.