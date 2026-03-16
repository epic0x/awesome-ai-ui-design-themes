# Lavender Breeze

> A soft, light, and friendly theme dominated by pastel purple/lavender gradients and clean white surfaces — gentle, approachable, and modern.

## Color Palette

### Backgrounds

- Primary background: `#F3F0F9` — very light lavender-grey page canvas
- Header/hero background: `linear-gradient(135deg, #A78BFA, #C084FC)` — soft purple gradient for top sections
- Card background: `#FFFFFF` — clean white for content cards
- Surface background: `rgba(167, 139, 250, 0.08)` — faint lavender tint for subtle sections

### Accent Colors

- Primary accent: `#8B5CF6` — medium purple for buttons, icons, and active states
- Secondary accent: `#A78BFA` — lighter purple for secondary elements and gradient endpoints
- Accent gradient: `linear-gradient(135deg, #A78BFA, #C084FC)` — soft lavender gradient
- CTA accent: `#7C3AED` — deeper violet for important action buttons
- Highlight green: `#10B981` — used sparingly for success indicators and status dots

### Text Colors

- Primary text: `#1F2937` — dark charcoal for headings on white backgrounds
- Primary text on purple: `#FFFFFF` — white text on purple/gradient backgrounds
- Secondary text: `#6B7280` — medium grey for body text and descriptions
- Muted text: `#9CA3AF` — light grey for placeholders, labels, hints
- Accent text: `#7C3AED` — purple for links and interactive text
- Price/highlight text: `#8B5CF6` — purple for prices and key data

### Status & Feedback Colors

- Success: `#10B981`
- Error: `#EF4444`
- Warning: `#F59E0B`

## Typography

- **Font family**: `'Poppins', 'Inter', -apple-system, BlinkMacSystemFont, sans-serif`
- **Heading weight**: 700 (Bold) — friendly and prominent
- **Subheading weight**: 600 (Semibold)
- **Body weight**: 400 (Regular)
- **Label weight**: 500 (Medium)
- **Heading sizes**: H1: `1.75rem`, H2: `1.375rem`, H3: `1.125rem`
- **Body text**: `0.875rem`, line-height `1.6`
- **Style**: rounded, soft feel — avoid sharp or condensed typefaces
- **Button text**: `font-weight: 600`, `text-transform: uppercase`, `letter-spacing: 0.08em` for large CTAs

## Buttons

### Primary Button (on white bg)

- Background: `linear-gradient(135deg, #A78BFA, #8B5CF6)`
- Text color: `#FFFFFF`
- Font weight: 600
- Text transform: uppercase, letter-spacing `0.08em`
- Border radius: `9999px` (fully rounded / pill shape)
- Padding: `14px 36px`
- Shadow: `0 4px 12px rgba(139, 92, 246, 0.25)`
- Hover: brighten gradient, shadow `0 6px 18px rgba(139, 92, 246, 0.35)`
- Active: `transform: scale(0.97)`

### Secondary / Outline Button (on purple bg)

- Background: `#FFFFFF`
- Text color: `#7C3AED`
- Font weight: 600
- Border radius: `9999px` (pill)
- Border: none (solid white fill)
- Padding: `10px 28px`
- Hover: `background: #F5F3FF`

### Small Action Button

- Background: `#FFFFFF`
- Border: `1.5px solid #8B5CF6`
- Text color: `#8B5CF6`
- Font size: `0.75rem`
- Font weight: 600
- Border radius: `6px`
- Padding: `4px 14px`
- Text transform: uppercase

## Cards

- Background: `#FFFFFF`
- Border radius: `16px`
- Border: none (rely on shadow for elevation)
- Shadow: `0 2px 8px rgba(0, 0, 0, 0.06), 0 8px 24px rgba(0, 0, 0, 0.04)`
- Padding: `20px – 24px`
- Hover: shadow `0 4px 16px rgba(0, 0, 0, 0.08)`
- Cards on gradient backgrounds appear as elevated white panels
- Inner sections/groups: light grey divider `1px solid #F3F4F6`

## Form Inputs

- Background: `transparent` (on purple gradient backgrounds)
- Border: none, use bottom border only — `border-bottom: 1.5px solid rgba(255, 255, 255, 0.4)` (on purple) or `border-bottom: 1.5px solid #D1D5DB` (on white)
- Text color: `#FFFFFF` (on purple), `#1F2937` (on white)
- Placeholder color: `rgba(255, 255, 255, 0.6)` (on purple), `#9CA3AF` (on white)
- No border radius (underline input style)
- Focus: border-bottom color sharpens to `#FFFFFF` (on purple) or `#7C3AED` (on white)
- Label: above field, small text, same color as placeholder

## Graphs & Data Visualization

- Chart primary: `#8B5CF6`
- Chart secondary: `#A78BFA`
- Chart tertiary: `#C4B5FD`
- Chart fill/area: `rgba(139, 92, 246, 0.1)`
- Grid lines: `#F3F4F6`
- Axis labels: `#9CA3AF`
- Tooltip background: `#FFFFFF`
- Tooltip shadow: `0 4px 12px rgba(0, 0, 0, 0.08)`
- Tooltip text: `#1F2937`
- Price values: `#8B5CF6`, `font-weight: 700`

## Icons & Navigation

- Icon style: filled or semi-filled with rounded shapes
- Default icon color: `#9CA3AF` (on white), `rgba(255, 255, 255, 0.6)` (on purple)
- Active icon color: `#7C3AED` (on white), `#FFFFFF` (on purple)
- Icon size: `22px – 26px`
- Bottom navigation: white background, purple active icon
- Location/map pin icons: `#8B5CF6`

## General Effects

- **Border radius scale**: small (`8px`), medium (`12px`), large (`16px`), pill (`9999px`)
- **Dominant shape language**: rounded, soft, pill-shaped buttons and elements
- **Shadows**: light and airy — `0 2px 8px rgba(0, 0, 0, 0.06)` for cards
- **Gradients**: soft purple gradients (`#A78BFA` → `#C084FC`) liberally used on headers, hero sections, and backgrounds
- **Gradient waves**: subtle wave or organic shapes in the purple gradient areas for visual depth
- **Dividers**: very light `#F3F4F6` or none (use whitespace)
- **Transitions**: `transition: all 0.2s ease`
- **Scrollbar**: thin with lavender thumb
- **Selection color**: `::selection { background: rgba(139, 92, 246, 0.2) }`
- **Overall mood**: approachable, gentle, pastel — never harsh or heavy
