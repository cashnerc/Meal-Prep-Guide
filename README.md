# Weekly Kitchen Manual

Single-page meal planning app. 27 lunches, 27 dinners, all scaled to six servings
(Monday–Saturday; Sunday flexible).

**Choose → Shop → Cook.** Pick one lunch and one dinner; it merges the two ingredient
lists with the fixed daily items into one checkable shopping list, then generates a
Sunday timeline with both dishes interleaved on a single clock.

## Install

Upload the six files at the top level of a public repo, then
Settings → Pages → Deploy from a branch → `main` → `/ (root)`.

- **iPhone / iPad:** open the URL in Safari → Share → Add to Home Screen
- **Android:** open in Chrome → three-dot menu → Install app

Works offline once installed. Picks and checked shopping items persist on the device.

## Sharing a week between devices

Every pairing has its own URL, e.g. `#L26-D22`. Use **Copy week link** and text it to
yourself — opening it on another device loads that exact week.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app — recipes, logic, styles |
| `manifest.webmanifest` | App name, icons, standalone display |
| `sw.js` | Service worker; offline cache |
| `icon-*.png` | Home screen icons |
