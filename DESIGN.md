# AI News Radar — Design System

## Color Strategy
Restrained — tinted neutrals + one accent. The accent (#126a73) is a deep teal that evokes radar screens and technical precision.

### Light Theme
- Background: warm off-white (#f6f6f2) — not sterile white
- Surface: pure white for content cards
- Ink: near-black with warm undertone (#171717)
- Muted: warm gray (#66645f)
- Accent: deep teal (#126a73) — used sparingly for active states, links, key data
- Accent warm: burnt orange (#b55231) — for warnings and builder sources
- Good/OK: forest green (#1f7a4d)
- Warn: amber (#9a6700)
- Bad: crimson (#b42318)

### Dark Mode
Not implemented yet. Future consideration.

## Typography
System font stack with CJK support. No custom web fonts — speed and reliability over personality.

Hierarchy:
- H1: 36px / 1.08 line-height — page title only
- H2: 20px — section headers
- H3: 16px — group headers
- Body: 14-16px / 1.42 — content
- Caption: 12-13px — metadata, labels

## Spacing
- Base unit: 8px
- Page padding: 26px horizontal, 18px on mobile
- Card padding: 13-16px
- Section gaps: 16px
- Item gaps: 8-12px

## Components
- News card: minimal — meta row + title link, no container border
- Stats: 4-column grid with bordered cells
- Coverage strip: 6-column grid showing source health
- Pills: rounded filter chips
- Mode switch: segmented control

## Motion
Minimal. No animations on data load. Focus mode switch transitions only.
