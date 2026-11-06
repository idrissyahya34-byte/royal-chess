ROYAL CHESS ULTIMATE — APP EDITION

FILES
- index.html: game
- chess.min.js: chess rules engine
- manifest.json: installable app settings
- sw.js: offline cache (after first successful load)
- icon.svg: app icon

IMPORTANT
This project uses chess.js 0.10.3 from cdnjs in index.html. The first run needs internet.
The service worker caches the game files on a supported HTTPS/local web server.
Opening index.html directly as file:// will let the game run, but PWA installation and
offline service-worker features require HTTPS or localhost.

ANDROID INSTALL
1. Upload the whole folder to an HTTPS static host, or run it from localhost.
2. Open the page in Chrome.
3. Open Chrome menu and choose "Install app" or "Add to Home screen".

DESKTOP
Open the HTTPS page in Chrome or Edge and use the install icon/menu.

The AI difficulty uses a small minimax search. Hard mode can take longer on slower phones.
