---
version: alpha
name: "Noir"
description: "Black, bone white and a huge serif. The work is the only color. Noir strips color away so the work can speak: black pages, bone white type, a giant Instrument Serif for names and project titles, and square image frames. It is at its best in dark mode; the bone-white light mode suits print-like case studies."
colors:
  primary: "#0E0E0E"
  on-primary: "#F4F2EE"
  secondary: "#6E6A63"
  tertiary: "#A39D93"
  neutral: "#5F5C57"
  surface: "#F4F2EE"
  on-surface: "#0E0E0E"
typography:
  display-lg:
    fontFamily: "Instrument Serif"
    fontSize: 120px
    fontWeight: 400
    lineHeight: 0.9
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: "Instrument Serif"
    fontSize: 72px
    fontWeight: 400
    lineHeight: 0.95
    letterSpacing: -0.02em
  headline-md:
    fontFamily: "Instrument Serif"
    fontSize: 40px
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: "Instrument Serif"
    fontSize: 22px
    fontWeight: 400
    lineHeight: 1.3
  body-md:
    fontFamily: "Manrope"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.6
  body-sm:
    fontFamily: "Manrope"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0.08em
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

Noir strips color away so the work can speak: black pages, bone white type, a giant Instrument Serif for names and project titles, and square image frames. It is at its best in dark mode; the bone-white light mode suits print-like case studies.

## Colors

- **primary (#0E0E0E):** Black in light mode and bone white in dark mode, for buttons, links and the active project.
- **on-primary (#F4F2EE)**
- **secondary (#6E6A63):** Warm dark grey, for secondary text blocks and the second data series.
- **tertiary (#A39D93):** Stone grey, for image placeholders, index numbers and a third series.
- **neutral (#5F5C57):** Warm mid grey for captions, credits and years.
- **surface (#F4F2EE):** Bone white in light mode with pure white cards; dark mode is almost pure black.
- **on-surface (#0E0E0E)**

## Typography

Instrument Serif at weight 400 for headlines, up to 120px with 0.9 line height and tight tracking; Manrope at 16px with 1.6 line height for body. Small 12px labels use 0.08em tracking.

## Layout

A 12-column grid up to 1440px with narrow 16px gutters and an 8px spacing unit. Project images run large and can break the grid; text stays in narrow 56-character columns.

## Shapes

Square corners (0px radius) on images and buttons. 1px hairlines in warm grey; no shadows.

## Components

An index list of projects with year and role, full-width image sequences, text-link buttons with an arrow, and a minimal header with name, work and contact.

## Do's and Don'ts

- Do open each page with one giant serif title.
- Do number projects and list the year, client and role.
- Don't add an accent color; the images supply the color.
- Don't put images in rounded or shadowed frames.
