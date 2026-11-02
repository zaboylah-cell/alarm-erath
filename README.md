# ALARM ERATH 🌍🚨

A responsive earthquake activity dashboard powered by the public USGS GeoJSON feed.

## Features
- Global earthquake events from the USGS past-24-hours feed; refreshes about once per minute.
- Interactive map with magnitude-sized markers and event detail links.
- Summary cards for total events, strongest event, magnitude 4.5+ events, and an approximate Pakistan-region count.
- Configurable magnitude threshold, optional browser notifications, and sound alerts.
- No API key or account required.

## Run locally
Open `index.html` in a modern browser with an internet connection. The app loads data, map tiles, and Leaflet from public services.

## Publish with GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select **main** and **/(root)**, then Save.
4. When publishing completes, visit https://zaboylah-cell.github.io/alarm-erath/.

## Data and safety
Data source: [USGS Earthquake Hazards Program](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php). Map tiles: [OpenStreetMap](https://www.openstreetmap.org/copyright).

**ALARM ERATH is an informational monitor, not an official earthquake early-warning system, prediction tool, or life-safety device.** USGS event feeds report detected and processed earthquakes; they do not guarantee advance warning. Data may be delayed, incomplete, or unavailable. Do not rely on this website or browser notifications for protective action. Follow local emergency-management instructions. During shaking, Drop, Cover, and Hold On.

Browser notifications require permission and a supported browser. Sound may require a user interaction first. Keep the page open for periodic checks; background tabs may be throttled.
