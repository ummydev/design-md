---
version: alpha
name: "Atelier"
description: "Ivory, ink and a refined serif, like a fashion house lookbook. Atelier borrows from fashion house lookbooks: warm ivory pages, black ink, a high-contrast Cormorant headline and photography that runs large. Color is almost absent; bronze is kept for focus states and fine details, so the product carries the page."
colors:
  primary: "#161412"
  on-primary: "#F7F5F2"
  secondary: "#161412"
  tertiary: "#B79E84"
  neutral: "#6B635B"
  surface: "#F7F5F2"
  on-surface: "#161412"
typography:
  display-lg:
    fontFamily: "Cormorant Garamond"
    fontSize: 96px
    fontWeight: 500
    lineHeight: 0.95
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: "Cormorant Garamond"
    fontSize: 60px
    fontWeight: 500
    lineHeight: 1
    letterSpacing: -0.015em
  headline-md:
    fontFamily: "Cormorant Garamond"
    fontSize: 36px
    fontWeight: 500
    lineHeight: 1.1
  headline-sm:
    fontFamily: "Cormorant Garamond"
    fontSize: 22px
    fontWeight: 500
    lineHeight: 1.3
    letterSpacing: 0.02em
  body-md:
    fontFamily: "Jost"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: 0.01em
  body-sm:
    fontFamily: "Jost"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0.12em
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

Atelier borrows from fashion house lookbooks: warm ivory pages, black ink, a high-contrast Cormorant headline and photography that runs large. Color is almost absent; bronze is kept for focus states and fine details, so the product carries the page.

## Colors

- **primary (#161412):** Warm ink black, for buttons, links and the wordmark. In dark mode it flips to ivory.
- **on-primary (#F7F5F2)**
- **secondary (#161412):** Ink black as a solid band behind campaign images, and the second chart series next to bronze.
- **tertiary (#B79E84):** Camel, for soft fills, image placeholders and a third series.
- **neutral (#6B635B):** Taupe grey for prices, captions and small uppercase labels.
- **surface (#F7F5F2):** Warm ivory; cards and product tiles are pure white.
- **on-surface (#161412)**

## Typography

Cormorant Garamond at weight 500 for headlines, from a 96px display with 0.95 line height down to 22px; Jost at 16px with 1.65 line height for body. Small labels are 12px with 0.12em tracking, set in uppercase.

## Layout

A 12-column grid up to 1440px with 24px gutters and an 8px spacing unit. Images run wide or full-bleed; text blocks stay narrow, about 60 characters, with plenty of air around them.

## Shapes

Square corners (0px radius) on images, buttons and inputs. Hairline 1px borders in pale greige; no shadows.

## Components

Buttons are black rectangles or thin outlined boxes with uppercase labels. Product tiles are just an image, a serif name and a small price. The header is a centered wordmark with sparse text links.

## Do's and Don'ts

- Do let photography take up most of the page.
- Do set labels and navigation in small uppercase with wide tracking.
- Don't add bright colors; bronze is as loud as it gets.
- Don't crowd products with badges, ratings or sale banners.
