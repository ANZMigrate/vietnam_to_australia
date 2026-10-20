# Vietnam to Australia design system

## Direction

A practical editorial system with a warm ochre signal colour and a strong emphasis on document readiness.

## Audience and tone

The primary audience is Vietnamese professionals, graduates and students. The voice is precise, calm and document-led. Explain the evidence and sequence rather than promising an outcome. Avoid vague conversion language and avoid claims that a visitor qualifies.

## Type

- Google Sans Flex, regular weight 400 for headings and body copy.
- Hero heading: clamp(44px, 5vw, 72px), 44px on mobile; line height 1.08 / 1.12.
- Section heading: 37.5px desktop / 35px mobile; line height 1.25.
- Supporting copy: 17.5px, line height 1.6; cards and labels: 15px, line height 1.6.
- Navy buttons #102568 with white text; hover #243966. Keep letter spacing normal.
- Light footer with subtle divider, dark text and keyboard focus states.
- See typography.md for the implemented type scale.

## Layout

- Maximum content width: 1440px.
- Page gutters use a responsive CSS variable.
- Hero layout uses an asymmetric two-column editorial composition on desktop.
- Content pages use page heroes, comparison rows, evidence cards, numbered process steps, FAQ details and a dark source panel.
- Keep long text below approximately 780px for comfortable reading.
- Mobile layout becomes one column with touch-sized controls and no horizontal scrolling.

## Colour and surfaces

Ochre accent on warm ivory, with rounded editorial cards.

The design uses warm or cool paper-like surfaces, ink text, muted secondary text, fine borders and one restrained accent. Colour is never the only signal for a visa type. Dark sections are used for source links and high attention transitions.

## Components

- Sticky text-only header with keyboard accessible mobile menu.
- Hero visual made from CSS geometry, not stock photography or a logo.
- Two route cards for skilled migration and study.
- Six visa cards or comparison rows for subclasses 189, 190, 491, 482, 186 and 494.
- Numbered process list for SkillSelect and Student visa preparation.
- Evidence cards for skills assessment and Genuine Student topics.
- Native FAQ details with one open item at a time.
- Footer with ANZ Migrate professional registration details, a Who We Are page and a privacy page. No contact form or Chatwoot widget.

## Motion

The local script uses GSAP for header entrance, hero entrance, card reveal and a restrained floating visual card. Motion is progressive enhancement. If GSAP does not load or reduced motion is enabled, all content remains visible and usable.

## Further development

- Add a real production hostname to the XML sitemap before launch.
- Recheck official Home Affairs and CRICOS URLs when content changes.
- If a form is added later, define the endpoint, privacy notice and success or error states before adding fields.
- Keep country-specific copy genuinely rewritten. Do not make doorway pages by changing only the country name.

## 2026 editorial refresh

- Mobbin inspiration: [Oyster](https://mobbin.com/sites/sections/67fdec3d-e3a1-49f7-9c34-9923acb1eba5) and [Complex Law](https://mobbin.com/sites/sections/d6b4e853-443b-4754-b6a3-626b51a82d0c); no external design assets copied.
- Midnight editorial hero, luminous geometric visa visualization, calm white information cards, refined mobile navigation and coherent inner-page treatment.
- Google Sans Flex typography with a system-font fallback; semantic content and material visa eligibility statements retained.
- GSAP-based entrance, card, and scroll-reveal enhancements retain reduced-motion and CDN failure fallbacks.
- The country-specific `site-vietnam` theme class controls the distinctive local palette.
