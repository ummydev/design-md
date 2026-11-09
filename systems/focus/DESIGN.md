---
version: alpha
name: "Focus"
description: "A white page, one blue and nothing else between you and the task. Focus removes everything that isn't the task: a white screen, Instrument Sans, thin dividers instead of cards and one bright blue for the add button and today. Icon-only tabs keep the bottom bar quiet, and a floating add button makes capture instant."
colors:
  primary: "#2F5BEA"
  on-primary: "#FFFFFF"
  secondary: "#E8743B"
  tertiary: "#19A974"
  neutral: "#5B616E"
  surface: "#FFFFFF"
  on-surface: "#16181D"
typography:
  display-lg:
    fontFamily: "Instrument Sans"
    fontSize: 40px
    fontWeight: 600
    lineHeight: 1.05
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: "Instrument Sans"
    fontSize: 30px
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: -0.01em
  headline-md:
    fontFamily: "Instrument Sans"
    fontSize: 22px
    fontWeight: 600
    lineHeight: 1.2
  headline-sm:
    fontFamily: "Instrument Sans"
    fontSize: 18px
    fontWeight: 600
    lineHeight: 1.3
  body-md:
    fontFamily: "Instrument Sans"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
  body-sm:
    fontFamily: "Instrument Sans"
    fontSize: 13px
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

Focus removes everything that isn't the task: a white screen, Instrument Sans, thin dividers instead of cards and one bright blue for the add button and today. Icon-only tabs keep the bottom bar quiet, and a floating add button makes capture instant.

## Colors

- **primary (#2F5BEA):** Bright blue, for the floating add button, checked boxes and today's date.
- **on-primary (#FFFFFF)**
- **secondary (#E8743B):** Orange, for due-soon dates and high-priority flags.
- **tertiary (#19A974):** Green, for completed tasks, streaks and a third project color.
- **neutral (#5B616E):** Cool grey for due dates, notes and finished tasks.
- **surface (#FFFFFF):** Pure white; cards match the page and are split by thin dividers. Dark mode is near-black with a hint of blue.
- **on-surface (#16181D)**

## Typography

Instrument Sans throughout: semibold 600 for titles (40px for the big date header, 30px for list titles), regular 400 at 16px for task rows. Dates and counts use 13px.

## Layout

Phone screens with 16px side padding and a 60px bottom tab bar with four icon-only tabs; the active tab shows its label. A floating add button sits bottom right, above the tab bar.

## Shapes

12px corners on cards, sheets and inputs; round checkboxes with 48px tap areas. 1px light grey dividers and no shadows; the add button stands out by color alone.

## Components

Task rows with a round checkbox, title and due date, a quick-add sheet that understands dates like tomorrow 9am, project lists with colored dots, and swipe actions to complete or reschedule.

## Do's and Don'ts

- Do let a task be added with one tap and one line.
- Do fade finished tasks to grey instead of removing them at once.
- Don't wrap every task in a card or shadow.
- Don't give a project more than one color.
