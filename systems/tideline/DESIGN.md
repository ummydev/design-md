---
version: alpha
name: "Tideline"
description: "Cool paper, navy ink and one cobalt accent, for people who live in tables. Tideline is a quiet, focused look for screens people work in all day: cool paper, navy ink, one cobalt accent, hairline borders and very little decoration. Color is kept for meaning, such as how hot a lead is, which stage a deal is in, or a step that's overdue, so it stands out when it appears."
colors:
  primary: "#245FD4"
  on-primary: "#FCFCFC"
  secondary: "#61A3E6"
  tertiary: "#B1D2F4"
  neutral: "#656C78"
  surface: "#F5F7F9"
  on-surface: "#131B29"
typography:
  display-lg:
    fontFamily: "Geist"
    fontSize: 36px
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: "Geist"
    fontSize: 24px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: -0.02em
  headline-md:
    fontFamily: "Geist"
    fontSize: 18px
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

Tideline is a quiet, focused look for screens people work in all day: cool paper, navy ink, one cobalt accent, hairline borders and very little decoration. Color is kept for meaning, such as how hot a lead is, which stage a deal is in, or a step that's overdue, so it stands out when it appears.

## Colors

- **primary (#245FD4):** Cobalt, for main buttons, the active tab underline, checked boxes and progress bars. A lighter cobalt in dark mode.
- **on-primary (#FCFCFC)**
- **secondary (#61A3E6):** Light blue, the middle stages of a pipeline chart.
- **tertiary (#B1D2F4):** Pale blue, the earliest stage of a pipeline chart.
- **neutral (#656C78):** Slate grey for labels, emails, dates and table headers.
- **surface (#F5F7F9):** Cool off-white paper; panels, tables and cards are white with a hairline border.
- **on-surface (#131B29)**

## Typography

Geist throughout: semibold 24px page titles with -0.02em tracking, 13px body and table text, and muted 12 to 12.5px labels. Numbers use tabular figures so columns line up; IDs, record numbers and shortcuts are set in Geist Mono.

## Layout

A 232px sidebar with search, navigation with counts, saved views and a quota card; a 56px top bar with breadcrumbs, team avatars and the page's main action. Pages open with a title, a strip of four KPI cells and tabs with counts, then a table, a board or three columns.

## Shapes

10px corners, 12px for panels and 8px for buttons and inputs; people are full circles. Panels are white with a 1px hairline and a 1 to 2px shadow; only floating things, like the bulk-action bar, get a real shadow. No gradients and no glass.

## Components

A KPI strip with 7-point sparklines, tabs with count badges, filters as small bordered chips, a lead table with heat dots and score bars, a dark floating bar for bulk actions, a pipeline board with stage totals and win probability, and a record page with an activity timeline.

## Do's and Don'ts

- Do keep color for meaning: heat, stage, overdue and won.
- Do set numbers in tabular figures, and IDs in Geist Mono.
- Do use at most one dark navy panel per screen.
- Don't add gradients, glass or big shadows; use hairlines to separate things.
