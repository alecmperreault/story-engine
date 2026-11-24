# Story Engine (phone version)

A personal, offline phone app for drawing and arranging Story Engine cards.

This repository holds only the app. It contains no card text: the cards are loaded on the phone from my own workbook or a saved session file, and they stay stored on the phone.

## Files

| File | Purpose |
|---|---|
| index.html | The app |
| xlsx.mini.min.js | Reads Excel workbooks (SheetJS) |
| sw.js | Lets the app work offline |
| manifest.webmanifest | Name, colors and icon for "Install app" |
| icon-192.png, icon-512.png, icon-maskable-512.png | App icons |

## Updating the app

1. Upload the changed files over the old ones (Add file > Upload files).
2. Open `sw.js` and change `se-mobile-v1` to the next number (`se-mobile-v2`, and so on). This tells phones to fetch the new version.
3. On the phone, open the app, then close it and open it again.
