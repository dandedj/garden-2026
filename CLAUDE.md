# Garden 2026 — Project Notes

## File Structure

This project contains both Markdown source files and HTML view files:

### Markdown (source of truth)
- `garden-preferences.md` — Household, location, garden setup, crop preferences
- `garden-inventory.md` — Seeds, plants, and supplies with specs and pricing
- `garden-timeline.md` — Full month-by-month planting/harvest schedule

### HTML (viewable via GitHub Pages or browser)
- `index.html` — Hub page linking to all other views
- `garden-preferences.html` — HTML version of preferences
- `garden-inventory.html` — HTML version of inventory
- `garden-supplies.html` — Tools, trellises, amendments, and accessories
- `garden-timeline-view.html` — HTML version of timeline with interactive checkboxes
- `garden-calendar.html` — Monthly calendar view with color-coded activity cards and Gantt overview
- `garden-layout.html` — Visual grid layout of both raised beds
- `garden-layout-time-a.html` — Plot A layout over time (warm crops)
- `garden-layout-time-b.html` — Plot B layout over time (cool crops)
- `irrigation-plan.html` — Irrigatia C18Q drip plan for Plot A

All HTML files (except `index.html`, which is the hub) share a consistent navigation bar linking to each other.

## Important: Keeping HTML in Sync

**When any markdown file is updated, the corresponding HTML file(s) must also be updated to reflect the changes, and all changes should be committed and pushed together.**

This includes:
- Changes to `garden-preferences.md` → update `garden-preferences.html`
- Changes to `garden-inventory.md` → update `garden-inventory.html`
- Changes to `garden-timeline.md` → update `garden-timeline-view.html` AND `garden-calendar.html` (both derive from timeline data)
- Changes to plot layouts → update `garden-layout.html`

## Garden Details

- Location: Issaquah, WA (Zone 8b)
- Two raised beds: Plot A (4×19.5 ft, E–W) and Plot B (4×19.5 ft, N–S, sloped)
- Last frost: ~April 15 · First frost: ~October 15
- Kale: only 1–2 plants needed (not a large planting)
