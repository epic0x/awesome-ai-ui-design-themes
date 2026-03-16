# Dark Explorer

> A deep, immersive dark theme with rich navy backgrounds and vibrant green accents — evoking the feel of a premium travel or outdoor adventure app.

## Color Palette

### Backgrounds
- Primary background: `#0B1726` — deep navy, used as the main canvas
- Secondary background: `#111D2E` — slightly lighter navy for content sections
- Card background: `#142236` — dark blue-grey with subtle transparency for card panels
- Overlay background: `rgba(11, 23, 38, 0.85)` — semi-transparent dark overlay on images

### Accent Colors
- Primary accent: `#2ECC71` — vibrant green for CTAs, buttons, and highlights
- Primary accent gradient: `linear-gradient(135deg, #2ECC71, #27AE60)` — green gradient for primary buttons
- Secondary accent: `#1ABC9C` — teal-green for secondary interactive elements
- Link accent: `#2ECC71` — green for hyperlinks and tappable text

### Text Colors
- Primary text: `#FFFFFF` — pure white for headings and primary content
- Secondary text: `#B0BEC5` — soft blue-grey for body text and descriptions
- Muted text: `#607D8B` — dimmed blue-grey for placeholders, labels, hints
- Accent text: `#2ECC71` — green for links, highlights, and call-to-action text

### Status & Feedback Colors
- Star rating: `#F39C12` — warm amber/orange for star ratings
- Success: `#2ECC71`
- Error: `#E74C3C`
- Warning: `#F39C12`

## Typography

- **Font family**: `'Inter', 'SF Pro Display', -apple-system, BlinkMacSystemFont, sans-serif`
- **Heading weight**: 700 (Bold) — large, commanding headings with slight letter-spacing (`0.02em`)
- **Subheading weight**: 600 (Semibold)
- **Body weight**: 400 (Regular)
- **Heading sizes**: H1: `2rem`, H2: `1.5rem`, H3: `1.25rem`
- **Body text**: `0.875rem` / `1rem`, line-height `1.6`
- **Text transform**: Uppercase with wide letter-spacing (`0.15em`) on CTA button labels (e.g., "LOGIN", "BOOK NOW")

## Buttons

### Primary Button
- Background: `linear-gradient(135deg, #2ECC71, #27AE60)`
- Text color: `#FFFFFF`
- Font weight: 700
- Text transform: uppercase, letter-spacing `0.15em`
- Border radius: `12px`
- Padding: `14px 32px`
- Shadow: `0 4px 15px rgba(46, 204, 113, 0.3)`
- Hover: brighten gradient, increase shadow to `0 6px 20px rgba(46, 204, 113, 0.45)`
- Active: scale down slightly (`transform: scale(0.97)`)

### Secondary / Outline Button
- Background: `transparent`
- Border: `1.5px solid #2ECC71`
- Text color: `#2ECC71`
- Border radius: `12px`
- Hover: fill with `rgba(46, 204, 113, 0.1)`, brighten border

### Text Button / Link
- Color: `#2ECC71`
- Font weight: 600
- Text decoration: underline on hover
- No background or border

## Cards

- Background: `#142236` or `rgba(20, 34, 54, 0.9)`
- Border radius: `16px`
- Border: `1px solid rgba(255, 255, 255, 0.05)`
- Shadow: `0 8px 32px rgba(0, 0, 0, 0.3)`
- Padding: `16px – 24px`
- Image corners match card radius (clip overflow)
- Hover: subtle lift with increased shadow `0 12px 40px rgba(0, 0, 0, 0.4)`

## Form Inputs

- Background: `rgba(255, 255, 255, 0.05)`
- Border: `1px solid rgba(255, 255, 255, 0.1)`
- Border radius: `10px`
- Text color: `#FFFFFF`
- Placeholder color: `#607D8B`
- Padding: `12px 16px`
- Focus: border color `#2ECC71`, shadow `0 0 0 3px rgba(46, 204, 113, 0.15)`
- Icons inside inputs: `#607D8B`, size `18px`
- Labels: `#B0BEC5`, font-size `0.75rem`, uppercase

## Graphs & Data Visualization

- Chart line color: `#2ECC71`
- Chart fill/area: `rgba(46, 204, 113, 0.15)`
- Secondary data lines: `#1ABC9C`, `#3498DB`
- Grid lines: `rgba(255, 255, 255, 0.05)`
- Axis labels: `#607D8B`
- Tooltip background: `#1A2D42`
- Tooltip text: `#FFFFFF`
- Tooltip border: `1px solid rgba(46, 204, 113, 0.3)`

## Icons & Navigation

- Icon style: outlined / line icons (thin stroke)
- Default icon color: `#607D8B`
- Active icon color: `#2ECC71`
- Icon size: `22px – 26px`
- Bottom navigation: dark background matching primary bg, evenly spaced icons
- Navigation active indicator: icon fills with `#2ECC71`, optional dot indicator below

## General Effects

- **Border radius scale**: small (`8px`), medium (`12px`), large (`16px`), pill (`9999px`)
- **Shadows**: use dark, diffused shadows — `0 8px 32px rgba(0, 0, 0, 0.3)`
- **Image overlays**: dark gradient overlay on hero images — `linear-gradient(to bottom, transparent 40%, #0B1726 100%)`
- **Transitions**: all interactive elements — `transition: all 0.2s ease`
- **Scrollbar**: thin, dark with green thumb
- **Selection color**: green highlight (`::selection { background: rgba(46, 204, 113, 0.3) }`)
