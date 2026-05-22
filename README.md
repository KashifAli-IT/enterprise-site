# Atlas United Enterprise

Atlas United Enterprise is a single-file, offline-friendly business accounting & management system.

## What’s Included

- Sales invoices (cash + credit) with auto-posted double-entry journal entries
- Purchase bills (cash + credit) with inventory updates
- Payments Received / Payments Paid
- Return invoices (sales returns) with COGS + stock reversal
- Expenses (with custom categories)
- Customer & Supplier ledgers, recovery sheets
- Product ledger and stock overview (carton + loose units)
- Journal Entries + Chart of Accounts
- Financial reports (P&L, Balance Sheet, Cash Flow, Aging, Sales Analysis)
- Backup & Restore (JSON export/import)
- Print + PDF export (templates are built-in)

## Run

This project is plain HTML/CSS/JS (single file). No setup required.

1. Open `atlas_united_enterprise (2).html` in your browser.
2. Login:
   - **Admin**: `admin` / `admin1234`
   - **Salesman**: create a salesman inside the app, then login using that username/password.

> Data is stored locally in your browser via `localStorage`.

## Notes

- For PDF export/printing, the app uses in-browser rendering.
- Period lock/backup/restore features are available from **Setup / Backup & Restore** in the UI.

## License

Add your license here (e.g., MIT). If you don’t specify one, GitHub will default to “All rights reserved.”

