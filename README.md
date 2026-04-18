# dreytools-admin

Generic admin dashboard template for drey tools.

**Live:** https://admin.dreytools.com
**CF project:** `dreytools-admin`

## What it has

- Left sidebar with nav sections (Workspace / Tools / Settings), active state, badges, user footer
- Top bar with search, notifications, help, avatar
- 4 KPI stat cards with inline SVG sparklines + delta badges (up/down/flat)
- Revenue chart (30 days) with dual-series stacked SVG area chart (Subscriptions + One-time)
- Recent activity feed (6 items with color-coded icons)
- Recent members table with avatars, plan, status pills, LTV (sortable-ready)
- Mobile-responsive (sidebar hides, table scrolls horizontally)
- Warm dark + cyan brand

## Specialize

This is a generic admin dashboard template. Can be forked and specialized into:
- **G3AC ops dashboard** — private, for energy grid ops data
- **ABS Club member dashboard** — community metrics, shipped streaks
- **Viral Editz client dashboard** — video production KPIs per client

Each specialization keeps the layout + components, swaps the data + labels.

## Stack

Pure HTML + CSS + vanilla JS (and inline SVG charts — no chart library). Single file. Zero dependencies.

## Deploy

```bash
wrangler pages deploy . --project-name dreytools-admin --branch main
```
