---
version: alpha
name: "Paper"
description: "Calm, editorial and readable, like a well-set book page. Paper reads like a well-set book page: paper white, near-black ink, a sturdy serif for headlines and a single deep ink-blue accent. It relies on type, rules and whitespace instead of shadows, gradients or decoration."
colors:
  primary: "#23408E"
  on-primary: "#FFFFFF"
  secondary: "#2F6B57"
  tertiary: "#A9741C"
  neutral: "#5C5F66"
  surface: "#F6F6F3"
  on-surface: "#1A1C20"
typography:
  display-lg:
    fontFamily: "Source Serif 4"
    fontSize: 64px
    fontWeight: 600
    lineHeight: 1.05
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: "Source Serif 4"
    fontSize: 44px
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: -0.015em
  headline-md:
    fontFamily: "Source Serif 4"
    fontSize: 30px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: "Source Serif 4"
    fontSize: 22px
    fontWeight: 600
    lineHeight: 1.3
  body-md:
    fontFamily: "Public Sans"
    fontSize: 17px
    fontWeight: 400
    lineHeight: 1.6
  body-sm:
    fontFamily: "Public Sans"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
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

Paper reads like a well-set book page: paper white, near-black ink, a sturdy serif for headlines and a single deep ink-blue accent. It relies on type, rules and whitespace instead of shadows, gradients or decoration.

## Colors

- **primary (#23408E):** Deep ink blue, for the main action and links. Use it sparingly, about once per screen.
- **on-primary (#FFFFFF)**
- **secondary (#2F6B57):** Bottle green, for secondary charts and tags.
- **tertiary (#A9741C):** Ochre, for highlights and a third data series.
- **neutral (#5C5F66):** Cool grey for captions, metadata and helper text.
- **surface (#F6F6F3):** Paper white with a hint of grey. Cards are pure white.
- **on-surface (#1A1C20)**

## Typography

Source Serif 4 for headlines at weight 600 with slightly tight tracking; Public Sans for body and UI at 17px with 1.6 line height. Keep text columns near 68 characters.

## Layout

A 12-column grid up to 1200px with 24px gutters. Generous vertical rhythm: sections are separated by space and thin rules, not by background blocks.

## Shapes

Small 4px corners. Borders are 1px in a warm grey. No shadows.

## Components

Buttons are solid ink blue or an ink outline. Cards are flat with a hairline border. Pull quotes use the serif at a large size.

## Do's and Don'ts

- Do let one serif headline carry each section.
- Do use thin rules to separate content.
- Don't add gradients, glassmorphism or drop shadows.
- Don't use more than one accent color on a screen.
