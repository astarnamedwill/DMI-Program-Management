# DMI Program Management

A simple, GitHub Pages-compatible portal linking the existing CCSF DMI Course Scheduling and Dose Badge Inventory applications behind one navigation interface.

## Deploy

1. Create a new GitHub repository, e.g. `DMI-Program-Management`.
2. Upload `index.html` and `README.md` to the root of the main branch.
3. Under Settings → Pages, select Deploy from a branch → `main` → `/ (root)`.

## Important limitations

- This is a **unified navigation portal**, not a source-code or database merge. The original applications remain separately hosted, and data is not synchronized across apps.
- The Dose Badge Inventory host may block embedding in an iframe. The portal provides a direct-link fallback.
- Avoid deleting either original site or clearing browser storage. The schedule app currently stores changes locally within its own origin.
- A full standalone merged app requires exporting or obtaining the source and data model of the Dose Badge Inventory app. Once available, the modules can be brought into one build and shared persistence/authentication can be designed.
