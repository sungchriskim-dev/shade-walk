# Shade Walk

Solar-aware pedestrian routing: plan walking routes that stay in the shade, or out of the rain, using live sun position, 3D building shadows, mapped trees, weather forecasts and rain radar.

**Try it:** open `index.html` (or the GitHub Pages link for this repository). Allow location access, or search for a start and destination in Brisbane.

- Shade mode: compares a Max Shade route with the direct route, with shaded metres from buildings and trees
- Rain mode: hourly rain on the time slider, falling-rain animation, and a Dry Route that keeps you under mapped cover (walkways, arcades, stations, bus shelters)
- Time slider with moving shadows, best-time-to-walk forecast, and walking navigation

Built in September 2026 by Chris Kim using AI coding assistants. Single HTML file using MapLibre GL, SunCalc, OpenStreetMap (OSRM, Overpass, Nominatim), Photon, OpenFreeMap, Open-Meteo and RainViewer.

Full design notes: [Shade_Walk_Documentation_v16.pdf](Shade_Walk_Documentation_v16.pdf)
