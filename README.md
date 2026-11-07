# Smart Warehouse Twin

A live 3D digital twin of a logistics park in Phnom Penh, built at the Institute of Technology of Cambodia (ITC) by Dr. PLACK Sokhit.

**Live site:** https://smart-warehouse-twin.netlify.app

## What it does
- 3D logistics park (dry warehouses, 2–8 °C cold store, cross-dock, 26 dock doors, roads, gate, truck yard) you can rotate, zoom and click
- Real-time mode: follows the clock, updates every few seconds, trucks dock and leave
- Alarms pinned to the exact zone or door: cold-chain temperature, zone nearly full, trucks queuing, camera outage, fire-panel fault
- Five-week replay on a timeline
- Khmer and English, TV mode, phone and tablet layout
- Real temperature data from a CSV/JSON feed (see `sample_temperature_readings.csv`)

The demo runs on clearly labelled sample data.

## Files
- `index.html` – the whole app in one file (three.js from a CDN, the 3D park model embedded and compressed)
- `sample_temperature_readings.csv` – example sensor file you can load in the Data tab
- `netlify.toml` – Netlify settings (no build step)

## Update the site
Edit `index.html`, commit and push to `main`. Netlify publishes the new version automatically.

Trees and other 3D assets from SketchUp 3D Warehouse, if added, are used inside the scene under the 3D Warehouse General Model License and are not offered as separate downloads.
