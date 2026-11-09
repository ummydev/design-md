---
version: alpha
name: "Vinyl"
description: "Cover art first, a hot pink play button and a dark room to listen in. Vinyl lets cover art set the mood: a near-black background, big square artwork, a hot pink play button and Syne for bold, slightly quirky titles. Playback is never more than a tap away, thanks to a mini player that sits above the tab bar on every screen."
colors:
  primary: "#D81B60"
  on-primary: "#FFFFFF"
  secondary: "#2F6FD6"
  tertiary: "#E0A43A"
  neutral: "#5E5B57"
  surface: "#F7F6F4"
  on-surface: "#121212"
typography:
  display-lg:
    fontFamily: "Syne"
    fontSize: 48px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: "Syne"
    fontSize: 32px
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: -0.01em
  headline-md:
    fontFamily: "Syne"
    fontSize: 22px
    fontWeight: 700
    lineHeight: 1.2
  headline-sm:
    fontFamily: "Syne"
    fontSize: 17px
    fontWeight: 700
    lineHeight: 1.3
  body-md:
    fontFamily: "Manrope"
    fontSize: 15px
    fontWeight: 500
    lineHeight: 1.5
  body-sm:
    fontFamily: "Manrope"
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0.02em
rounded:
  sm: 8px
  md: 10px
  lg: 12px
  xl: 16px
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

Vinyl lets cover art set the mood: a near-black background, big square artwork, a hot pink play button and Syne for bold, slightly quirky titles. Playback is never more than a tap away, thanks to a mini player that sits above the tab bar on every screen.

## Colors

- **primary (#D81B60):** Raspberry pink in light mode and hot pink in dark mode, for play, the progress bar, liked tracks and the active tab.
- **on-primary (#FFFFFF)**
- **secondary (#2F6FD6):** Blue, for podcasts, downloads and the second chart series.
- **tertiary (#E0A43A):** Amber, for new releases, live shows and a third series.
- **neutral (#5E5B57):** Warm grey for artist names, durations and episode details.
- **surface (#F7F6F4):** Near-black in dark mode with cards a step lighter; light mode is a warm off-white.
- **on-surface (#121212)**

## Typography

Syne at weight 700 for screen titles and album names (48px display, 32px titles); Manrope at weight 500 and 15px for body and track lists. Times and durations use tabular figures so they don't jump.

## Layout

Phone screens with 16px side padding, a 60px bottom tab bar with four labeled tabs and a persistent mini player directly above it. The now-playing screen is full screen with the artwork at the top.

## Shapes

12px corners on cards, artwork and sheets; round play buttons with 48px hit areas. No shadows; dark surfaces step up in tone instead.

## Components

Square cover-art cards in horizontal shelves, track rows with number, title, artist and duration, a mini player with a progress line, a full now-playing screen with scrubber and queue, and podcast episode cards with play and download.

## Do's and Don'ts

- Do make cover art the biggest element on each screen.
- Do keep the mini player visible everywhere except the now-playing screen.
- Don't use pink for anything that doesn't play, like or record.
- Don't set Syne below 17px; smaller text belongs to Manrope.
