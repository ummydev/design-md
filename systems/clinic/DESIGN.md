---
version: alpha
name: "Clinic"
description: "Calm teal, clear type and plain language for health websites. Clinic is built for trust: a pale mint-white page, deep teal for actions, a highly legible humanist sans and clear, roomy forms. Every page answers the patient's next question, such as where, when and how much, before it tries to sell anything."
colors:
  primary: "#0B6E69"
  on-primary: "#FFFFFF"
  secondary: "#3B82C4"
  tertiary: "#E0A43A"
  neutral: "#4E6466"
  surface: "#F8FBFB"
  on-surface: "#10282B"
typography:
  display-lg:
    fontFamily: "Source Sans 3"
    fontSize: 60px
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: "Source Sans 3"
    fontSize: 40px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: -0.02em
  headline-md:
    fontFamily: "Source Sans 3"
    fontSize: 28px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: "Source Sans 3"
    fontSize: 20px
    fontWeight: 700
    lineHeight: 1.3
  body-md:
    fontFamily: "Source Sans 3"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.55
  body-sm:
    fontFamily: "Source Sans 3"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.45
rounded:
  sm: 6px
  md: 8px
  lg: 10px
  xl: 14px
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

Clinic is built for trust: a pale mint-white page, deep teal for actions, a highly legible humanist sans and clear, roomy forms. Every page answers the patient's next question, such as where, when and how much, before it tries to sell anything.

## Colors

- **primary (#0B6E69):** Deep teal, for booking buttons, links and the active step.
- **on-primary (#FFFFFF)**
- **secondary (#3B82C4):** Clear blue, for information callouts and the second chart series.
- **tertiary (#E0A43A):** Warm amber, for reminders, pending states and a third series.
- **neutral (#4E6466):** Slate grey with a hint of teal for helper text and form hints.
- **surface (#F8FBFB):** Very pale mint-white; white cards lift off it with a soft shadow.
- **on-surface (#10282B)**

## Typography

Source Sans 3 throughout: bold 700 for headings from a 60px display down to 20px, body copy in regular 400 at 16px, line height 1.55. Source Code Pro for reference numbers and codes. Keep lines near 70 characters.

## Layout

Pages max out at 1200px on a 12-column grid, with 24px gutters and a 4px spacing unit. Service pages lead with a short summary, then opening hours and location, with a booking card kept in view on desktop.

## Shapes

10px corners on cards, inputs and buttons. 1px borders in a pale grey-teal; soft, low shadows lift cards and the booking panel.

## Components

A booking card with date and time slots, doctor profile cards with photo and specialties, form fields with visible labels and hints, and FAQ accordions.

## Do's and Don'ts

- Do write buttons as plain verbs a patient would use.
- Do keep every form label visible above its input.
- Don't use red for anything but errors and urgent warnings.
- Don't rely on color alone to show status.
