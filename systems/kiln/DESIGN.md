---
version: alpha
name: "Kiln"
description: "Bone paper, charcoal ink and one kiln-orange accent, so a busy week reads at a glance. Kiln is a warm, friendly look for the tools a team plans its week in: bone paper, charcoal ink, one kiln-orange accent and a soft color for each project. It is rounded, bold and calm, so a page full of projects, tasks and dates still reads at a glance. Orange is kept for the main action and for today; everything else that has a color has it because it belongs to a project or says whether something is on track."
colors:
  primary: "#BC4602"
  on-primary: "#FFFFFF"
  secondary: "#5BB0D7"
  tertiary: "#9EC773"
  neutral: "#69625D"
  surface: "#F7F4EF"
  on-surface: "#241E1A"
typography:
  display-lg:
    fontFamily: "Manrope"
    fontSize: 36px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: "Manrope"
    fontSize: 28px
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: -0.03em
  headline-md:
    fontFamily: "Manrope"
    fontSize: 20px
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: "Manrope"
    fontSize: 15px
    fontWeight: 700
    lineHeight: 1.35
    letterSpacing: -0.01em
  body-md:
    fontFamily: "Manrope"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.5
  body-sm:
    fontFamily: "Manrope"
    fontSize: 12px
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

Kiln is a warm, friendly look for the tools a team plans its week in: bone paper, charcoal ink, one kiln-orange accent and a soft color for each project. It is rounded, bold and calm, so a page full of projects, tasks and dates still reads at a glance. Orange is kept for the main action and for today; everything else that has a color has it because it belongs to a project or says whether something is on track.

## Colors

- **primary (#BC4602):** Kiln orange, for main buttons with white text, the today line and the logo. Orange text, such as today's date and count badges, uses the darker accent foreground. A lighter orange with dark text in dark mode.
- **on-primary (#FFFFFF)**
- **secondary (#5BB0D7):** Sky, one of the five project colors (clay, sky, lime, lilac and sand). Each has a soft fill for bars and tiles and a darker ink tone for the text on it.
- **tertiary (#9EC773):** Lime, another project color, used the same way: a soft fill with its own ink tone for text.
- **neutral (#69625D):** Warm grey for labels, dates, task keys and table headers, and warm stone for the sidebar around the content.
- **surface (#F7F4EF):** Bone paper for the content; cards, tables and task cards are a warmer white with a hairline border and no shadow.
- **on-surface (#241E1A)**

## Typography

Manrope throughout: bold 28px page titles with -0.03em tracking, bold 15px card titles, 13 to 13.5px body text and semibold 12px labels in muted grey. Numbers use tabular figures; task and project keys such as HAL-52 are set in Geist Mono.

## Layout

The app sits in a rounded stone frame with a 228px sidebar: workspace, search, navigation with orange count badges, the project list with color dots and the signed-in person. The content is a rounded bone panel inside the frame. Pages open with a title and the main action, then a row of four KPI cards, a board, or a timeline that fills the page.

## Shapes

14px corners: 16px for cards, 12px for buttons and inputs, 6 to 8px for tags; people are full circles, and the frame around the app is 22px. Cards have a hairline border and no shadow; only the active sidebar item and the selected segment get a 1px shadow. No glass and no gradients.

## Components

KPI cards with a small bar or meter, a week view with pill bars per project and a today line, team load bars that turn red over capacity, a projects table with status, progress and team, a kanban board with tinted columns and task cards, and a twelve-week Gantt timeline with phase bars and launch diamonds.

## Do's and Don'ts

- Do give each project one color: a soft fill with its darker ink tone for text.
- Do keep orange for the main action and for today.
- Do use at most one dark charcoal card per screen, for what needs attention.
- Don't add glass, gradients or card shadows; separate things with hairlines and space.
