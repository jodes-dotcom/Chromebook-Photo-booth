# Memory Booth v6 — Custom Guest Home Screen

This update adds editable guest welcome wording and home-screen colours to the v5 app.

## New admin options
- Welcome heading (supports a line break)
- Welcome description
- Home background colour
- Home text colour
- Guest button accent colour (choice-card borders, icons and hover state)

These settings save on the device and are included in saved event profiles, so you can create a different look for each booking. Existing keyboard choices remain: 1 single photo, 2 pose challenge, 3 filter mix, 4 standard four-photo session.

## Update on GitHub Pages
1. Extract this ZIP.
2. Open the `memory-booth-pwa` folder.
3. Upload/replace its contents in the root of your existing GitHub Pages repository. Keep `index.html`, `manifest.webmanifest`, `sw.js`, and `icons/` at the repository root.
4. Commit the changes and wait for GitHub Pages to deploy.
5. Open Memory Booth while online and reload it. The service-worker cache version has been updated to v6.
6. Open Host settings (default PIN `2468` if you have not changed it), edit the Guest home screen customisation fields, and save.

## Notes
- Colour controls affect the guest welcome screen. Accent colour remains a separate setting for the app and photo layout.
- Existing settings are retained where available; new fields use the default Memory Booth palette until you customise them.
- Test camera capture and SD-card saving after any app update before using it at a paid event.
