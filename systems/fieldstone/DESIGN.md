---
version: alpha
name: "Fieldstone"
description: "Limestone white, deep pine ink and one brass accent, so the houses fill the frame. Fieldstone is a confident, photo-first look for a local real estate agency: limestone white, deep pine ink, one brass accent and a big grotesk for headlines. Houses fill the frame and the interface stays out of their way: full-bleed photos with dark scrims under any text on them, prices set large in the display face, and a deep pine pill for the one thing to do next."
colors:
  primary: "#152C22"
  on-primary: "#F9F8F5"
  secondary: "#4F7D69"
  tertiary: "#CFA761"
  neutral: "#57605B"
  surface: "#FAF9F6"
  on-surface: "#121E18"
typography:
  display-lg:
    fontFamily: "Bricolage Grotesque"
    fontSize: 104px
    fontWeight: 600
    lineHeight: 0.92
    letterSpacing: -0.035em
  headline-lg:
    fontFamily: "Bricolage Grotesque"
    fontSize: 60px
    fontWeight: 600
    lineHeight: 0.95
    letterSpacing: -0.035em
  headline-md:
    fontFamily: "Bricolage Grotesque"
    fontSize: 44px
    fontWeight: 600
    lineHeight: 1
    letterSpacing: -0.035em
  headline-sm:
    fontFamily: "Bricolage Grotesque"
    fontSize: 32px
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: -0.035em
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

Fieldstone is a confident, photo-first look for a local real estate agency: limestone white, deep pine ink, one brass accent and a big grotesk for headlines. Houses fill the frame and the interface stays out of their way: full-bleed photos with dark scrims under any text on them, prices set large in the display face, and a deep pine pill for the one thing to do next.

## Colors

- **primary (#152C22):** Deep pine, for the main buttons with limestone text, the footer, the saved-search tile and the selected map pin and day. In dark mode it turns to limestone with pine text.
- **on-primary (#F9F8F5)**
- **secondary (#4F7D69):** Brass, the one accent: stars, Price cut badges and small icons on pine, never as text on white. Brass-colored text and icons use the darker accent foreground, on the pale brass of New badges, on limestone or on the soft green-grey panels.
- **tertiary (#CFA761):** A mid pine green and pale sage for charts, such as the stacked bar of a monthly cost estimate next to brass.
- **neutral (#57605B):** Grey-green for secondary text, addresses, specs and captions; 5.6:1 or better on every surface, so it passes WCAG AA.
- **surface (#FAF9F6):** Limestone white for the page and plain white for cards: fact strips, the booking card, reviews and map controls. A soft green-grey for feature chips, the valuation band and the agent card.
- **on-surface (#121E18)**

## Typography

Bricolage Grotesque, semibold, with -0.035em tracking, for display: a 104px hero, page titles of 56 to 88px, section titles of 44 to 52px and prices of 24 to 44px. Geist for everything else: 15px medium nav, 15 to 18px body text and 13 to 14px labels. Prices, counts and specs use tabular figures.

## Layout

Pages are 1312px of content on a 1440px desktop. The home page opens with a full-bleed photo and the header laid over it; other pages have a plain header with a hairline. Listings sit in two or three columns with 24 to 28px gutters, the listings page puts a map beside them, sections are about 96 to 112px apart, and every page ends in a deep pine footer.

## Shapes

Photo corners from 14px on cards to 24px on the agent portrait, 16 to 20px on panels, and full pills for buttons, filters, chips and status badges. One soft shadow, only on things that float over photos: the hero search bar and map pins. Dark scrims under any text on a photo. No glass.

## Components

A header that sits over the hero photo, a three-field search bar, listing cards with a 4:3 photo, status pill and save heart, the price in display type, address, area, agent and beds, baths and square feet, neighbourhood tiles with counts, filter pills, an illustrated map with price pins, a five-photo mosaic, a fact strip, feature chips, a monthly cost estimate with a stacked bar, a booking card with day and time choices, an agent stat strip and review cards.

## Do's and Don'ts

- Do let the photos fill the frame, with a dark scrim under any text on them.
- Do set headlines and prices in Bricolage Grotesque and everything else in Geist.
- Do use deep pine for the one main action on a page, as a full pill.
- Don't set brass text on white; and keep the one soft shadow for things that float over photos.
