# Augsburg Adventure Radius V8

Stability + discovery rebuild.

- Fixes the broken Flights toggle.
- Drive / Train / Flights are independent and may all be off.
- Filters are separated into Travel Mode, Ground Time, What To Do, Flight Price, and Airport rows.
- Zoom performance rebuilt: 87 ground markers are created once; zooming does not destroy/recreate them.
- Mobile bottom-sheet details with Overview / See / Eat / Trips tabs.
- Food is a visible first-class feature.
- Rome includes ❤️ La Fata Ignorante as a Personal Favorite.
- Flight markers show city + fare.
- Adds Oslo and Barcelona to the flight dataset.
- Dublin includes an observed $84 RT MUC–DUB example for Nov 13–21, 2026.
- Fare filters: $75 / $100 / $125 / $150 / $200.
- FMM / MUC / Either filter.
- New service-worker cache strategy reduces stale-version problems.

Upload/replace index.html, manifest.webmanifest, sw.js, README.md in the Mapping repository root and commit.
