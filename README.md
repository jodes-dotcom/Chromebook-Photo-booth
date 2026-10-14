# Memory Booth v5 — Pose Challenge + Filter Mix

## Keyboard choices
- **1**: Single photo (existing mode)
- **2**: Pose Challenge — takes four photos and shows a random fun pose prompt before every photo
- **3**: Filter Mix — takes four photos and applies the four filters selected by the host, one per photo, to the finished PNG layout
- **4**: Standard four-photo session (existing mode)

The number-row keys and numeric keypad keys are supported. Guests can also click the four on-screen choices.

## Configure the four filters
1. Open Memory Booth and choose **Host settings**.
2. Sign in with your existing administrator PIN.
3. In **Filter Mix — filter for each of the four photos**, choose a filter for Photo 1, Photo 2, Photo 3 and Photo 4.
4. Save event settings. These filter choices are included in saved event profiles.

Available filters: Original, Vivid, Black & White, Warm Vintage, Cool Tone and Soft Matte.

## Update an existing GitHub Pages installation
1. Download and extract this ZIP.
2. Open your existing GitHub repository used by Memory Booth.
3. Upload the **contents** of the `memory-booth-pwa` folder to the repository's publishing root, replacing the old files. Keep `index.html`, `manifest.webmanifest`, `sw.js` and `icons/` at the root.
4. Commit the changes and wait for GitHub Pages to publish.
5. On the HP, open the app URL while online and reload it. If the old version remains, close the app window, reopen the URL in Chrome and reload.
6. Open Host settings and verify your saved event profile. If the app asks again, reselect the SD-card folder.

## Notes
- Original JPG captures remain unfiltered. The four selected filters are applied to the individual photo cells in the finished PNG layout. This preserves unedited originals on the SD card.
- Pose Challenge (key 2) always shows a random prompt. The existing admin toggle controls whether prompts also appear in regular single/four-photo sessions.
- The app is a browser-based PWA and must be tested on the actual ChromeOS Flex computer before paid events. Check camera access, folder permission and SD-card writes.
- Keep the existing admin PIN; change it if it is still the default `2468`.
