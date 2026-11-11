# Hip Fracture DOAC Timing Aid — mobile app package

This package wraps the supplied HTML calculator as an installable Progressive Web App (PWA).
The calculator's existing clinical decision logic and wording have been retained; the app shell
adds an install manifest, app icons, and offline caching.

## Install it on a phone

A PWA must be served from a secure HTTPS website to be installable. Opening `index.html`
directly from Files/Downloads is not enough for the normal install flow.

### Easiest route (using a computer)
1. Unzip this package.
2. Upload the *contents* of this folder to a static HTTPS host such as Netlify Drop
   (https://app.netlify.com/drop) or a GitHub Pages site.
3. Open the resulting HTTPS website on your phone.

### Android
1. Open the HTTPS app link in Chrome.
2. Tap the browser menu (⋮), then **Install app** or **Add to Home screen**.
3. Confirm. Open it from the new home-screen icon. It will cache for offline use
   after the first successful visit.

### iPhone
1. Open the HTTPS app link in Safari.
2. Tap **Share** → **Add to Home Screen**.
3. If offered, enable **Open as Web App**, then tap **Add**.
4. Open it from the new home-screen icon. Visit once while online before relying on it offline.

## Important clinical-use note
This is a technical conversion of the supplied decision aid, not clinical validation or endorsement.
The source itself says it is not a formal guideline and that consultant judgement prevails.
Check the current approved local guideline and governance requirements before clinical use.
Do not enter identifiable patient information. The app does not send calculator inputs to a server.
