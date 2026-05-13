# AI News Radar — Design System

## Design Philosophy
Dark editorial theme — Bloomberg Terminal density meets The Verge editorial courage. Designed for an AI practitioner scanning signals at midnight.

## Color Strategy
OKLCH-tinted neutrals toward amber brand hue (chroma ~0.008). No pure black or white.

### Dark Theme (active)
- Background: deep navy-black (#0f1117)
- Surface: #181b25
- Surface hover: #1e2230
- Ink: warm off-white (#e8e6e0)
- Muted: cool gray (#7a7d85)
- Line: #2a2d37
- Accent: amber (#e8a230) — used for active states, links, key data
- Good: bright green (#4ade80)
- Warn: bright yellow (#facc15)
- Bad: bright red (#f87171)

## Typography
Three-font system:
- Display: DM Sans (700, 800) + Noto Sans SC — headings
- Body: system-ui + Noto Sans SC — content
- Mono: JetBrains Mono (400, 500) + SF Mono — data, time, labels

Perfect fourth scale (1.333):
- H1: 38px / 1.05 line-height — page title
- H2: 18px — section headers
- H3: 15px — group headers
- Body: 15px / 1.55 — content
- Caption: 12-13px — metadata
- Micro: 11px — tags, labels

## Layout
- Max width: 1080px, centered
- 2-column grid: feed (1fr) + sidebar (300px)
- Responsive: 860px single column, sidebar above feed
- Page padding: 40px 28px, 24px 16px on mobile

## Components
- News card: title-first, meta below — no container border, 1px separator
- Stats: 4 data points — big mono number (amber) + small uppercase label
- Coverage strip: small chips with colored dots
- Pills: rounded filter chips, amber active state
- Mode switch: segmented control, amber active
- Site group: 2px amber left border header
- Source health: metric cards + issue lists

## Motion
Minimal. No animations on data load. Focus/hover transitions only (0.15s).
