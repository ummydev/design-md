---
version: alpha
name: "Pop"
description: "Thick black outlines, hard shadows and lemon yellow. Loud on purpose. Pop is neo-brutalism with good manners: a cream page, wide Unbounded headlines, black outlines on everything and solid offset shadows that make cards look like stickers. Lemon yellow and coral do the shouting, while the grid and spacing stay disciplined."
colors:
  primary: "#141414"
  on-primary: "#FFE45C"
  secondary: "#FF6B4A"
  tertiary: "#3D7EFF"
  neutral: "#5C5A52"
  surface: "#FFFDF5"
  on-surface: "#141414"
typography:
  display-lg:
    fontFamily: "Unbounded"
    fontSize: 72px
    fontWeight: 600
    lineHeight: 1
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: "Unbounded"
    fontSize: 48px
    fontWeight: 600
    lineHeight: 1.05
    letterSpacing: -0.02em
  headline-md:
    fontFamily: "Unbounded"
    fontSize: 30px
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: "Unbounded"
    fontSize: 20px
    fontWeight: 600
    lineHeight: 1.3
  body-md:
    fontFamily: "Manrope"
    fontSize: 17px
    fontWeight: 500
    lineHeight: 1.55
  body-sm:
    fontFamily: "Manrope"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.45
rounded:
  sm: 10px
  md: 12px
  lg: 14px
  xl: 18px
spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 48px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.lg}"
    padding: "{spacing.md}"
---

## Overview

Pop is neo-brutalism with good manners: a cream page, wide Unbounded headlines, black outlines on everything and solid offset shadows that make cards look like stickers. Lemon yellow and coral do the shouting, while the grid and spacing stay disciplined.

## Colors

- **primary (#141414):** Black with yellow text in light mode and lemon yellow in dark mode, for the main call to action.
- **on-primary (#FFE45C)**
- **secondary (#FF6B4A):** Coral, for stickers, highlight blocks and the second chart series.
- **tertiary (#3D7EFF):** Bright blue, for links inside cards, tags and a third series.
- **neutral (#5C5A52):** Warm grey for supporting copy and captions.
- **surface (#FFFDF5):** Warm off-white with white cards. Whole sections can switch to lemon yellow.
- **on-surface (#141414)**

## Typography

Unbounded at weight 600 for headlines, wide and geometric, up to 72px with -0.03em tracking; Manrope at weight 500 and 17px for body. JetBrains Mono for price tags and code.

## Layout

A 12-column grid up to 1200px with 24px gutters and a 4px spacing unit. Sections alternate between cream and solid color blocks; feature cards sit in a chunky two- or three-column grid.

## Shapes

14px corners and black borders on every card, button and input (cream borders in dark mode). Shadows are hard: a solid block offset down and to the right, with no blur.

## Components

Buttons are outlined blocks with a hard shadow that drops flat when pressed. Cards carry a colored header strip. Badges look like stickers, and pricing tables use heavy rules between plans.

## Do's and Don'ts

- Do give every card, button and input the same black outline.
- Do pick one loud color per section.
- Don't blur the shadows; keep them solid and offset.
- Don't mix in pastel gradients or glassmorphism.
