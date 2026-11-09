---
version: alpha
name: "Boutique"
description: "Edge-to-edge photos, a Bodoni serif and black on white, like a shop window. Boutique works like a shop window on a phone: product photos run edge to edge, Bodoni Moda gives names and stories a fashion-magazine voice, and the interface steps back into black, white and warm neutrals. Prices stay quiet, in the body weight rather than bold."
colors:
  primary: "#111111"
  on-primary: "#FFFFFF"
  secondary: "#B79E84"
  tertiary: "#7A6555"
  neutral: "#615C57"
  surface: "#FFFFFF"
  on-surface: "#111111"
typography:
  display-lg:
    fontFamily: "Bodoni Moda"
    fontSize: 48px
    fontWeight: 500
    lineHeight: 1
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: "Bodoni Moda"
    fontSize: 32px
    fontWeight: 500
    lineHeight: 1.05
  headline-md:
    fontFamily: "Bodoni Moda"
    fontSize: 24px
    fontWeight: 500
    lineHeight: 1.15
  headline-sm:
    fontFamily: "Bodoni Moda"
    fontSize: 17px
    fontWeight: 500
    lineHeight: 1.3
    letterSpacing: 0.04em
  body-md:
    fontFamily: "Jost"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0.01em
  body-sm:
    fontFamily: "Jost"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0.1em
rounded:
  sm: 0px
  md: 2px
  lg: 4px
  xl: 8px
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

Boutique works like a shop window on a phone: product photos run edge to edge, Bodoni Moda gives names and stories a fashion-magazine voice, and the interface steps back into black, white and warm neutrals. Prices stay quiet, in the body weight rather than bold.

## Colors

- **primary (#111111):** Black, for add-to-bag, checkout and the active tab. Warm off-white in dark mode.
- **on-primary (#FFFFFF)**
- **secondary (#B79E84):** Camel, for editorial tags, active filters and the second chart series.
- **tertiary (#7A6555):** Cocoa brown, for collection labels and a third series.
- **neutral (#615C57):** Warm grey for prices, sizes and product details.
- **surface (#FFFFFF):** White; product cards sit on a warm bone tone so packshots look studio-lit.
- **on-surface (#111111)**

## Typography

Bodoni Moda at weight 500 for titles and editorial headlines (48px display, 32px titles); Jost at 15px for body with slight tracking. Small 12px labels are uppercase with 0.1em tracking; prices stay in the regular body weight.

## Layout

Phone screens with 16px side padding and a 60px bottom tab bar with five icon-only tabs and a bag badge. Product photos run edge to edge; product lists use a two-column grid with tight gutters.

## Shapes

Nearly square: 4px corners on buttons, inputs and sheets, and crisp-edged photos. 1px warm grey borders; no shadows; tap areas stay 48px even around tiny icons.

## Components

A two-column product grid with image, brand, name and price, a full-screen product page with a size selector and sticky add-to-bag bar, editorial story cards and a minimal bag and checkout flow.

## Do's and Don'ts

- Do give product photos the full width of the screen.
- Do set brand names and labels in small uppercase with wide tracking.
- Don't make prices bold or colored, except sale prices.
- Don't cover the grid with sale badges and stickers.
