# V12.3 runtime fix
Root cause fixed: V12.2 called closeDetails() during startup before `selectedMasterId` had been initialized. JavaScript's temporal-dead-zone rules caused a ReferenceError, halting the entire application before markers, master-list results, and button handlers initialized.

V12.3 declares state before use and establishes the initial closed-details layout without calling map-dependent code before Leaflet is constructed.
