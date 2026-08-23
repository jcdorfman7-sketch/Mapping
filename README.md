# Augsburg Adventure Radius V9 — Fixed

This replaces the broken V9 build.

## Critical fix
The previous V9 had a JavaScript syntax error in the Save / Skip / Trip action-button HTML builder. Because the parser failed, Leaflet initialization and every button handler after that point failed too. This build replaces those fragile inline onclick strings with event delegation and data attributes.

## Retained V9 features
- Essential / Major / Hidden Gem / Worthwhile hierarchy
- larger high-contrast touch markers
- persistent Favorites and Skip list
- persistent Mini Trips
- food intel
- drive / train / flight filtering
- Vienna deep destination hub as the first model for the deeper treatment intended across ALL cities

## Borders
Country borders are now a darker/thicker optional GeoJSON overlay. They load only after the app is initialized and cannot break the map if the external border source is unavailable.

## Next intel pass
Vienna was an example, not a Vienna-only requirement. The next systematic content expansion should bring all major ground and flight destinations toward the same depth.
