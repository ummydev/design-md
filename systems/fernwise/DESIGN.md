---
version: alpha
name: "Fernwise"
description: "Sage paper, deep forest ink and money that feels calm. Fernwise makes money feel calm instead of urgent: a soft sage background, frosted panels, and one dark forest-green card per screen that carries the number that matters most. Mint marks good news, honey shows progress toward a goal, and red only appears when a budget is over."
colors:
  primary: "#113C2C"
  on-primary: "#F6F4EB"
  secondary: "#4B7E63"
  tertiary: "#9ACCAA"
  neutral: "#57685E"
  surface: "#ECF2ED"
  on-surface: "#11281F"
typography:
  display-lg:
    fontFamily: "Geist"
    fontSize: 44px
    fontWeight: 500
    lineHeight: 1
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: "Geist"
    fontSize: 28px
    fontWeight: 500
    lineHeight: 1.15
    letterSpacing: -0.02em
  headline-md:
    fontFamily: "Geist"
    fontSize: 20px
    fontWeight: 500
    lineHeight: 1.25
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: "Geist"
    fontSize: 17px
    fontWeight: 500
    lineHeight: 1.3
  body-md:
    fontFamily: "Geist"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.5
  body-sm:
    fontFamily: "Geist"
    fontSize: 13px
    fontWeight: 400
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

Fernwise makes money feel calm instead of urgent: a soft sage background, frosted panels, and one dark forest-green card per screen that carries the number that matters most. Mint marks good news, honey shows progress toward a goal, and red only appears when a budget is over.

## Colors

- **primary (#113C2C):** Deep forest green, for the balance card, the active tab and main buttons. Pale mint in dark mode.
- **on-primary (#F6F4EB)**
- **secondary (#4B7E63):** Sage green, for income amounts, chart lines and the second budget category.
- **tertiary (#9ACCAA):** Mint, for positive badges, avatars, completed days and lighter chart bars.
- **neutral (#57685E):** Grey-green for notes, dates and labels.
- **surface (#ECF2ED):** Sage paper; panels are frosted cream on top of it.
- **on-surface (#11281F)**

## Typography

Geist throughout: medium 500 headings at 28px with tight -0.02em tracking, 15px body, and muted labels at 12.5 to 13px. Money is set light with tabular figures and -0.03em tracking, the dollar sign and cents at 45% size.

## Layout

Phone screens with 20px side padding: a two-option pill switch at the top left, the avatar at the top right, and a floating pill tab bar with five tabs at the bottom. On the web, a 232px sidebar, a row of four KPI panels and a two-column grid of glass panels.

## Shapes

20 to 28px corners on cards and panels; full pills for tabs, filters, search and the tab bar. Panels are frosted glass with a white inner highlight and a soft forest-tinted shadow.

## Components

A dark balance card with quick actions, a weekly spending bar chart, transaction rows with a 40px round icon and right-aligned amount, budget bars, savings goals, a no-spend challenge tracker, a send-money keypad and card controls with switches.

## Do's and Don'ts

- Do give each screen one dark forest card for its key number, and keep everything else glass.
- Do use honey for progress toward a target only, at most once per screen.
- Don't use red for ordinary spending; keep it for budgets that are over.
- Don't set money in bold; use the light weight with tabular figures.
