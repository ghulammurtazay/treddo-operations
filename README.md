# TREDDO Operations — open-source iPhone-friendly starter app

## What it does
A responsive, dark-mode business operations app with TREDDO orange accents. Modules:
- Dashboard and low-stock alerts
- Vendors
- Items and stock on hand
- Purchases
- Stock ledger
- BOM / recipes
- Production batches
- Wholesale sales
- Cashbook
- Expenses
- Reports
- JSON backup/import and CSV export

## Run locally
Open `index.html` in a modern browser. It uses browser localStorage and needs no build tools or external dependencies.

## Use on iPhone
For the best experience, host the files on a static HTTPS host (for example GitHub Pages) and open the URL in Safari. Use Share → Add to Home Screen. The app is responsive but this starter version does not yet include a service worker, so offline availability depends on the browser cache.

## Important limitations
- Data is stored in the current browser/device only; there is no cloud database or multi-user sync.
- No automatic bank, vendor, barcode or accounting integrations.
- Cost/profit values are management estimates and need accounting review before formal reporting.
- Export JSON backups frequently. If browser data is cleared, local records may be lost.

## License
MIT License (see LICENSE).

## Brand styling
TREDDO primary orange #ED4323, black #161616, pale blue #F1F8FC. Use the TREDDO identity consistently.
