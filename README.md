# V12.4 — live repository fix
The deployed V12.3 index.html was inspected directly in GitHub.

Root cause: the JavaScript bound a click handler to `#collapseFilters`, but the actual HTML did not contain `#collapseFilters` or `#filterBody`. `document.getElementById("collapseFilters").onclick = ...` therefore threw immediately and halted initialization before marker creation, master-list rendering, and the remaining button handlers.

V12.4 restores the missing filter header/body markup and makes the collapse binding defensive so an optional missing control cannot kill the application again.
