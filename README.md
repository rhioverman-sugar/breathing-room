# Breathing Room

A small mobile-friendly, manual-entry cash-flow planner. No bank connections, analytics, external scripts, or third-party accounts.

## Run

Open `index.html` locally, or host it over HTTPS as a static site. On an iPhone, add the hosted page to the Home Screen. A private GitHub repository **does not** provide a private GitHub Pages site on typical personal plans. Do not publish an import file or export to a publicly accessible site.

## First use

Open Settings → Restore / import records, choose `personal-starter.json` stored privately on your phone, and verify each balance, due date and arrangement. The starter file is delivered separately and must **never** be committed to GitHub. Then update actual cash if anything changed, and enter transactions manually.

Data is stored in browser `localStorage` for the specific origin/browser. Use Settings → Download encrypted backup frequently, and separately store the password. On iOS, clear browsing data or a different site URL may lose access to data. Browser localStorage is not device-level encrypted by this app. A local-only web app cannot sync automatically across devices.

## How forecast works

Cash balance = opening available cash + recorded income − recorded spending − recorded bill payments. Expected income does not increase cash until recorded as received. Current outstanding bill balances are separate from cash. Each bill has a list of planned payments against its opening balance. Recurring future monthly charges are estimates and don't silently expand the saved opening balance. Unscheduled outstanding balances appear as a prominent forecast warning rather than being placed on an invented due date. Confirm actual statements and payment arrangements.

This is a prototype, not financial, payment or disconnection advice. Verify bill dates and amounts before relying on forecast.
