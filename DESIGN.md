---
name: Sinaloa Street Roll Modern Dark
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#ddc1b0'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#a58c7c'
  outline-variant: '#564336'
  surface-tint: '#ffb783'
  primary: '#ffb783'
  on-primary: '#4f2500'
  primary-container: '#ff8a1f'
  on-primary-container: '#633000'
  inverse-primary: '#944a00'
  secondary: '#a1d662'
  on-secondary: '#1e3700'
  secondary-container: '#447200'
  on-secondary-container: '#bdf57c'
  tertiary: '#ffb4a9'
  on-tertiary: '#690002'
  tertiary-container: '#ff8676'
  on-tertiary-container: '#820003'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdcc5'
  primary-fixed-dim: '#ffb783'
  on-primary-fixed: '#301400'
  on-primary-fixed-variant: '#713700'
  secondary-fixed: '#bcf37b'
  secondary-fixed-dim: '#a1d662'
  on-secondary-fixed: '#0f2000'
  on-secondary-fixed-variant: '#2e4f00'
  tertiary-fixed: '#ffdad5'
  tertiary-fixed-dim: '#ffb4a9'
  on-tertiary-fixed: '#410001'
  on-tertiary-fixed-variant: '#930004'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  headline-xl:
    fontFamily: Outfit
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
  headline-xl-mobile:
    fontFamily: Outfit
    fontSize: 30px
    fontWeight: '800'
    lineHeight: 36px
  headline-lg:
    fontFamily: Outfit
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
  headline-md:
    fontFamily: Outfit
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
  title-sm:
    fontFamily: Outfit
    fontSize: 18px
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
    lineHeight: 16px
  label-lg:
    fontFamily: Outfit
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 18px
  label-md:
    fontFamily: Outfit
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
  label-sm:
    fontFamily: Outfit
    fontSize: 10px
    fontWeight: '800'
    lineHeight: 12px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-lg: 1.5rem
  margin: 1rem
  margin-md: 1.5rem
  margin-lg: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system channels a high-energy, mouth-watering "premium street food" mood specifically crafted for modern culinary sushi culture from Sinaloa. It bridges fast-paced accessibility with indulgent culinary craft: deep charcoal and obsidian foundations elevate rich culinary hues (gratin orange, sriracha red, fresh avocado green).

The emotional tone is dynamic, crave-inducing, bold, and welcoming. Surfaces stay sleek and night-mode first, evoking the sizzle of blowtorched gratins, freshly sliced rolls, and warm street-corner vibes. Interface layers avoid stiff corporate geometry in favor of rounded, organic contours, tactile pill buttons, and subtle warm-tinted glows.

## Colors

The palette is engineered around dark surfaces that force food photography and status cues into vivid focus:

- **Primary (`#FF8A1F`)**: Warm gratin orange directly inspired by the brand mark. Used for primary calls-to-action, active tabs, price highlights, and focus rings.
- **Secondary (`#7BAE3F`)**: Crisp avocado green derived from the sushi mark badge. Used for veggie tags, freshness indicators, and secondary supportive highlights.
- **Tertiary (`#E63B2E`)**: Sriracha red for spicy tier indicators, hot deal pills, limited-time roll badges, and destructive states.
- **Neutral Base (`#121212` & `#181818`)**: Deep charcoal foundations keeping contrast gentle on eyes while maintaining visual punch.
- **Card Surfaces (`#1E1E1E` & `#262626`)**: Tonal elevated tiers providing clear component boundaries without relying on harsh strokes.
- **WhatsApp Accent (`#25D366`)**: Reserved strictly for instant-order WhatsApp touchpoints and direct order validation flows.
- **Text Hierarchy**: Cream soft text (`#F6EBDD`) for headings and lead copy to soften contrast against pure blacks, complemented by crisp neutral white (`#FFFFFF`) for micro-labels and badges.

## Typography

Typography pairs the punchy, rounded geometric authority of **Outfit** for headlines, prices, and badges with the utilitarian legibility of **Inter** for descriptions, ingredient lists, and nutritional info.

- Headings use heavier weights (700–800) with compact line heights to create appetizing poster-like street menus.
- Price tags utilize `Outfit` Bold with slight negative tracking to give numbers impact.
- Body copy relies on `Inter` Regular (400) and Medium (500) set in warm off-white (`#F6EBDD`) to ensure effortless reading over dark panels.
- Micro-labels and food badges (e.g., "HORNEADO", "SPICY", "PROMO") use uppercase `Outfit` with generous letter spacing (`0.06em`).

## Layout & Spacing

The layout is built on an adaptive responsive structure optimized primarily for mobile ordering and handheld browsing, scaling seamlessly to desktop takeout orders:

- **Mobile (<768px)**: 4-column layout with 16px margins and gutters. Cards take 100% width or run in horizontal peek-carousels. Sticky bottom bar contains quick cart totals and one-tap WhatsApp ordering.
- **Tablet (768px–1024px)**: 8-column layout with 24px margins, displaying food cards in 2-column grids with quick filtering chips fixed under category navigation.
- **Desktop (>1024px)**: 12-column layout capped at 1280px max-width, with 3 to 4 columns per food item and a persistent sticky sidebar displaying the live ticket order.

Internal component gaps follow an 8pt spatial cadence: tight 4px–8px groupings for ingredient tags and pricing, and generous 16px–24px gaps between promotional rolls and category groupings.

## Elevation & Depth

Visual hierarchy leverages layered dark tones reinforced by subtle warm-cast lighting rather than traditional cold gray drop shadows:

- **Base Layer (`#121212`)**: The canvas floor where section dividers and background watermarks rest.
- **Surface Layer 1 (`#1E1E1E`)**: Food item cards, search bars, and collapsed accordion containers. Bordered with a hairline stroke: `1px solid rgba(246, 235, 221, 0.08)`.
- **Surface Layer 2 (`#262626`)**: Floating modaled sheets, customization trays (e.g., extra chipotle dressing, fried cream cheese), and hover card states.
- **Ambient Glow Shadow**: Interactive floating elements (such as primary buttons and sticky cart banners) receive a soft radial glow: `box-shadow: 0 12px 32px -4px rgba(255, 138, 31, 0.25)`.
- **WhatsApp Float Shadow**: Instant WhatsApp floating triggers carry: `box-shadow: 0 8px 24px -2px rgba(37, 211, 102, 0.35)`.

## Shapes

The design system embraces generous, friendly rounded corners that match the smooth rolls and warm sauces of street-style sushi:

- Standard cards, promo banners, and modal sheets use `rounded-lg` (16px to 20px).
- Small badges, interactive chips, tag indicators, and buttons adopt full pill radius (`rounded-full` or 9999px) to echo the circular motif of the logo.
- Food photography frames always clip with `rounded-lg` to create harmonious balance against the card shells.

## Components

### Buttons
- **Primary Order Button**: Solid gratin orange (`#FF8A1F`), pill-shaped, text in rich black (`#121212`) `Outfit` Bold. On press, delivers an appetizing amber glow.
- **WhatsApp Action Button**: Branded `#25D366` green background, white typography with WhatsApp icon, rounded-full pill styling, positioned persistently or inline as "Pedir por WhatsApp".
- **Secondary / Ghost**: Dark surface (`#262626`) with 1px border `rgba(246, 235, 221, 0.15)` and cream text (`#F6EBDD`).

### Food Cards
- Modular dark card (`#1E1E1E`) with 18px corner radius.
- Top: 16:10 or 1:1 crisp food photo with top-left floating badges (e.g., "HOT ROLL", "GRATINADO", "NUEVO").
- Middle: Roll name in `Outfit` SemiBold (`#F6EBDD`), followed by short ingredients (surimi, philadelphia, aguacate, salsa de anguila) in muted `Inter` (`#A39E98`).
- Bottom: Large orange price tag with a circular (+) stepper or pill "Agregar" button.

### Badges & Chips
- **Spicy / Sriracha Tag**: Solid `#E63B2E` with white text, micro flame icon.
- **Avocado / Veggie Tag**: Subtle `#7BAE3F` background with deep tint for natural balance.
- **Filter Chips**: Pill shape, background `#1E1E1E` when inactive, solid `#FF8A1F` with dark text when active.

### Input Fields & Steppers
- Background `#1E1E1E`, subtle outline `rgba(246, 235, 221, 0.12)`, active focus ring in glowing primary `#FF8A1F`.
- Quantity steppers: Rounded pill container with tactile `+` and `-` touch targets.

### Promotional Banners
- Featured sushi specials wrapped in rich gradient backgrounds (`linear-gradient(135deg, #262626 0%, #1A120B 100%)`) with warm orange rim highlights and urgent combo deal badges.