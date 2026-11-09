---
version: alpha
name: "Voyage"
description: "Full-bleed photos, ocean blue and a serif that feels like a postcard. Voyage sells the destination first: full-bleed photo headers, a postcard serif for place names, ocean blue for booking and sunset orange for deals. Below the photos it turns practical, with clear dates, prices and itineraries on warm sand-white."
colors:
  primary: "#0B5D7A"
  on-primary: "#FFFFFF"
  secondary: "#E2884A"
  tertiary: "#3E8E6A"
  neutral: "#5A6A70"
  surface: "#FAF7F2"
  on-surface: "#0F2A33"
typography:
  display-lg:
    fontFamily: "DM Serif Display"
    fontSize: 44px
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: "DM Serif Display"
    fontSize: 32px
    fontWeight: 400
    lineHeight: 1.1
  headline-md:
    fontFamily: "DM Serif Display"
    fontSize: 24px
    fontWeight: 400
    lineHeight: 1.2
  headline-sm:
    fontFamily: "DM Serif Display"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.3
  body-md:
    fontFamily: "Manrope"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.5
  body-sm:
    fontFamily: "Manrope"
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.4
rounded:
  sm: 16px
  md: 18px
  lg: 20px
  xl: 24px
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

Voyage sells the destination first: full-bleed photo headers, a postcard serif for place names, ocean blue for booking and sunset orange for deals. Below the photos it turns practical, with clear dates, prices and itineraries on warm sand-white.

## Colors

- **primary (#0B5D7A):** Deep ocean blue, for search, book buttons and selected dates. Sky blue in dark mode.
- **on-primary (#FFFFFF)**
- **secondary (#E2884A):** Sunset orange, for deals, price drops and the second chart series.
- **tertiary (#3E8E6A):** Palm green, for free cancellation, eco stays and a third series.
- **neutral (#5A6A70):** Slate grey for dates, distances and fine print.
- **surface (#FAF7F2):** Warm sand-white; white cards, with a soft shadow where they overlap photos.
- **on-surface (#0F2A33)**

## Typography

DM Serif Display at weight 400 for place names and screen titles (44px on photo headers, 32px for titles); Manrope at weight 500 and 16px for body, prices and details.

## Layout

Phone screens with 20px side padding and a 4-item bottom tab bar 64px tall. Destination and hotel screens open with a full-bleed photo header; booking details follow in stacked cards above a sticky price and book bar.

## Shapes

20px corners on cards, photos and sheets; pill-shaped search bar and date chips; 48px minimum touch targets. Soft, low shadows on cards that overlap photos.

## Components

A pill search bar for where, when and who, destination cards with a large photo and serif name, a date range picker, an itinerary timeline and a boarding pass card.

## Do's and Don'ts

- Do open destination screens with a full-bleed photo.
- Do show the total price, taxes included, before the book button.
- Don't set paragraphs in the serif; keep it for names and titles.
- Don't put text on busy photos without a dark scrim behind it.
