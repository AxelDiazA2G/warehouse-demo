# Warehouse Control Room Demo

> Illustrative front-end simulation. All operational activity, KPIs, and inventory identifiers are synthetic; this project does not connect to a live WMS, ERP, or employer data.

A dark-mode warehouse control-room interface that visualizes a top-down facility layout, simulated equipment movement, operational activity, and live KPI cards in a single browser page.

## What it demonstrates

- Operations-oriented KPI presentation for receipts, outbound shipments, scrap events, active vehicles, and throughput
- A map-style warehouse canvas with aisles, docks, forklifts, workers, trucks, and a scrap bay
- Browser-side event simulation with a scrolling activity log
- Responsive layout behavior for desktop and narrower screens

## Run locally

No build step is required. From the repository root, serve the files with any static server:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Scope

This is a visual and interaction prototype for operational-dashboard concepts. It is intentionally self-contained and does not represent live facility conditions, production data, or an integrated warehouse system.
