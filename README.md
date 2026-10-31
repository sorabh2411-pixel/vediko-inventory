# Vediko Inventory

A single-page inventory dashboard built from the Vediko Origins Google Sheet (demo data).
Plain HTML, CSS and JavaScript. No build step, no dependencies.

## Features
- Dashboard: KPIs, inward vs dispatched chart, dispatch by channel, reorder priorities
- Finished products: search and filter by category and status, days of cover
- Boxes, jars and raw material stock with Low / Out / Check-entry status
- Add entry: record Inward, Outward, Return or Damage and see stock update instantly

## Run locally
Open `index.html` in a browser.

## Live demo
Enable GitHub Pages (Settings > Pages > Deploy from branch > main / root).

## Roadmap
- Backend (FastAPI or Node.js) with PostgreSQL
- Import the full movement logs and BOM search
- Login and per-user audit trail

## Note
Entries are kept in the browser tab only and reset on refresh.
