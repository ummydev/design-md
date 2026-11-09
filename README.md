# DESIGN.md templates for AI coding agents

Free, complete design systems for websites and mobile apps, written as [DESIGN.md](https://codexdesign.io/guides/design-md) files that Codex, Claude Code, Cursor and other AI agents can follow. Each one has colors for light and dark mode, Google Fonts, a type scale, corner radius, spacing, and rules for using them, plus a shadcn theme.

**Live previews of every system:** [codexdesign.io/design-systems](https://codexdesign.io/design-systems)

## Use one in your project

Paste this into Codex or Claude Code, with the system you want:

```text
This project uses the Paper design system. Its spec is at https://codexdesign.io/design-systems/paper.md. Save it as DESIGN.md in the project root and follow it for every screen from now on.
```

Or copy `systems/<name>/DESIGN.md` into your project root yourself. Codex reads `AGENTS.md` automatically but not `DESIGN.md`, so add a line to `AGENTS.md` that points to it.

To install the colors, fonts and radius as a shadcn theme:

```bash
npx shadcn@latest add https://codexdesign.io/r/paper.json
```

## Website and dashboard systems

| System | For | Look | File |
| --- | --- | --- | --- |
| [Paper](https://codexdesign.io/design-systems/paper) | Editorial | Calm, editorial and readable, like a well-set book page. | [DESIGN.md](systems/paper/DESIGN.md) |
| [Swiss](https://codexdesign.io/design-systems/swiss) | Minimal Grid | Black, white and one signal red on a strict grid. | [DESIGN.md](systems/swiss/DESIGN.md) |
| [Ledger](https://codexdesign.io/design-systems/ledger) | Dark SaaS Dashboard | A dense, dark interface for numbers, with a terminal-amber accent. | [DESIGN.md](systems/ledger/DESIGN.md) |
| [Mono](https://codexdesign.io/design-systems/mono) | Developer Docs | Plain white pages, Geist type and one cobalt blue, built for docs and dev tools. | [DESIGN.md](systems/mono/DESIGN.md) |
| [Atelier](https://codexdesign.io/design-systems/atelier) | Luxury Fashion | Ivory, ink and a refined serif, like a fashion house lookbook. | [DESIGN.md](systems/atelier/DESIGN.md) |
| [Noir](https://codexdesign.io/design-systems/noir) | Dark Portfolio | Black, bone white and a huge serif. The work is the only color. | [DESIGN.md](systems/noir/DESIGN.md) |
| [Harbor](https://codexdesign.io/design-systems/harbor) | Enterprise B2B | Navy, white space and steady structure for serious B2B products. | [DESIGN.md](systems/harbor/DESIGN.md) |
| [Nordic](https://codexdesign.io/design-systems/nordic) | Calm SaaS | Muted blues, soft greys and quiet confidence for productivity tools. | [DESIGN.md](systems/nordic/DESIGN.md) |
| [Clinic](https://codexdesign.io/design-systems/clinic) | Healthcare | Calm teal, clear type and plain language for health websites. | [DESIGN.md](systems/clinic/DESIGN.md) |
| [Terra](https://codexdesign.io/design-systems/terra) | Earthy Eco | Moss, linen and clay for brands that work close to the land. | [DESIGN.md](systems/terra/DESIGN.md) |
| [Chalk](https://codexdesign.io/design-systems/chalk) | Friendly Education | Bright, rounded and encouraging, like a good classroom. | [DESIGN.md](systems/chalk/DESIGN.md) |
| [Pop](https://codexdesign.io/design-systems/pop) | Neo-Brutalist | Thick black outlines, hard shadows and lemon yellow. Loud on purpose. | [DESIGN.md](systems/pop/DESIGN.md) |

## Mobile app systems

App systems add the rules phone screens need: touch targets, a bottom tab bar, and screen padding.

| System | For | Look | File |
| --- | --- | --- | --- |
| [Stride](https://codexdesign.io/design-systems/stride) | Fitness App | Big condensed numbers and an energetic orange for movement apps. | [DESIGN.md](systems/stride/DESIGN.md) |
| [Pantry](https://codexdesign.io/design-systems/pantry) | Food Ordering App | Warm, friendly and appetizing, for food and ordering apps. | [DESIGN.md](systems/pantry/DESIGN.md) |
| [Calm](https://codexdesign.io/design-systems/calm) | Wellness App | Soft sage, a gentle serif and room to breathe. | [DESIGN.md](systems/calm/DESIGN.md) |
| [Wallet](https://codexdesign.io/design-systems/wallet) | Finance App | Clear balances, calm green and numbers you can trust. | [DESIGN.md](systems/wallet/DESIGN.md) |
| [Focus](https://codexdesign.io/design-systems/focus) | Task Manager App | A white page, one blue and nothing else between you and the task. | [DESIGN.md](systems/focus/DESIGN.md) |
| [Chatter](https://codexdesign.io/design-systems/chatter) | Messaging App | Round bubbles, a friendly teal and conversations front and center. | [DESIGN.md](systems/chatter/DESIGN.md) |
| [Voyage](https://codexdesign.io/design-systems/voyage) | Travel App | Full-bleed photos, ocean blue and a serif that feels like a postcard. | [DESIGN.md](systems/voyage/DESIGN.md) |
| [Boutique](https://codexdesign.io/design-systems/boutique) | Fashion Shopping App | Edge-to-edge photos, a Bodoni serif and black on white, like a shop window. | [DESIGN.md](systems/boutique/DESIGN.md) |
| [Quest](https://codexdesign.io/design-systems/quest) | Gamified Learning App | Streaks, XP and chunky buttons that make practice feel like a game. | [DESIGN.md](systems/quest/DESIGN.md) |
| [Care](https://codexdesign.io/design-systems/care) | Healthcare App | One clear task per screen, for patients who just want to get it done. | [DESIGN.md](systems/care/DESIGN.md) |
| [Vinyl](https://codexdesign.io/design-systems/vinyl) | Music and Podcast App | Cover art first, a hot pink play button and a dark room to listen in. | [DESIGN.md](systems/vinyl/DESIGN.md) |
| [Hearth](https://codexdesign.io/design-systems/hearth) | Smart Home App | Warm amber light on a dark, quiet home screen. | [DESIGN.md](systems/hearth/DESIGN.md) |

## What's in each folder

- `DESIGN.md`: the design system in the DESIGN.md format, with tokens in YAML front matter and sections for overview, colors, typography, layout, shapes, components, and do's and don'ts.
- `shadcn-theme.json`: a shadcn registry item with the CSS variables for light and dark mode, fonts and radius.

Every text color passes WCAG contrast on its background. The systems avoid patterns that make AI-made interfaces look the same, such as purple gradients and glassmorphism.

## More

- [DESIGN.md examples](https://codexdesign.io/guides/design-md-examples) and [what DESIGN.md is](https://codexdesign.io/guides/design-md)
- [DESIGN.md generator](https://codexdesign.io/tools/design-md-generator), to make one from your own colors and fonts
- [Codex Design](https://codexdesign.io), a plugin that adds a visual design canvas to Codex, so you can compare design directions side by side

## License

MIT. Use these design systems in personal and commercial projects.
