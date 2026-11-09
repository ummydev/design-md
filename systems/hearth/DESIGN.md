---
version: alpha
name: "Hearth"
description: "Warm amber light on a dark, quiet home screen. Hearth feels like a lamp switched on in a dark room: a warm charcoal background, amber for anything that is on, and large rounded device tiles you can read from across the room. Rooms sit in horizontal tabs, and temperatures are big, steady numbers."
colors:
  primary: "#B85C00"
  on-primary: "#FFFFFF"
  secondary: "#2F7FA8"
  tertiary: "#4E9A5F"
  neutral: "#5F5A53"
  surface: "#F4F2EF"
  on-surface: "#1A1816"
typography:
  display-lg:
    fontFamily: "Outfit"
    fontSize: 56px
    fontWeight: 600
    lineHeight: 1
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: "Outfit"
    fontSize: 30px
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: -0.01em
  headline-md:
    fontFamily: "Outfit"
    fontSize: 22px
    fontWeight: 600
    lineHeight: 1.2
  headline-sm:
    fontFamily: "Outfit"
    fontSize: 17px
    fontWeight: 600
    lineHeight: 1.3
  body-md:
    fontFamily: "Outfit"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
  body-sm:
    fontFamily: "Outfit"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0.01em
rounded:
  sm: 18px
  md: 20px
  lg: 22px
  xl: 26px
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

Hearth feels like a lamp switched on in a dark room: a warm charcoal background, amber for anything that is on, and large rounded device tiles you can read from across the room. Rooms sit in horizontal tabs, and temperatures are big, steady numbers.

## Colors

- **primary (#B85C00):** Burnt amber in light mode and bright amber in dark mode, for devices that are on, sliders and the active tab.
- **on-primary (#FFFFFF)**
- **secondary (#2F7FA8):** Cool blue, for cooling, humidity and the second chart series.
- **tertiary (#4E9A5F):** Leaf green, for energy savings, solar and a third series.
- **neutral (#5F5A53):** Warm grey for device status, room names and units.
- **surface (#F4F2EF):** Warm charcoal in dark mode with tiles a step lighter; light mode is a warm stone grey with white tiles.
- **on-surface (#1A1816)**

## Typography

Outfit throughout: semibold 600 for titles and the big temperature readout (up to 56px, with tabular figures so it doesn't jump), regular 400 at 16px for labels and body.

## Layout

Phone screens with 20px side padding and a 64px bottom tab bar with four labeled tabs. Rooms are horizontal tabs under the title; devices fill a two-column grid of tiles.

## Shapes

22px corners on device tiles and sheets; round dials and toggles with touch areas of 48px or more. No shadows or glow effects; a device that is on simply fills with amber.

## Components

Device tiles with icon, name, state and a tap-to-toggle area, a large circular thermostat dial, brightness sliders, scene buttons such as Good night, and a weekly energy chart.

## Do's and Don'ts

- Do make on and off obvious from across the room.
- Do toggle a device on tap and open its controls on long press.
- Don't use amber for anything that isn't on or active.
- Don't hide a device's main controls behind menus.
