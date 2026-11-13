# Mileage & Expense Log

Log business mileage, meals and expenses with receipt photos, see yearly totals at the IRS
standard mileage rate, print a tax report, and export CSV files for your accountant.
Supports multiple businesses and color themes.

**Open / install the app:** https://taraleightechnologies-coder.github.io/mileage-log/

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest` | App name, icon and colors (lets phones and PCs install it) |
| `sw.js` | Offline support. **Change `VERSION` in this file every time the app changes**, so installed copies update |
| `icons/` | App icons (192, 512 and 180 for iPhone) |

## Opening it

- **Right now (this PC only):** double-click `index.html`. Works in Edge or Chrome.
- **As an installed app:** the app must be online (step 2: GitHub Pages). Then open the link and
  click **Install app** (PC/Android) or Share → **Add to Home Screen** (iPhone).

## Your data

Entries and receipts are saved inside the browser/app on each device. They are never uploaded.
Use **Settings & Backup → Download backup** regularly, and **Restore** to move data to another device.

## Roadmap

1. Installable app (done)
2. Host free on GitHub Pages (done)
3. Install on phone and both PCs
3b. Share with a second person (Supabase sync)
4. Google Play Store (PWABuilder → Android package; $25 Google Play developer account)
5. Apple App Store (needs an Apple Developer account and a Mac, or a cloud Mac build service)
