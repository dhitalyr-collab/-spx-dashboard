SPX MACRO & 0DTE DASHBOARD — VERSION 3

FILES
-----
index.html              Main dashboard
manifest.webmanifest    Home-screen / PWA metadata
sw.js                   Caches the dashboard shell
icon-192.png            App icon
icon-512.png            App icon
apple-touch-icon.png    iPhone Home Screen icon

FASTEST DEPLOYMENT — NETLIFY DROP
---------------------------------
1. Unzip SPX_Dashboard_V3.zip.
2. Go to Netlify Drop in a desktop browser.
3. Drag the entire SPX_Dashboard_V3 folder onto the deploy area.
4. Netlify gives you a public HTTPS URL.
5. Open that URL on your iPhone in Safari.
6. Tap Share -> Add to Home Screen.
7. Name it "SPX Dashboard".

GITHUB PAGES
------------
1. Create a new GitHub repository.
2. Upload all files from this folder to the repository root.
3. Open Settings -> Pages.
4. Under Build and deployment, choose "Deploy from a branch".
5. Select your main branch and root folder.
6. Save. GitHub will publish an HTTPS URL.
7. Open it in Safari on iPhone -> Share -> Add to Home Screen.

IMPORTANT
---------
TradingView widgets require internet access. The service worker caches only the
dashboard shell; live market widgets still need a connection.

Exact real-time status depends on the exchange/instrument and TradingView data
entitlements. Use your broker's executable quote as the final authority for
0DTE order entry.

The dashboard stores your edited SPX levels and checklist selections locally
on the device/browser where you use it.
