---
version: alpha
name: "Morrow"
description: "Oat paper, espresso ink and one sage accent, so the product photos do the talking. Morrow is an editorial storefront look for a small maker brand: oat paper, espresso ink, one sage accent and a tall serif for headlines. The product photos do the talking, and the interface stays quiet around them: warm plaster behind every photo, hairline borders instead of shadows, and pill buttons in espresso for the one thing to do next."
colors:
  primary: "#30231B"
  on-primary: "#F9F6F1"
  secondary: "#627A56"
  tertiary: "#B79876"
  neutral: "#695E55"
  surface: "#F9F6F1"
  on-surface: "#291F18"
typography:
  display-lg:
    fontFamily: "Instrument Serif"
    fontSize: 84px
    fontWeight: 400
    lineHeight: 0.95
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: "Instrument Serif"
    fontSize: 64px
    fontWeight: 400
    lineHeight: 1
    letterSpacing: -0.01em
  headline-md:
    fontFamily: "Instrument Serif"
    fontSize: 44px
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: "Instrument Serif"
    fontSize: 24px
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: -0.01em
  body-md:
    fontFamily: "Geist"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.6
  body-sm:
    fontFamily: "Geist"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.45
rounded:
  sm: 4px
  md: 6px
  lg: 8px
  xl: 12px
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

Morrow is an editorial storefront look for a small maker brand: oat paper, espresso ink, one sage accent and a tall serif for headlines. The product photos do the talking, and the interface stays quiet around them: warm plaster behind every photo, hairline borders instead of shadows, and pill buttons in espresso for the one thing to do next.

## Colors

- **primary (#30231B):** Espresso, for the main buttons with oat text, the announcement bar, the newsletter band and the one dark tile on a page. In dark mode it turns to oat with espresso text.
- **on-primary (#F9F6F1)**
- **secondary (#627A56):** Sage, the one accent: eyebrow labels, small icons, the bag count and badges. Sage text uses the deep sage accent foreground, on oat or on the pale sage fill of the free-shipping bar.
- **tertiary (#B79876):** Warm clay, a quiet earth tone for charts and small details next to the glazes in the photos.
- **neutral (#695E55):** Warm grey-brown for secondary text, glaze names, footer links and captions; it passes WCAG AA on every surface.
- **surface (#F9F6F1):** Oat paper for the page; photo wells, the order summary and review cards are a warmer plaster that matches the photo backdrops. No shadows: hairline borders separate the rest.
- **on-surface (#291F18)**

## Typography

Instrument Serif for display: an 84px hero with one word in italic, 60 to 64px page titles, 44px section titles and 22 to 24px quotes, with -0.01em tracking. Geist for everything else: 14 to 17px nav and body text, 15px medium product names and prices in tabular figures. Eyebrows are 13px medium, uppercase, with 0.08em tracking, in sage, at most one per section.

## Layout

Pages are 1280px of content on a 1440px desktop. An announcement bar comes first, then a header with the nav on the left, a centered serif wordmark and icons on the right. Products sit in a four-column grid with 20px gutters; sections are spaced generously, about 96px apart, and every page ends in a four-column footer.

## Shapes

6px corners on photos, 10px on bands and cards, and full pills for buttons, chips, quantity steppers and glaze swatches. No shadows and no gradients: separation comes from the warm card color and 1px borders. No glass.

## Components

An announcement bar, a header with a centered wordmark and a bag count in a sage dot, product cards with a square or 4:5 photo, an optional pill badge, name and price on one line, glaze swatches and the star rating, a filter sidebar with counts, quick-filter chips, glaze pills and a quantity stepper on the product page, accordions, a free-shipping progress bar, cart line items and an order summary card.

## Do's and Don'ts

- Do let the photos carry the color; keep the interface oat, espresso and sage.
- Do set headlines in the serif and everything else in Geist.
- Do use espresso for the one main action on a page, as a full pill.
- Don't add shadows, gradients or glass; separate things with the plaster card color and hairlines.
