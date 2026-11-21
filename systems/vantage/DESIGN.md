---
version: alpha
name: "Vantage"
description: "Graphite night, one signal-lime accent and numbers that line up. Vantage is a dark analytics look for people who watch numbers all day: graphite surfaces, one signal-lime accent, cyan as the second series, and monospaced figures that line up in every table. It is dark first, and the admin dashboard template ships in dark only; the light theme here keeps the same graphite and lime, with lime moving onto graphite buttons so it stays readable on white."
colors:
  primary: "#16191D"
  on-primary: "#BEF050"
  secondary: "#0C7385"
  tertiary: "#6F74C6"
  neutral: "#5D636B"
  surface: "#F5F6F7"
  on-surface: "#121418"
typography:
  display-lg:
    fontFamily: "Geist"
    fontSize: 34px
    fontWeight: 600
    lineHeight: 1.05
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: "Geist"
    fontSize: 20px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: -0.02em
  headline-md:
    fontFamily: "Geist"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: "Geist"
    fontSize: 15px
    fontWeight: 600
    lineHeight: 1.35
  body-md:
    fontFamily: "Geist"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.5
  body-sm:
    fontFamily: "Geist"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.4
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

Vantage is a dark analytics look for people who watch numbers all day: graphite surfaces, one signal-lime accent, cyan as the second series, and monospaced figures that line up in every table. It is dark first, and the admin dashboard template ships in dark only; the light theme here keeps the same graphite and lime, with lime moving onto graphite buttons so it stays readable on white.

## Colors

- **primary (#16191D):** Signal lime with dark text in dark mode, for main buttons, the first chart series, the active nav icon, checked boxes and funnel bars. In light mode, graphite buttons with lime labels.
- **on-primary (#BEF050)**
- **secondary (#0C7385):** Cyan, the second chart series, country bars, bounce bars and the Fulfilled status.
- **tertiary (#6F74C6):** Soft violet, a third category; amber and grey follow for a fourth and fifth.
- **neutral (#5D636B):** Cool grey for labels, dates, paths and table headers.
- **surface (#F5F6F7):** Graphite night, with tiles one step lighter and the sidebar one step darker; every surface keeps a hairline border instead of a shadow.
- **on-surface (#121418)**

## Typography

Geist for text: a 20px semibold page title in the top bar, 15px semibold tile titles, 13 to 13.5px body and muted 12 to 12.5px labels. Every number, ID and path is set in Geist Mono with tabular figures and -0.03em tracking; KPI values are 34px.

## Layout

A 220px sidebar with a store switcher, navigation with a pending-orders badge, an Admin section for users and roles, settings and the signed-in user; a 72px top bar with the page title, a ⌘K search, the date range, notifications and the page's main action. Pages fill a 1440×1000 frame with 20px gaps: a row of four KPI tiles, then charts, tables and side panels.

## Shapes

16px tiles with a 1px border at 8% white and no shadow; 9 to 10px controls; a 20px app frame. Charts have no axis lines, only a faint horizontal grid, a lime area with a fading fill and a dashed cyan line for the second series. Only the floating bulk-action bar gets a shadow.

## Components

KPI tiles with a delta and a sparkline, a traffic area chart with a live-visitors chip, channel and country bars, a top pages table with bounce bars, status tabs with counts, an order detail panel, a conversion funnel, a cohort heatmap, a staff table with role badges and 2FA, a floating bulk-action bar and a permission matrix.

## Do's and Don'ts

- Do keep lime for the one thing that matters: the main action, the first series, what's selected.
- Do set every number, ID and path in Geist Mono with tabular figures.
- Do use green and coral for deltas only, never for decoration.
- Don't add shadows, gradients or glow to tiles; separate them with hairlines.
