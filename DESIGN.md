---
name: Phorecast Design System
version: 1.0.0
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
  h1:
    fontFamily: "Inter"
    fontSize: "3rem"
    fontWeight: "800"
    lineHeight: "1.2"
  h2:
    fontFamily: "Inter"
    fontSize: "2.5rem"
    fontWeight: "700"
    lineHeight: "1.3"
  h3:
    fontFamily: "Inter"
    fontSize: "1.5rem"
    fontWeight: "600"
    lineHeight: "1.4"
  h4:
    fontFamily: "Inter"
    fontSize: "1.25rem"
    fontWeight: "600"
    lineHeight: "1.5"
  body:
    fontFamily: "Inter"
    fontSize: "1rem"
    fontWeight: "400"
    lineHeight: "1.6"
  large:
    fontFamily: "Inter"
    fontSize: "1.25rem"
    fontWeight: "400"
    lineHeight: "1.8"

spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  "2xl": "48px"
  "3xl": "64px"
  "4xl": "96px"

rounded:
  none: "0px"
  sm: "4px"
  md: "8px"
  lg: "12px"
  xl: "16px"
  "2xl": "20px"
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

components:
  buttonPrimary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.bgWhite}"
    padding: "{spacing.md}"
    rounded: "{rounded.lg}"
  buttonSecondary:
    backgroundColor: "rgba(255,255,255,0.2)"
    textColor: "{colors.bgWhite}"
    padding: "{spacing.md}"
    rounded: "{rounded.lg}"

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
**Fallback:** Open Sans (current site font), Arial, sans-serif

### Hierarchy

The typography scale follows a clear hierarchy that guides users through content:

1. **H1** - Page titles, hero headlines (3rem, 800 weight)
2. **H2** - Section headers (2.5rem, 700 weight)
3. **H3** - Subsection headers, card titles (1.5rem, 600 weight)
4. **H4** - Small headers, labels (1.25rem, 600 weight)
5. **Body** - Main content text (1rem, 400 weight)
6. **Large** - Lead paragraphs, emphasis (1.25rem, 400 weight)

### Readability

- Line height: 1.6 for body text (optimal for readability)
- Letter spacing: -0.02em for headings (tighter, more modern)
- Max line length: 65-75 characters for body text

---

## Layout & Spacing

### 8px Grid System

All spacing is based on an 8px grid for consistency and visual rhythm:

- **xs** (4px) - Tight spacing, icon margins
- **sm** (8px) - Small gaps, inline elements
- **md** (16px) - Standard spacing, card padding
- **lg** (24px) - Section spacing, component gaps
- **xl** (32px) - Large sections
- **2xl** (48px) - Major section breaks
- **3xl** (64px) - Hero sections
- **4xl** (96px) - Page-level spacing

### Container

- **Max width:** 1200px (optimal reading width)
- **Section padding:** 96px vertical, 24px horizontal (mobile: 16px)

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

- **sm** (4px) - Inputs, small buttons
- **md** (8px) - Standard buttons, tags
- **lg** (12px) - Cards, large buttons
- **xl** (16px) - Hero elements, featured cards
- **2xl** (20px) - CTA boxes, modals
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

### Don't ❌

- Don't use more than 2 accent colors per section
- Don't make text smaller than 16px
- Don't use pure black (#000000) - use #333333 instead
- Don't overcrowd layouts - embrace white space
- Don't use corporate stock photos - use authentic imagery
- Don't hide CTAs - make them prominent
- Don't use jargon - keep language clear and human

---

## Accessibility

### Color Contrast

All text must meet WCAG AA standards:
- Normal text: 4.5:1 contrast ratio
- Large text: 3:1 contrast ratio

### Keyboard Navigation

- All interactive elements must be keyboard accessible
- Focus states must be visible
- Tab order must be logical

### Screen Readers

- All images need alt text
- Form inputs need labels
- Headings must be in hierarchical order

---

## Version History

- **1.0.0** (2026-05-13) - Initial design system extracted from phorecast.com + modernized

---

## Notes for AI Agents

When generating UI for Phorecast:

1. **Always reference this DESIGN.md** for colors, spacing, and component styles
2. **Use component tokens** (e.g., `{colors.primary}`) instead of hardcoded values
3. **Maintain the friendly, professional tone** - not corporate, not casual
4. **Prioritize clarity** - every element should have a clear purpose
5. **Test contrast** - ensure all text is readable
6. **Mobile-first** - design for mobile, enhance for desktop

**Remember:** Phorecast helps make strategy understandable. The design should do the same - clear, actionable, human.
