# Table Rock Services invoices

A small, static invoice creator and receivables tracker. Open `index.html` to use it locally, or upload `index.html` and `logo.png` to a GitHub repository and enable GitHub Pages for that branch. No build process or server is needed.

Create an invoice once and it appears in the ledger. Record full or partial payments, print or save a PDF through the browser print dialog, and export or restore a JSON backup.

**Data location:** This version saves invoices in the browser's local storage. Each browser/device has separate data. Browser resets and private browsing can erase it. Use **Backup / Restore → Download backup** regularly. For shared live use across two devices, the next version needs a hosted database and authentication. Do not enter live invoices independently on separate devices and expect them to merge.

No sample invoices are preloaded. Existing spreadsheet invoices can be entered manually; a future CSV import can streamline that after the fields are confirmed.
