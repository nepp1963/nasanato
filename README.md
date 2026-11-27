# NasaNaTo

**NasaNaTo** is a lightweight, offline-capable OpenStreetMap field mapper and street contributor tool designed for on-the-ground surveying, POI pinning, road/street attribute tagging, and multi-format export (`.osc`, `.geojson`, `.csv`, and `.gpx`).

Note: The name "NasaNato" is a shortened version of the Filipino question or interrogative phrase, "Nasaan na ito?" or "Where is it?" in English.

## Features
- **Fullscreen Field Map & Reticle:** Centered precision crosshair with coordinate readout, quick zoom controls, and multi-tier basemap switching (`Map`, `Sat`, `Topo`, `Gray`) plus tile reload.
- **Pin Shop & POI Presets:** Philippine-focused POI presets, address auto-fill, payment/hours chips, custom OSM tags, duplicate proximity checks, and local-only reference photo storage in IndexedDB.
- **Road & Street Tagging:** Tag road classes, surfaces, lanes, one-way streets, and street names directly from the current center.
- **Field Surveying Toolkit:** 10-second GNSS waypoint averaging, GPX breadcrumb track recording, 2x crosshair loupe, and visible tile caching.
- **Multi-Format Export & JOSM Support:** Export queued field changes as OSM Change XML (`.osc`), GeoJSON (`.geojson`), CSV (`.csv`), or GPX (`.gpx`), or send directly to JOSM Remote Control (`127.0.0.1:8111`).

## Local Development (WSL)
```bash
cd ~/projects/nasanato
python3 -m http.server 8080 --bind 0.0.0.0
```
Open `http://localhost:8080` in your browser.

## Licensing & Attribution
- **Application Code:** Licensed under the [MIT License](LICENSE).
- **Map Data & Compliance:** Map data © OpenStreetMap contributors under the **ODbL 1.0**. Always contribute direct field observations and never copy data from proprietary maps.

Created by VelocityVibe Systems • Live App: https://nepp1963.github.io/nasanato/
