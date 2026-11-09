---
version: alpha
name: "Swiss"
description: "Black, white and one signal red on a strict grid. Swiss follows the International Typographic Style: big grotesque type, a strict grid, square corners and lots of white. Red is the only color and appears in a few precise places."
colors:
  primary: "#D70015"
  on-primary: "#FFFFFF"
  secondary: "#0A0A0A"
  tertiary: "#7A7A7A"
  neutral: "#595959"
  surface: "#FFFFFF"
  on-surface: "#0A0A0A"
typography:
  display-lg:
    fontFamily: "Archivo"
    fontSize: 88px
    fontWeight: 700
    lineHeight: 0.95
    letterSpacing: -0.035em
  headline-lg:
    fontFamily: "Archivo"
    fontSize: 56px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: -0.025em
  headline-md:
    fontFamily: "Archivo"
    fontSize: 32px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: "Archivo"
    fontSize: 20px
    fontWeight: 700
    lineHeight: 1.25
  body-md:
    fontFamily: "Archivo"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
  body-sm:
    fontFamily: "Archivo"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0.01em
rounded:
  sm: 0px
  md: 0px
  lg: 0px
  xl: 4px
spacing:
  xs: 8px
  sm: 16px
  md: 32px
  lg: 48px
  xl: 96px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.lg}"
    padding: "{spacing.md}"
---

## Overview

Swiss follows the International Typographic Style: big grotesque type, a strict grid, square corners and lots of white. Red is the only color and appears in a few precise places.

## Colors

- **primary (#D70015):** Signal red, for the primary action and key highlights only.
- **on-primary (#FFFFFF)**
- **secondary (#0A0A0A):** Black, used as a solid block for contrast sections.
- **tertiary (#7A7A7A):** Mid grey for secondary data.
- **neutral (#595959):** Neutral grey for captions and labels.
- **surface (#FFFFFF):** Pure white. Dark mode is pure black.
- **on-surface (#0A0A0A)**

## Typography

Archivo throughout: bold at very large sizes with tight tracking for headlines, regular at 16px for body. Small labels can be uppercase with wide tracking.

## Layout

A strict 12-column grid up to 1440px with 16px gutters and an 8px spacing unit. Align everything to the grid, and leave columns empty on purpose.

## Shapes

Square corners everywhere (0px radius). Hairline 1px borders; no shadows.

## Components

Buttons are solid red or black rectangles. Navigation is plain text. Tables and lists use horizontal rules only.

## Do's and Don'ts

- Do make the headline the biggest thing on the page.
- Do leave empty columns in the grid.
- Don't round corners or add shadows.
- Don't use red for decoration.
