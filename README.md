# V13.3 — phone recovery + city readability
Built from V13.1, the last phone build that demonstrably rendered the map.

Phone <=600px:
- Removes obsolete fixed Filters/Augsburg/Details toolbar.
- Uses one stable 100vw x 430px Leaflet map box that is never hidden or resized by details/filters.
- Filters and details are overlays, not layout participants.
- Full result set retained.
- Decorative country-border overlay skipped on phone only.
- Results remain in a bounded scroll box with stronger scrollbar.
- Simple Filters and Results controls.

All devices:
- Destination hubs now have persistent city-name labels in a dedicated high-z-index Leaflet pane, so attraction icons are less likely to bury city names.
