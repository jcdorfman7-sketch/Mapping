# Augsburg Adventure Radius V15.1

282 attraction records.

Every attraction now has attraction-specific photo handling:
- Wikipedia page-image search using attraction + city
- additional query variants if needed
- Wikimedia Commons fallback
- successful images cached locally
- direct Google Images “More photos” link on every attraction
- photo code is isolated from map startup

Favorites:
- Excel export
- Text export
- Save Code backup/restore
- old JSON export UI removed

Regression checks passed:
- JavaScript syntax
- critical mobile DOM hierarchy
- Leaflet/map initialization preserved
- clustering preserved
- selected-marker enlargement preserved
