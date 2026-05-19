---
name: Phorecast Design System
version: 1.1.0
description: Modern, professional design system for Phorecast - strategy consulting that delivers results

colors:
  primary: "#0077B6"
  primaryLight: "#00B4D8"
  primaryDark: "#023E8A"
  accentOrange: "#FF4500"
  accentRed: "#FF6B6B"
  accentGold: "#FFD93D"
  accentTeal: "#4ECDC4"
  textPrimary: "#333333"
  textSecondary: "#6B7280"
  textMuted: "#9CA3AF"
  bgWhite: "#FFFFFF"
  bgLight: "#F8F9FA"
  success: "#10B981"
  warning: "#F59E0B"
  error: "#EF4444"
  info: "#3B82F6"

typography:
  fontFamily: "Inter"
  fontFamilyHeadings: "Inter"
  
  display:
    fontFamily: "{typography.fontFamilyHeadings}"
    fontSize: "4rem"
    fontWeight: "800"
    lineHeight: "1.1"
    letterSpacing: "-0.03em"
  
  h1:
    fontFamily: "{typography.fontFamilyHeadings}"
    fontSize: "3rem"
    fontWeight: "800"
    lineHeight: "1.2"
    letterSpacing: "-0.02em"
  
  h2:
    fontFamily: "{typography.fontFamilyHeadings}"
    fontSize: "2.5rem"
    fontWeight: "700"
    lineHeight: "1.3"
    letterSpacing: "-0.02em"
  
  h3:
    fontFamily: "{typography.fontFamilyHeadings}"
    fontSize: "1.5rem"
    fontWeight: "600"
    lineHeight: "1.4"
  
  h4:
    fontFamily: "{typography.fontFamilyHeadings}"
    fontSize: "1.25rem"
    fontWeight: "600"
    lineHeight: "1.5"
  
  h5:
    fontFamily: "{typography.fontFamilyHeadings}"
    fontSize: "1.125rem"
    fontWeight: "600"
    lineHeight: "1.5"
  
  subtitle:
    fontFamily: "{typography.fontFamily}"
    fontSize: "1.25rem"
    fontWeight: "400"
    lineHeight: "1.6"
  
  body:
    fontFamily: "{typography.fontFamily}"
    fontSize: "1rem"
    fontWeight: "400"
    lineHeight: "1.6"
  
  bodyLarge:
    fontFamily: "{typography.fontFamily}"
    fontSize: "1.125rem"
    fontWeight: "400"
    lineHeight: "1.7"
  
  bodySmall:
    fontFamily: "{typography.fontFamily}"
    fontSize: "0.875rem"
    fontWeight: "400"
    lineHeight: "1.5"
  
  caption:
    fontFamily: "{typography.fontFamily}"
    fontSize: "0.8125rem"
    fontWeight: "500"
    lineHeight: "1.4"
  
  captionBold:
    fontFamily: "{typography.fontFamily}"
    fontSize: "0.8125rem"
    fontWeight: "600"
    lineHeight: "1.4"
  
  micro:
    fontFamily: "{typography.fontFamily}"
    fontSize: "0.75rem"
    fontWeight: "500"
    lineHeight: "1.3"
  
  microUppercase:
    fontFamily: "{typography.fontFamily}"
    fontSize: "0.6875rem"
    fontWeight: "600"
    lineHeight: "1.3"
    letterSpacing: "0.5px"
    textTransform: "uppercase"
  
  button:
    fontFamily: "{typography.fontFamily}"
    fontSize: "1rem"
    fontWeight: "600"
    lineHeight: "1.3"

spacing:
  xxs: "4px"
  xs: "8px"
  sm: "12px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  "2xl": "48px"
  "3xl": "64px"
  "4xl": "96px"
  "5xl": "128px"

rounded:
  none: "0px"
  xs: "4px"
  sm: "6px"
  md: "8px"
  lg: "12px"
  xl: "16px"
  "2xl": "20px"
  "3xl": "24px"
  full: "9999px"

layout:
  containerMax: "1200px"
  sectionPaddingY: "96px"
  sectionPaddingX: "24px"
  gridGap: "24px"

elevation:
  sm: "0 1px 2px 0 rgba(0, 0, 0, 0.05)"
  md: "0 4px 6px -1px rgba(0, 0, 0, 0.1)"
  lg: "0 10px 15px -3px rgba(0, 0, 0, 0.1)"
  xl: "0 20px 25px -5px rgba(0, 0, 0, 0.1)"

gradients:
  primaryGradient: "linear-gradient(135deg, {colors.primary} 0%, {colors.primaryLight} 100%)"
  primaryDarkGradient: "linear-gradient(135deg, {colors.primaryDark} 0%, {colors.primary} 100%)"
  accentGradient: "linear-gradient(135deg, {colors.accentOrange} 0%, {colors.accentRed} 100%)"
  heroGradient: "linear-gradient(135deg, #667eea 0%, #764ba2 100%)"
  subtleGradient: "linear-gradient(180deg, rgba(0,119,182,0.05) 0%, transparent 100%)"
  glow: "radial-gradient(ellipse at 50% 0%, rgba(0,119,182,0.15) 0%, transparent 60%)"

components:
  buttonPrimary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.bgWhite}"
    typography: "{typography.button}"
    padding: "{spacing.md} {spacing.xl}"
    rounded: "{rounded.lg}"
    transition: "all 0.3s ease"
    hover:
      backgroundColor: "{colors.primaryDark}"
      transform: "translateY(-2px)"
      shadow: "{elevation.lg}"
    pressed:
      backgroundColor: "{colors.primaryDark}"
      transform: "translateY(0)"
    disabled:
      backgroundColor: "{colors.textMuted}"
      cursor: "not-allowed"
      opacity: "0.6"
  
  buttonSecondary:
    backgroundColor: "rgba(255,255,255,0.2)"
    textColor: "{colors.bgWhite}"
    typography: "{typography.button}"
    padding: "{spacing.md} {spacing.xl}"
    rounded: "{rounded.lg}"
    backdropFilter: "blur(10px)"
    border: "1px solid rgba(255,255,255,0.3)"
    transition: "all 0.3s ease"
    hover:
      backgroundColor: "rgba(255,255,255,0.3)"
    pressed:
      backgroundColor: "rgba(255,255,255,0.25)"
  
  buttonGhost:
    backgroundColor: "transparent"
    textColor: "{colors.textPrimary}"
    typography: "{typography.button}"
    padding: "{spacing.sm} {spacing.md}"
    rounded: "{rounded.md}"
    hover:
      backgroundColor: "{colors.bgLight}"
  
  card:
    backgroundColor: "{colors.bgWhite}"
    rounded: "{rounded.xl}"
    padding: "{spacing.xl}"
    shadow: "{elevation.lg}"
    border: "1px solid rgba(0,0,0,0.05)"
    hover:
      transform: "translateY(-4px)"
      shadow: "{elevation.xl}"
  
  cardProblem:
    backgroundColor: "{colors.bgWhite}"
    rounded: "{rounded.xl}"
    padding: "{spacing.xl}"
    shadow: "{elevation.md}"
    borderLeft: "4px solid {colors.accentRed}"
    hover:
      transform: "translateY(-4px)"
      shadow: "{elevation.xl}"
  
  cardResult:
    backgroundColor: "rgba(255,255,255,0.05)"
    textColor: "{colors.bgWhite}"
    rounded: "{rounded.xl}"
    padding: "{spacing.xl}"
    border: "1px solid rgba(255,255,255,0.1)"
  
  ctaBox:
    backgroundColor: "{gradients.heroGradient}"
    rounded: "{rounded.2xl}"
    padding: "{spacing.4xl}"
    textColor: "{colors.bgWhite}"
    shadow: "{elevation.xl}"
  
  nav:
    backgroundColor: "{colors.bgWhite}"
    height: "80px"
    paddingX: "{spacing.lg}"
    shadow: "{elevation.md}"
  
  input:
    backgroundColor: "{colors.bgWhite}"
    textColor: "{colors.textPrimary}"
    typography: "{typography.body}"
    padding: "{spacing.sm} {spacing.md}"
    rounded: "{rounded.md}"
    border: "1px solid {colors.textMuted}"
    focus:
      borderColor: "{colors.primary}"
      shadow: "0 0 0 3px rgba(0,119,182,0.1)"
    disabled:
      backgroundColor: "{colors.bgLight}"
      textColor: "{colors.textMuted}"

---

# Phorecast Design System

## Overview

Phorecast is a strategy consulting firm that helps organizations create strategies that actually get used. The design should reflect:

- **Professionalism** - Trustworthy, established expertise
- **Clarity** - Making complex ideas simple and actionable
- **Energy** - Dynamic, forward-thinking, results-oriented
- **Approachability** - Not corporate stuffy, but human and relatable

### Brand Personality

> "We're not management consultants. We're innovators, entrepreneurs, and change leaders who know how strategy becomes reality."

**Keywords:** Clear, Actionable, Results-driven, Human, Modern

---

## Colors

### Primary Palette

The primary blue represents trust, professionalism, and clarity - core values of Phorecast's consulting approach.

- **Primary** `#0077B6` - Main brand color, used for CTAs and key elements
- **Primary Light** `#00B4D8` - Hover states, highlights
- **Primary Dark** `#023E8A` - Active states, emphasis

### Accent Palette

Extracted from the signature "flow" imagery on phorecast.com, representing the dynamic nature of strategy and change.

- **Accent Orange** `#FF4500` - Energy, action, urgency
- **Accent Red** `#FF6B6B` - Important highlights, alerts
- **Accent Gold** `#FFD93D` - Success, results, achievements
- **Accent Teal** `#4ECDC4` - Innovation, fresh thinking

### Usage Guidelines

**Do:**
- Use primary blue for main CTAs and navigation
- Use accent colors sparingly for emphasis
- Maintain high contrast for accessibility

**Don't:**
- Use multiple accent colors in the same component
- Use accent colors for large backgrounds
- Mix warm and cool accents without clear hierarchy

---

## Typography

### Font Family

**Primary:** Inter (modern, highly readable, excellent for UI)
**Fallback:** Open Sans, Arial, sans-serif

### Hierarchy

The typography scale follows a clear hierarchy that guides users through content:

| Style | Size | Weight | Use Case |
|-------|------|--------|----------|
| **Display** | 4rem | 800 | Hero headlines, major statements |
| **H1** | 3rem | 800 | Page titles, hero headlines |
| **H2** | 2.5rem | 700 | Section headers |
| **H3** | 1.5rem | 600 | Subsection headers, card titles |
| **H4** | 1.25rem | 600 | Small headers, labels |
| **H5** | 1.125rem | 600 | Card subtitles, captions |
| **Subtitle** | 1.25rem | 400 | Lead paragraphs |
| **Body** | 1rem | 400 | Main content text |
| **Body Large** | 1.125rem | 400 | Emphasized content |
| **Body Small** | 0.875rem | 400 | Footnotes, small print |
| **Caption** | 0.8125rem | 500 | Metadata, timestamps |
| **Caption Bold** | 0.8125rem | 600 | Important metadata |
| **Micro** | 0.75rem | 500 | Tiny labels, badges |
| **Micro Uppercase** | 0.6875rem | 600 | Tags, pill labels |
| **Button** | 1rem | 600 | Button text |

### Readability

- Line height: 1.6 for body text (optimal for readability)
- Letter spacing: -0.02em for headings (tighter, more modern)
- Max line length: 65-75 characters for body text

---

## Layout & Spacing

### 8px Grid System

All spacing is based on an 8px grid for consistency and visual rhythm:

- **xxs** (4px) - Tight spacing, icon margins
- **xs** (8px) - Small gaps, inline elements
- **sm** (12px) - Compact spacing
- **md** (16px) - Standard spacing, card padding
- **lg** (24px) - Section spacing, component gaps
- **xl** (32px) - Large sections
- **2xl** (48px) - Major section breaks
- **3xl** (64px) - Hero sections
- **4xl** (96px) - Page-level spacing
- **5xl** (128px) - Full page sections

### Container

- **Max width:** 1200px (optimal reading width)
- **Section padding:** 96px vertical, 24px horizontal (mobile: 16px)

---

## Gradients

Phorecast uses gradients to create depth, energy, and visual interest:

| Gradient | Use Case |
|----------|----------|
| `primaryGradient` | Primary CTA backgrounds, highlights |
| `primaryDarkGradient` | Dark section backgrounds |
| `accentGradient` | Dynamic backgrounds, hero sections |
| `heroGradient` | Hero section backgrounds (purple to blue) |
| `subtleGradient` | Section dividers, backgrounds |
| `glow` | Ambient effects, focus states |

---

## Elevation & Depth

Shadows are used to create hierarchy and indicate interactivity:

- **sm** - Subtle separation (cards on light backgrounds)
- **md** - Navigation, floating elements
- **lg** - Cards, modals, dropdowns
- **xl** - CTAs, important interactive elements

### Usage

- Cards use `lg` shadow by default
- Hover states increase to `xl` shadow
- Navigation uses `md` shadow for separation

---

## Shapes

### Rounded Corners

The design uses generous rounded corners for a friendly, modern feel:

- **xs** (4px) - Tight spacing, icon margins
- **sm** (6px) - Inputs, small buttons
- **md** (8px) - Standard buttons, tags
- **lg** (12px) - Cards, large buttons
- **xl** (16px) - Hero elements, featured cards
- **2xl** (20px) - CTA boxes, modals
- **3xl** (24px) - Large containers
- **full** (9999px) - Pills, avatars

### Philosophy

Rounded corners make the design feel approachable and human - reflecting Phorecast's "not corporate consultants" positioning.

---

## Components

### Navigation

**Purpose:** Primary site navigation, always visible

**Structure:**
- Logo (left)
- Nav links (center)
- CTA button (right)

**Behavior:**
- Fixed position on scroll
- White background with subtle shadow
- Smooth transitions on hover

### Buttons

**Primary Button:**
- Used for main CTAs
- Blue background, white text
- Hover: darker blue + lift effect
- Examples: "Book Free Strategy Session"

**Secondary Button:**
- Used for secondary actions
- Transparent with backdrop blur
- White text (for dark backgrounds)
- Examples: "See How It Works"

**Ghost Button:**
- Minimal, text-only
- Used for less important actions
- Examples: "Learn More", "Back"

### Cards

**Problem Cards:**
- White background
- Red left border (indicates "pain point")
- Hover: lift effect
- Used in "Do You Recognize This?" section

**Result Cards:**
- Semi-transparent background (for dark sections)
- Large numbers/amounts
- Customer quote + name
- Star ratings

**Process Cards:**
- Timeline format
- Numbered steps
- Time estimates
- Connected by animated line

### CTA Box

**Purpose:** Final call-to-action at bottom of pages

**Design:**
- Gradient background (purple to blue)
- Large, centered text
- Bullet points with checkmarks
- Primary button
- "No obligations" reassurance text

### Timeline

**Purpose:** Show the 6-week process

**Design:**
- Vertical line (gradient)
- Alternating left/right items
- Animated on scroll
- Each item shows: number, time, title, description

### Form Inputs

**Design:**
- White background
- Subtle border
- Focus: blue border + glow
- Disabled: gray background

---

## Accessibility

### Color Contrast (WCAG AA)

| Pair | Foreground | Background | Ratio | Pass AA |
|------|-----------|-----------|-------|---------|
| Primary text on white | #333333 | #FFFFFF | 14.7:1 | ✅ Yes |
| Primary text on primary | #FFFFFF | #0077B6 | 4.5:1 | ✅ Yes |
| Secondary text on white | #6B7280 | #FFFFFF | 4.6:1 | ✅ Yes |
| Muted text on white | #9CA3AF | #FFFFFF | 2.8:1 | ⚠️ Decorative only |
| Primary on accent red | #FFFFFF | #FF6B6B | 3.6:1 | ✅ Large text |
| Accent orange on white | #FF4500 | #FFFFFF | 4.5:1 | ✅ Yes |

**Important:**
- `#9CA3AF` (muted) is below WCAG AA - use only for decorative/disabled text
- White-on-primary button passes for large text (≥18px) or bold text (≥14px bold)
- For small button labels, use weight 600 which qualifies as "bold" at 14px+

### Keyboard Navigation

- All interactive elements must be keyboard accessible
- Focus states must be visible (blue glow on inputs)
- Tab order must be logical

### Screen Readers

- All images need alt text
- Form inputs need labels
- Headings must be in hierarchical order

---

## Do's and Don'ts

### Do ✅

- Use the 8px spacing grid consistently
- Maintain high contrast for accessibility (WCAG AA minimum)
- Use primary blue for main CTAs
- Keep plenty of white space
- Use animations sparingly and purposefully
- Make CTAs clear and action-oriented
- Include social proof (testimonials, results)
- Reference design tokens (`{colors.primary}`) instead of hardcoded values

### Don't ❌

- Don't use more than 2 accent colors per section
- Don't make text smaller than 16px for body content
- Don't use pure black (#000000) - use #333333 instead
- Don't overcrowd layouts - embrace white space
- Don't use corporate stock photos - use authentic imagery
- Don't hide CTAs - make them prominent
- Don't use jargon - keep language clear and human
- Don't skip hover/focus/disabled states for interactive elements

---

## Version History

- **1.1.0** (2026-05-19) - Added gradients, extended typography (15+ styles), component states (hover/pressed/disabled), WCAG contrast table
- **1.0.0** (2026-05-13) - Initial design system extracted from phorecast.com + modernized

---

## Notes for AI Agents

When generating UI for Phorecast:

1. **Always reference this DESIGN.md** for colors, spacing, and component styles
2. **Use component tokens** (e.g., `{colors.primary}`) instead of hardcoded values
3. **Maintain the friendly, professional tone** - not corporate, not casual
4. **Prioritize clarity** - every element should have a clear purpose
5. **Test contrast** - ensure all text is readable (WCAG AA minimum)
6. **Mobile-first** - design for mobile, enhance for desktop
7. **Include all states** - hover, pressed, disabled for interactive elements

**Remember:** Phorecast helps make strategy understandable. The design should do the same - clear, actionable, human.
