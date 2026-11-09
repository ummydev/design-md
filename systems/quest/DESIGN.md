---
version: alpha
name: "Quest"
description: "Streaks, XP and chunky buttons that make practice feel like a game. Quest turns practice into a game: a lesson path on the home screen, big streak and XP numbers, royal blue for the next step and gold for rewards. Buttons and cards sit on solid offset shadows so every tap feels physical, and Nunito keeps the tone warm and encouraging."
colors:
  primary: "#2346D8"
  on-primary: "#FFFFFF"
  secondary: "#F5B800"
  tertiary: "#18A957"
  neutral: "#585F78"
  surface: "#FFFFFF"
  on-surface: "#1A1F36"
typography:
  display-lg:
    fontFamily: "Nunito"
    fontSize: 44px
    fontWeight: 800
    lineHeight: 1.05
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: "Nunito"
    fontSize: 30px
    fontWeight: 800
    lineHeight: 1.1
  headline-md:
    fontFamily: "Nunito"
    fontSize: 22px
    fontWeight: 800
    lineHeight: 1.2
  headline-sm:
    fontFamily: "Nunito"
    fontSize: 18px
    fontWeight: 800
    lineHeight: 1.3
  body-md:
    fontFamily: "Nunito"
    fontSize: 17px
    fontWeight: 600
    lineHeight: 1.5
  body-sm:
    fontFamily: "Nunito"
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1.4
rounded:
  sm: 14px
  md: 16px
  lg: 18px
  xl: 22px
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

Quest turns practice into a game: a lesson path on the home screen, big streak and XP numbers, royal blue for the next step and gold for rewards. Buttons and cards sit on solid offset shadows so every tap feels physical, and Nunito keeps the tone warm and encouraging.

## Colors

- **primary (#2346D8):** Royal blue, for the continue button, the current lesson on the path and the active tab.
- **on-primary (#FFFFFF)**
- **secondary (#F5B800):** Gold, for XP, streak flames, coins and rewards.
- **tertiary (#18A957):** Green, for correct answers, completed lessons and a third series.
- **neutral (#585F78):** Blue-grey for hints, locked lessons and secondary labels.
- **surface (#FFFFFF):** White; dark mode is a deep indigo with slightly lighter cards.
- **on-surface (#1A1F36)**

## Typography

Nunito throughout: extra bold 800 for titles and the big streak and XP numbers (up to 44px), weight 600 at 17px for questions, answers and body.

## Layout

Phone screens with 16px side padding and a 64px bottom tab bar with four labeled tabs and a streak counter. Home is a vertical lesson path; lesson screens put a progress bar at the top and the check button at the bottom.

## Shapes

18px corners on cards, buttons and answer tiles, each at least 48px tall. Hard shadows: a solid, unblurred edge offset below each button and card that disappears when it is pressed.

## Components

A winding lesson path with round nodes, answer tiles that turn green or red after checking, a full-width check button, streak and XP counters, a reward screen with confetti and a weekly leaderboard.

## Do's and Don'ts

- Do celebrate every finished lesson with a short reward screen.
- Do keep one big continue or check button at the bottom.
- Don't punish mistakes with harsh red screens; show the right answer kindly.
- Don't show more than one reward or popup at a time.
