MY LEDGER — ANDROID INSTALLATION

This is a real offline-first Progressive Web App (PWA), not an APK.

1. Upload ALL files in this folder to an HTTPS static website host (for example GitHub Pages, Netlify, or Cloudflare Pages). Keep the files together at the same path.
2. On Android, open the hosted HTTPS address in Chrome.
3. Chrome menu (three dots) > Install app or Add to Home screen.
4. Open My Ledger from the home screen. Visit once online before using it offline.

IMPORTANT
- A downloaded HTML file opened directly from your phone's file manager is not an installable PWA. It needs HTTPS hosting for installation and offline service worker support.
- Transactions, budgets and bills are stored in the browser's IndexedDB on that phone, not in the cloud.
- Export a JSON backup frequently from Settings; keep it safe. Clearing browser/site data may erase your register.
- This is a personal bookkeeping tool, not a bank-connected financial service.
- This version supports one account. Multi-account support, encryption, reminders and additional reporting can be added in future versions.
