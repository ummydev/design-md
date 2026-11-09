---
version: alpha
name: "Chatter"
description: "Round bubbles, a friendly teal and conversations front and center. Chatter keeps people and messages at the center: a white screen, teal bubbles for what you send, pale grey bubbles for replies, round avatars and generous 22px corners. Unread badges and typing states are clear without turning the screen into a slot machine."
colors:
  primary: "#0F7F81"
  on-primary: "#FFFFFF"
  secondary: "#F08A4B"
  tertiary: "#5B7BE0"
  neutral: "#56676A"
  surface: "#FFFFFF"
  on-surface: "#14201F"
typography:
  display-lg:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 40px
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 30px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: -0.01em
  headline-md:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 22px
    fontWeight: 700
    lineHeight: 1.2
  headline-sm:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 18px
    fontWeight: 700
    lineHeight: 1.3
  body-md:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
  body-sm:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.4
rounded:
  sm: 18px
  md: 20px
  lg: 22px
  xl: 26px
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

Chatter keeps people and messages at the center: a white screen, teal bubbles for what you send, pale grey bubbles for replies, round avatars and generous 22px corners. Unread badges and typing states are clear without turning the screen into a slot machine.

## Colors

- **primary (#0F7F81):** Deep teal, for your own message bubbles, the send button and unread badges. Bright aqua in dark mode.
- **on-primary (#FFFFFF)**
- **secondary (#F08A4B):** Apricot, for reactions, mentions and the second chart series.
- **tertiary (#5B7BE0):** Periwinkle, for links, shared files and a third series.
- **neutral (#56676A):** Grey-teal for timestamps, read receipts and message previews in the chat list.
- **surface (#FFFFFF):** White; cards and incoming bubbles are a pale grey-teal.
- **on-surface (#14201F)**

## Typography

Plus Jakarta Sans throughout: bold 700 for screen titles (30px) and names, regular 400 at 16px with 1.5 line height for messages. Timestamps and previews use 13px.

## Layout

Phone screens with 16px side padding and a 60px bottom tab bar with four labeled tabs and unread badges. The chat list opens into a full-screen thread with the composer pinned to the bottom.

## Shapes

22px corners on bubbles, cards and the composer, with a tighter corner on the tail side; circular avatars; every tap target is at least 48px. No shadows; pale 1px borders where needed.

## Components

Chat list rows with avatar, name, preview, time and unread count, message bubbles grouped by sender, a composer with attach and send, reaction pills and a typing indicator.

## Do's and Don'ts

- Do group consecutive messages from the same person.
- Do keep the composer visible above the keyboard.
- Don't use teal outside your own messages and key actions.
- Don't put shadows or gradients on bubbles.
