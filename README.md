# Rangs Motors Workshop ERP — GitHub Pages upload

Upload both `index.html` and `parts-catalog.csv` to the repository root used by GitHub Pages. The ERP loads the 30,000-row reference parts catalog from the adjacent CSV on first visit and stores it in browser IndexedDB.

## Catalog data note

This starter catalog contains estimated reference rates, no OEM part numbers, and unverified model fitments. All opening stock is zero. Verify against VIN and an authorized OEM/dealer catalog before issue or customer billing. Import your verified CSV through **Parts Master → Import CSV** to update the records.

## Publish

1. Upload `index.html` and `parts-catalog.csv` to the repository root.
2. Open **Settings → Pages**.
3. Choose **Deploy from a branch**, select the default branch and `/ (root)`, then save.
4. After deployment, open the Pages URL and hard refresh with **Ctrl+Shift+R**.