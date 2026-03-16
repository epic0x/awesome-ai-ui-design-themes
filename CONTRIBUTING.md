# Contributing to awesome-ai-ui-design-themes

Thank you for your interest in contributing! This project collects curated UI design themes that AI coding agents can use to style frontend applications. Here's how you can add a new theme.

---

## How to Add a New Theme

### 1. Create a New Theme Folder

Inside the `themes/` directory, create a new folder with the next sequential number (zero-padded to 4 digits):

```
themes/
  0001/
  0002/
  ...
  XXXX/   <-- your new folder
```

### 2. Add a Preview Image

Place a preview image in your theme folder. The file must be named `preview.jpg` or `preview.png`.

- The image should showcase the visual style of the theme (color palette, buttons, cards, typography, inputs, etc.)
- Recommended resolution: **1200×800** or higher
- Keep file size reasonable (under 2MB)

### 3. Create a `THEME.md` File

This is the core of your contribution. The `THEME.md` file is a **structured design guideline** that an AI agent reads to build frontend UI matching the theme's visual style.

#### `THEME.md` Structure

```markdown
# Theme Name

> A one-line description of the theme's mood and feel.

## Color Palette

### Backgrounds

- Primary background: `#hexcode` — description
- Secondary background: `#hexcode` — description
- Card background: `#hexcode` — description

### Accent Colors

- Primary accent: `#hexcode` — usage
- Secondary accent: `#hexcode` — usage

### Text Colors

- Primary text: `#hexcode` — usage
- Secondary text: `#hexcode` — usage
- Muted text: `#hexcode` — usage

## Typography

- Font family recommendation (e.g., Inter, Poppins, system-ui)
- Font weights used (regular, medium, semibold, bold)
- Heading style (size scale, weight, letter-spacing)
- Body text style (size, line-height)

## Buttons

### Primary Button

- Background, text color, border-radius, padding
- Hover and active states

### Secondary / Outline Button

- Background, border, text color, border-radius
- Hover and active states

## Cards

- Background color, border-radius, shadow/border
- Padding and spacing
- Hover behavior (if any)

## Form Inputs

- Background, border, border-radius
- Focus state styling
- Placeholder text color
- Label styling

## Graphs & Data Visualization

- Chart line / bar / fill colors
- Axis and grid colors
- Tooltip styling
- Legend styling

## Icons & Navigation

- Icon style (outlined, filled, duotone)
- Active/inactive state colors
- Navigation bar styling

## General Effects

- Shadow styles (box-shadow values)
- Border-radius scale
- Glassmorphism / gradients / overlays (if applicable)
- Transitions and animation preferences
```

> **Important:** Focus on general visual guidelines (colors, buttons, fonts, cards, graphs, effects) — NOT on specific page layouts or screen structure. The goal is to let any AI agent apply the theme to **any** type of application.

### 4. Create a `README.md` for Your Theme Folder

Add a short `README.md` inside your theme folder that displays the preview image and instructions for using the theme.

```markdown
# Theme Name

![Theme Name](preview.jpg)

## Usage

1. Download the `THEME.md` file from this folder
2. Place it in the **root** of your application project
3. Ask your AI coding agent to follow the design guidelines in `THEME.md` when building UI
```

### 5. Update the Main `README.md`

Add your theme to the table in the main `README.md` in the root of the repository. Themes are shown two per row.

### 6. Submit a Pull Request

- Make sure your folder follows the naming convention (`XXXX/`)
- Ensure `preview.jpg` (or `.png`), `THEME.md`, and `README.md` exist in your folder
- Keep your PR focused on adding a single theme

---

## Guidelines

- **No copyrighted images**: Use original designs or properly licensed assets
- **Be descriptive**: The more specific your `THEME.md` color codes and guidelines, the better the AI output
- **Use hex colors**: Always provide exact hex color codes, not vague descriptions
- **Think portability**: Your theme should work for dashboards, landing pages, mobile apps, or any frontend — don't assume a specific layout

---

## Questions?

Open an issue if you're unsure about anything. We're happy to help!
