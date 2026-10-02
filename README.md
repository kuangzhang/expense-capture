# Expense Capture

Snap an invoice photo, get the line items. Export tax-ready CSV.

- 100% on-device OCR (Tesseract.js) — the photo never leaves the device.
- Guided wizard: splash intro → single/bulk choice → capture with upload progress → photo-quality check → review & fix line items → export.
- Export formats: Default CSV, Xero (bills), QuickBooks Online (bills), FreshBooks (expenses). Email the CSV or save it locally.
- Bulk scan with per-invoice review — clean invoices can be skipped, flagged ones get attention.
- Saved invoice history, CSV import, Google Drive photo archive (optional, needs a Drive OAuth client ID).

Single self-contained `index.html` — no build step. Deploy anywhere static.
