CASHBOOK LKR — INSTALLABLE APP

Files:
- index.html: the app
- manifest.webmanifest: installable app metadata
- sw.js: offline cache
- icon-192.png / icon-512.png: app icons

IMPORTANT:
This is a Progressive Web App (PWA). For installation and offline caching, it must be served from HTTPS or localhost. Opening index.html directly may let you use the tracker, but browser install/offline features will not work.

EASIEST FREE TEST ON A COMPUTER:
1. Install Python if it is not already installed.
2. Extract this ZIP.
3. Open a terminal/Command Prompt in the extracted folder.
4. Run: python -m http.server 8000
5. In your browser, open: http://localhost:8000
6. Use the browser's Install app option (often shown in the address bar or browser menu).

TO INSTALL ON A PHONE:
The app must be hosted on a secure HTTPS address. You can publish these files using a free static host such as GitHub Pages, then open that HTTPS site on your phone and choose "Add to Home Screen" / "Install app".

DATA:
Your records are stored locally in the browser on that device. There is no account, cloud sync, or automatic backup. Use Backup > Export backup regularly. Import backup restores data and replaces current app data.

CASH COUNT:
Transactions are a ledger only. They do not automatically change denomination counts. After receiving or spending cash, update Count cash to reflect the notes and coins physically in your possession.
