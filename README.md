# V13.5 — structural mobile fix

Root cause found:
`.app` was accidentally nested inside `#filters` because the filters container was missing its closing `</div>`.

On iPhone the filters panel is hidden until opened, which therefore hid the entire application—including the map, results, and phone controls.

V13.5 closes `#filters` before `.app`.

Validation:
- `.app` is now a sibling of `#filters`
- `#map` remains inside `.app`
- JavaScript syntax passes
