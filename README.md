# V13.1 — Phone stabilization
- Phone-only breakpoint at <=600px. iPad/desktop V13 behavior is left intact.
- Full result database retained on phone.
- Filters start collapsed on phones.
- Map is always visible during phone initialization; Map/Results controls scroll instead of hiding/reconstructing Leaflet.
- Repeated Leaflet size invalidation after phone layout settles and after resize/orientation changes.
- Country-border decorative overlay is skipped on phones only; attractions/events/flights/food are not reduced.
- More prominent internal scrollbars for filters and results where the browser exposes custom scrollbars.
- Visible “Results below” cue and “Back to map” control.
- Details remain closed until a place is selected.
