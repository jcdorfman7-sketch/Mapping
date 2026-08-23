# V12.2 Atlas — iPad/layout repair

- Filters are now outside the map canvas, so collapsing them cannot leave a dead/blank area over the map.
- Closing details hides the panel cleanly and invalidates Leaflet size so the map reclaims space.
- Explicit DOM references replace fragile browser ID globals.
- Ground markers now actually use the V12 canonical icon system (V11's function was named gi(), which the first V12 patch missed).
- Removed a duplicate country-border GeoJSON loader.
- Added startup fail-safe and Leaflet resize refresh.
- All V11/V12 data and features remain self-contained in four files.
