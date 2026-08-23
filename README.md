# V13.2 — rebuilt phone interface
Phone <=600px only:
- Removed legacy Filters/Augsburg/Details mobile toolbar.
- Dedicated Filters launcher and overlay; filters never sit behind navigation.
- Map has a permanent 420px phone height and remains in layout at all times.
- Details are a fixed bottom overlay and cannot resize/reflow the map.
- Opening/closing details preserves map center and zoom.
- Full result dataset retained.
- Results list remains bounded and scrollable with a visible scroll affordance.
- Phone map receives delayed post-layout Leaflet invalidation.
iPad and desktop V13 behavior remains untouched.
