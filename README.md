# Lufthansa Live Map

Live positions of airborne Lufthansa (LH) flights, using data from the [AirLabs API](https://airlabs.co).

- `index.html`: 3D WebGL globe with three altitude layers (0–3,500 m, 3,500–9,000 m, above 9,000 m)
- `map.html`: flat latitude/longitude world map

Data refreshes every 60 seconds; between refreshes, positions are projected from each flight's speed and heading.
