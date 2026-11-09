---
version: alpha
name: "Mono"
description: "Plain white pages, Geist type and one cobalt blue, built for docs and dev tools. Mono is a quiet system for developer products: white pages, Geist and Geist Mono, hairline borders and one cobalt blue for links and primary actions. Code blocks, tables and API references are the main event, not an afterthought."
colors:
  primary: "#2450E6"
  on-primary: "#FFFFFF"
  secondary: "#0F9F6E"
  tertiary: "#D97706"
  neutral: "#5D6470"
  surface: "#FFFFFF"
  on-surface: "#0B0C0E"
typography:
  display-lg:
    fontFamily: "Geist"
    fontSize: 60px
    fontWeight: 600
    lineHeight: 1.05
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: "Geist"
    fontSize: 40px
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: -0.02em
  headline-md:
    fontFamily: "Geist"
    fontSize: 28px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: "Geist"
    fontSize: 20px
    fontWeight: 600
    lineHeight: 1.3
  body-md:
    fontFamily: "Geist"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.55
  body-sm:
    fontFamily: "Geist"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.45
rounded:
  sm: 4px
  md: 6px
  lg: 8px
  xl: 12px
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

Mono is a quiet system for developer products: white pages, Geist and Geist Mono, hairline borders and one cobalt blue for links and primary actions. Code blocks, tables and API references are the main event, not an afterthought.

## Colors

- **primary (#2450E6):** Cobalt blue, for links, primary buttons and the active item in the sidebar.
- **on-primary (#FFFFFF)**
- **secondary (#0F9F6E):** Emerald, for success states, added lines in diffs and the second chart series.
- **tertiary (#D97706):** Amber, for warnings, deprecation notes and a third series.
- **neutral (#5D6470):** Cool slate grey for descriptions, line numbers and metadata.
- **surface (#FFFFFF):** Pure white; cards match the page and are set apart by a border. Dark mode is near-black.
- **on-surface (#0B0C0E)**

## Typography

Geist throughout: semibold 600 for headings from a 60px display down to 20px, regular 400 at 16px with 1.55 line height for body. Geist Mono for code, commands, keys and version numbers.

## Layout

Content sits on a 12-column, 1280px grid with 24px gutters and a 4px spacing unit. Docs pages use a left sidebar, a 72-character content column and an on-page table of contents on the right.

## Shapes

8px corners on cards, code blocks, inputs and buttons. Light grey 1px borders separate everything; no shadows.

## Components

Code blocks with a copy button and a file name tab, note and warning callouts, install commands in tabs (npm, pnpm, bun), keyboard shortcut chips and a command-K search.

## Do's and Don'ts

- Do show a working code sample near the top of every page.
- Do set every command, path and flag in Geist Mono.
- Don't use blue for anything that isn't clickable.
- Don't decorate with gradients, illustrations or glows.
