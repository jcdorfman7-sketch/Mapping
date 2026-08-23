# Augsburg Adventure Radius V12 — Atlas

V12 is the visual-polish and architecture release.

## GUI
- Cleaner Atlas visual system, cards, spacing and typography.
- Collapsible filter panel to reclaim map space.
- Dismissible details panel with × and Escape support.
- Closing details reclaims desktop map width.
- Tablet uses an overlay details panel so the map is not squeezed.
- Phone uses a dismissible bottom-style details sheet.
- Tapping the same selected marker again closes its details.

## Canonical visual language
Importance and place type are now separate:
- 🔥 Essential
- ⭐ Major
- 💎 Hidden Gem
- 👍 Worthwhile
- 🏰 Castle / Palace
- 🏛️ Museum / History
- ⛪ Architecture
- 🌲 Nature
- 🍴 Food
- 📅 Event
- ✈️ Flight

The legend, filters, list and ground markers use the same meanings.

## Architecture
Travel data has been separated from index.html into data/travel-data.js. This is the first step toward making future destination-intelligence expansions safer.

## Retained
V11 synchronized map/master list, date-aware events, Discover, favorites, skip, mini trips, seasonal intelligence, flight filters and non-critical country borders are retained.
