# Soft Violet

> A clean, light-mode UI theme with a gentle violet/purple accent — minimal, modern, and airy with a focus on clarity and readability.

## Color Palette

### Backgrounds
- Primary background: `#F4F0FA` — very light lavender-grey page canvas
- Secondary background: `#FFFFFF` — pure white for cards and content panels
- Tertiary background: `#EDE7F6` — light violet tint for highlighted sections or alternating rows

### Accent Colors
- Primary accent: `#7C3AED` — rich violet/purple for buttons, links, active states
- Primary accent hover: `#6D28D9` — darker violet on hover
- Secondary accent: `#A78BFA` — lighter violet for tags, badges, secondary highlights
- Accent background: `rgba(124, 58, 237, 0.08)` — very faint violet for hover backgrounds and selected states

### Text Colors
- Primary text: `#1E1B4B` — deep indigo-black for headings and primary content
- Secondary text: `#4B5563` — neutral dark grey for body text
- Muted text: `#9CA3AF` — light grey for placeholders, hints, timestamps
- Accent text: `#7C3AED` — violet for links and highlighted text

### Status & Feedback Colors
- Star rating: `#F59E0B` — warm amber
- Success: `#10B981`
- Error: `#EF4444`
- Warning: `#F59E0B`
- Info: `#7C3AED`

## Typography

- **Font family**: `'Inter', 'Poppins', -apple-system, BlinkMacSystemFont, sans-serif`
- **Heading weight**: 700 (Bold)
- **Subheading weight**: 600 (Semibold)
- **Body weight**: 400 (Regular)
- **Caption/label weight**: 500 (Medium)
- **Heading sizes**: H1: `1.75rem`, H2: `1.375rem`, H3: `1.125rem`
- **Body text**: `0.875rem`, line-height `1.6`
- **Letter-spacing**: `-0.01em` on headings, normal on body
- **Style**: clean, upright, no text-transform on headings

## Buttons

### Primary Button
- Background: `#7C3AED`
- Text color: `#FFFFFF`
- Font weight: 600
- Border radius: `10px`
- Padding: `10px 24px`
- Shadow: `0 2px 8px rgba(124, 58, 237, 0.2)`
- Hover: background `#6D28D9`, shadow `0 4px 12px rgba(124, 58, 237, 0.3)`
- Active: `transform: scale(0.98)`

### Secondary / Outline Button
- Background: `#FFFFFF`
- Border: `1.5px solid #D1D5DB`
- Text color: `#4B5563`
- Border radius: `10px`
- Hover: border color `#7C3AED`, text color `#7C3AED`, background `rgba(124, 58, 237, 0.04)`

### Small Action Button
- Background: `rgba(124, 58, 237, 0.08)`
- Text color: `#7C3AED`
- Font weight: 500
- Font size: `0.75rem`
- Border radius: `6px`
- Padding: `4px 12px`

## Cards

- Background: `#FFFFFF`
- Border radius: `14px`
- Border: `1px solid #E5E7EB`
- Shadow: `0 1px 3px rgba(0, 0, 0, 0.04), 0 4px 12px rgba(0, 0, 0, 0.03)`
- Padding: `20px – 24px`
- Hover: shadow `0 4px 16px rgba(0, 0, 0, 0.07)`, subtle lift
- Section headers inside cards: `font-weight: 600`, `color: #1E1B4B`, `font-size: 0.875rem`

## Form Inputs

- Background: `#FFFFFF`
- Border: `1.5px solid #D1D5DB`
- Border radius: `10px`
- Text color: `#1E1B4B`
- Placeholder color: `#9CA3AF`
- Padding: `10px 14px`
- Focus: border color `#7C3AED`, shadow `0 0 0 3px rgba(124, 58, 237, 0.1)`
- Label: `#4B5563`, font-size `0.75rem`, font-weight `500`, margin-bottom `4px`

## Graphs & Data Visualization

- Chart primary line/bar: `#7C3AED`
- Chart secondary: `#A78BFA`
- Chart tertiary: `#C4B5FD`
- Chart fill/area: `rgba(124, 58, 237, 0.08)`
- Grid lines: `#F3F4F6`
- Axis labels: `#9CA3AF`, font-size `0.75rem`
- Tooltip background: `#FFFFFF`
- Tooltip border: `1px solid #E5E7EB`
- Tooltip shadow: `0 4px 12px rgba(0, 0, 0, 0.08)`
- Tooltip text: `#1E1B4B`
- Data value highlights: colored with the accent — `#7C3AED` primary, `#EF4444` for high, `#10B981` for low
- Progress bars: gradient `linear-gradient(90deg, #7C3AED, #A78BFA)`

## Icons & Navigation

- Icon style: outlined / line icons (light stroke weight)
- Default icon color: `#9CA3AF`
- Active icon color: `#7C3AED`
- Icon size: `20px – 24px`
- Navigation bar: white background, top or bottom placement
- Active nav item: violet icon + optional violet dot indicator
- Sidebar menu items: left color bar indicator (`3px solid #7C3AED`) on active row

## General Effects

- **Border radius scale**: small (`6px`), medium (`10px`), large (`14px`), pill (`9999px`)
- **Shadows**: soft and subtle — `0 1px 3px rgba(0, 0, 0, 0.04)` (cards), `0 2px 8px rgba(124, 58, 237, 0.15)` (buttons)
- **Dividers**: `1px solid #E5E7EB`
- **Transitions**: `transition: all 0.15s ease`
- **Avatar borders**: `2px solid #7C3AED` or `2px solid #E5E7EB`
- **Badge/chip**: background `#EDE7F6`, text `#7C3AED`, border-radius `9999px`, padding `2px 10px`
- **Scrollbar**: thin, light grey track with violet thumb
- **Selection color**: `::selection { background: rgba(124, 58, 237, 0.15) }`
- **Calendar/date highlights**: selected date has `background: #7C3AED`, `color: #FFFFFF`, `border-radius: 10px`
