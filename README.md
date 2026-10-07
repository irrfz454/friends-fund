# Friends Fund

A small app for a group of friends who keep a shared fund: everyone deposits a fixed amount each month, and the treasurer records collections and expenses. It shows who has paid, pending dues, where the money went, and how much is left at any date.

**Open it:** https://irrfz454.github.io/friends-fund/

## Install on iPhone

1. Open the link above in **Safari** (not Chrome or the WhatsApp in-app browser).
2. Tap the **Share** button (square with an arrow), then **Add to Home Screen**, then **Add**.
3. Open it from the new **Fund** icon on your home screen. It runs full-screen and works offline.

## Your data

Everything is stored only on the device, inside the app. Nothing is sent to GitHub or anywhere else; this repository holds only the app's code.
Use **Download backup** regularly (for example after each month's collection) and save the file to Files, iCloud Drive or WhatsApp. **Restore from backup** in Settings loads it on a new phone.

Note: the copy installed on the home screen keeps its own data, separate from the Safari tab. Enter your data in the home-screen app.

## Files

- `index.html`: the whole app
- `manifest.webmanifest`, `icon-*.png`: home-screen name and icon
- `sw.js`: makes the app work offline
