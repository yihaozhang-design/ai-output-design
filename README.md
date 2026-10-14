# AI Output – Property Inspections

A pixel-perfect HTML implementation of the **AI Output** screen from the [GW Projects for Behance](https://www.figma.com/design/YzVlclcVDjr5mS7mA35Vfg/GW-Projects-for-Behance?node-id=736-76237) Figma design.

## What's included

```
ai-output-design/
├── index.html        ← Single-file implementation (no build step)
└── assets/           ← All icons and images downloaded from Figma
    ├── logo.svg
    ├── timer.svg
    ├── inspection.png
    └── ...
```

## Preview

Open `index.html` directly in any browser — no server, no dependencies.

```bash
open index.html         # macOS
start index.html        # Windows
xdg-open index.html     # Linux
```

## Design

The screen is a **370 px wide mobile chat UI** for a property inspection AI assistant. It covers 5 conversation turns:

| Turn | User prompt | AI response |
|------|-------------|-------------|
| 1 | *(initial load)* | Today's 4 appointments + timeline overview |
| 2 | Pull up next appointment details | Next appointment card (address, time, ETA, Navigate) |
| 3 | Navigate to next appointment | Same card, navigation focused |
| 4 | Pull up all assigned HO claims | Claims list (3 claims with status badges, Schedule Inspection CTA) |
| 5 | Record damages for Claim# 3804-942-522 | Damage recording card (Take Notes / New Video / Voice Note) |

## Stack

- Plain **HTML + CSS** — no framework, no bundler
- Fonts: **Roboto** + **Inter** via Google Fonts
- All assets are **local** — no Figma URLs in the code

## Figma source

[GW Projects for Behance → AI Output (node 736:76237)](https://www.figma.com/design/YzVlclcVDjr5mS7mA35Vfg/GW-Projects-for-Behance?node-id=736-76237)
