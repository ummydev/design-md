---
version: alpha
name: "Care"
description: "One clear task per screen, for patients who just want to get it done. Care is written for patients who may be tired, worried or reading on a small screen: a cool, pale background, calm cerulean for the next step and large, plain labels. Each screen handles one task, like choosing a time or confirming a visit, before moving on."
colors:
  primary: "#0A6C8A"
  on-primary: "#FFFFFF"
  secondary: "#2EA37A"
  tertiary: "#E0A43A"
  neutral: "#4F6573"
  surface: "#F7FAFC"
  on-surface: "#0F2533"
typography:
  display-lg:
    fontFamily: "Source Sans 3"
    fontSize: 40px
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: "Source Sans 3"
    fontSize: 30px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: -0.01em
  headline-md:
    fontFamily: "Source Sans 3"
    fontSize: 22px
    fontWeight: 700
    lineHeight: 1.2
  headline-sm:
    fontFamily: "Source Sans 3"
    fontSize: 18px
    fontWeight: 700
    lineHeight: 1.3
  body-md:
    fontFamily: "Source Sans 3"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
  body-sm:
    fontFamily: "Source Sans 3"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.4
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

Care is written for patients who may be tired, worried or reading on a small screen: a cool, pale background, calm cerulean for the next step and large, plain labels. Each screen handles one task, like choosing a time or confirming a visit, before moving on.

## Colors

- **primary (#0A6C8A):** Calm cerulean, for book and confirm buttons, selected time slots and the active tab.
- **on-primary (#FFFFFF)**
- **secondary (#2EA37A):** Jade green, for confirmed visits, normal results and the second chart series.
- **tertiary (#E0A43A):** Amber, for reminders, pending results and a third series.
- **neutral (#4F6573):** Slate blue-grey for helper text, addresses and times.
- **surface (#F7FAFC):** Pale, cool white so cards and time slots stand out.
- **on-surface (#0F2533)**

## Typography

Source Sans 3 throughout: bold 700 for screen titles (30px) and section heads, regular 400 at 16px with 1.5 line height for body. Source Code Pro for booking references and prescription codes.

## Layout

Screens keep 20px of side padding above a four-tab bottom bar, 64px tall. One task per screen, with a step indicator at the top and the main button fixed at the bottom.

## Shapes

14px corners on cards, time slots and sheets; pill primary buttons; nothing tappable is smaller than 48px. 1px pale blue-grey borders and soft, low shadows on cards.

## Components

Doctor cards with photo, specialty, rating and next free slot, a day strip with time-slot chips, appointment cards with directions and a video call button, medication reminders to tick off, and lab results with a normal-range bar.

## Do's and Don'ts

- Do confirm every booking with a summary screen.
- Do pair every status color with an icon and a word.
- Don't put two primary buttons on one screen.
- Don't use medical jargon where a plain word works.
