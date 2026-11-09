---
version: alpha
name: "Chalk"
description: "Bright, rounded and encouraging, like a good classroom. Chalk makes learning feel approachable: warm cream pages, a confident blue for actions, cheerful amber and green for progress, and rounded Nunito set large enough for young and tired eyes alike. Lessons are broken into small, clearly labeled steps."
colors:
  primary: "#1F5FD6"
  on-primary: "#FFFFFF"
  secondary: "#F59E0B"
  tertiary: "#16A34A"
  neutral: "#5A6070"
  surface: "#FFF8EC"
  on-surface: "#1C2333"
typography:
  display-lg:
    fontFamily: "Nunito"
    fontSize: 64px
    fontWeight: 800
    lineHeight: 1.05
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: "Nunito"
    fontSize: 44px
    fontWeight: 800
    lineHeight: 1.1
    letterSpacing: -0.015em
  headline-md:
    fontFamily: "Nunito"
    fontSize: 30px
    fontWeight: 800
    lineHeight: 1.2
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: "Nunito"
    fontSize: 21px
    fontWeight: 800
    lineHeight: 1.3
  body-md:
    fontFamily: "Nunito"
    fontSize: 18px
    fontWeight: 500
    lineHeight: 1.6
  body-sm:
    fontFamily: "Nunito"
    fontSize: 15px
    fontWeight: 500
    lineHeight: 1.45
rounded:
  sm: 12px
  md: 14px
  lg: 16px
  xl: 20px
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

Chalk makes learning feel approachable: warm cream pages, a confident blue for actions, cheerful amber and green for progress, and rounded Nunito set large enough for young and tired eyes alike. Lessons are broken into small, clearly labeled steps.

## Colors

- **primary (#1F5FD6):** Bright blue, for enroll buttons, links and the current lesson.
- **on-primary (#FFFFFF)**
- **secondary (#F59E0B):** Amber, for highlights, tips and the second chart series.
- **tertiary (#16A34A):** Green, for completed lessons, correct answers and a third series.
- **neutral (#5A6070):** Slate grey for lesson details, durations and hints.
- **surface (#FFF8EC):** Warm cream, like the page of a notebook; cards are white. Dark mode is a deep ink blue.
- **on-surface (#1C2333)**

## Typography

Nunito throughout: extra bold 800 for headings from a 64px display down to 21px, body text in weight 500 at a generous 18px, line height 1.6. Small text stays at 15px so it is still easy to read.

## Layout

A 1200px, 12-column grid with 24px gutters and spacing in multiples of 4px. Course pages pair a syllabus sidebar with a 66-character lesson column; landing pages use friendly three-up feature cards.

## Shapes

16px corners on cards, buttons and inputs. 1px borders in warm sand; soft, low shadows on cards and quizzes.

## Components

Course cards with level, length and progress, a lesson outline with check marks, quiz options as large tappable cards, tip callouts in pale yellow, and badges for finished modules.

## Do's and Don'ts

- Do show progress on every course and lesson.
- Do keep body text at 18px, even in dense lessons.
- Don't mark wrong answers in red without a short explanation.
- Don't stack more than three colors in one card.
