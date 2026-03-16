# Neon Cosmos

> A bold, futuristic dark theme with deep noir backgrounds, vivid purple-blue gradients, and glassmorphism effects — built for a sleek, high-tech aesthetic.

## Color Palette

### Backgrounds
- Primary background: `#0A0A1A` — near-black with a subtle blue undertone
- Secondary background: `#12122A` — dark indigo for sections and content areas
- Card background: `rgba(25, 25, 60, 0.7)` — semi-transparent dark purple with backdrop blur (glassmorphism)
- Surface background: `#1A1A3E` — solid dark purple for elevated surfaces

### Accent Colors
- Primary accent: `#8B5CF6` — vivid violet for primary interactive elements
- Secondary accent: `#6366F1` — indigo-blue for secondary interactive elements
- CTA accent: `#EF4444` — coral-red for call-to-action buttons (e.g., "Enter Now")
- Highlight: `#C084FC` — light violet for badges, tags, and highlights
- Gradient primary: `linear-gradient(135deg, #8B5CF6, #6366F1)` — violet-to-indigo
- Gradient background glow: `radial-gradient(ellipse at 20% 50%, rgba(139, 92, 246, 0.15), transparent 60%)` — soft purple ambient glow on page

### Text Colors
- Primary text: `#FFFFFF` — white for headings and key content
- Secondary text: `#C4B5FD` — light lavender for body text
- Muted text: `#6B7280` — dimmed grey for placeholders and captions
- Accent text: `#C084FC` — light purple for links and highlights

### Status & Feedback Colors
- Star rating: `#A78BFA` — soft violet stars
- Success: `#10B981`
- Error: `#EF4444`
- Warning: `#F59E0B`

## Typography

- **Font family**: `'Inter', 'Satoshi', -apple-system, BlinkMacSystemFont, sans-serif`
- **Heading weight**: 800 (Extra Bold) — large, impactful headings
- **Subheading weight**: 600 (Semibold)
- **Body weight**: 400 (Regular)
- **Heading sizes**: H1: `2.5rem`, H2: `1.75rem`, H3: `1.25rem`
- **Body text**: `0.875rem` / `1rem`, line-height `1.6`
- **Letter-spacing**: `-0.02em` on large headings for tightness
- **Heading style**: Title Case, large and bold

## Buttons

### Primary CTA Button
- Background: `#EF4444`
- Text color: `#FFFFFF`
- Font weight: 700
- Border radius: `12px`
- Padding: `12px 28px`
- Shadow: `0 4px 15px rgba(239, 68, 68, 0.3)`
- Hover: background `#DC2626`, shadow `0 6px 20px rgba(239, 68, 68, 0.4)`
- Active: `transform: scale(0.97)`

### Secondary / Ghost Button
- Background: `transparent`
- Border: `1.5px solid rgba(255, 255, 255, 0.2)`
- Text color: `#FFFFFF`
- Border radius: `9999px` (pill)
- Padding: `10px 24px`
- Hover: border color `#8B5CF6`, background `rgba(139, 92, 246, 0.1)`

### Accent Button
- Background: `linear-gradient(135deg, #8B5CF6, #6366F1)`
- Text color: `#FFFFFF`
- Border radius: `12px`
- Shadow: `0 4px 15px rgba(139, 92, 246, 0.25)`

## Cards

- Background: `rgba(25, 25, 60, 0.6)`
- Backdrop filter: `blur(16px)` (glassmorphism)
- Border: `1px solid rgba(255, 255, 255, 0.08)`
- Border radius: `16px – 20px`
- Shadow: `0 8px 32px rgba(0, 0, 0, 0.4)`
- Padding: `20px – 28px`
- Inner glow effect: `box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.05)`
- Hover: border brightens to `rgba(139, 92, 246, 0.2)`, shadow increases

## Form Inputs

- Background: `rgba(255, 255, 255, 0.05)`
- Border: `1.5px solid rgba(255, 255, 255, 0.12)`
- Border radius: `12px`
- Text color: `#FFFFFF`
- Placeholder color: `#6B7280`
- Padding: `12px 16px`
- Focus: border color `#8B5CF6`, shadow `0 0 0 3px rgba(139, 92, 246, 0.15)`
- Email/text input style: outlined with soft purple tint on focus

## Graphs & Data Visualization

- Chart primary line: `#8B5CF6`
- Chart secondary line: `#6366F1`
- Chart tertiary: `#C084FC`
- Chart fill/area: `rgba(139, 92, 246, 0.1)`
- Grid lines: `rgba(255, 255, 255, 0.04)`
- Axis labels: `#6B7280`
- Tooltip background: `#1A1A3E`
- Tooltip border: `1px solid rgba(139, 92, 246, 0.3)`
- Tooltip text: `#FFFFFF`
- Progress bars/sliders: `linear-gradient(90deg, #8B5CF6, #EC4899)` — violet to pink gradient

## Icons & Navigation

- Icon style: outlined / line icons
- Default icon color: `rgba(255, 255, 255, 0.5)`
- Active icon color: `#FFFFFF`
- Icon size: `20px – 24px`
- Social media icons: `#FFFFFF`, opacity `0.6`, hover to full opacity
- Navigation links: `#C4B5FD`, hover `#FFFFFF`

## General Effects

- **Border radius scale**: small (`8px`), medium (`12px`), large (`16px – 20px`), pill (`9999px`)
- **Glassmorphism**: `backdrop-filter: blur(16px)`, semi-transparent backgrounds, subtle borders
- **Ambient glow**: radial gradients of purple/violet on the page background to create depth
- **Shadows**: deep and dark — `0 8px 32px rgba(0, 0, 0, 0.4)`
- **Inner highlights**: `inset 0 1px 0 rgba(255, 255, 255, 0.05)` on cards/surfaces
- **Gradients**: liberal use of purple-to-pink and purple-to-blue gradients on backgrounds and decoratives
- **Transitions**: `transition: all 0.25s cubic-bezier(0.4, 0, 0.2, 1)`
- **Hover effects**: subtle glow increase, border brightening
- **Scrollbar**: thin dark with violet thumb
- **Selection color**: `::selection { background: rgba(139, 92, 246, 0.3) }`
- **3D / Depth**: UI element mockups appear tilted/angled — use subtle `transform: perspective()` rotations for decorative elements if desired
