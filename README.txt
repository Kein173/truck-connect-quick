TRUCK CONNECT QUICK — v20 CMR scanner feedback update

Files:
- index.html: app interface and interactions
- manifest.webmanifest: installable web app metadata
- sw.js: offline cache (v20)
- icon files: app icons

Changes in v20:
- Clear confirmation after each captured page
- Visible page counter and thumbnail previews
- Each page can be removed before PDF creation
- Capture button shows a saving state and is temporarily disabled to prevent accidental repeated captures
- Short vibration confirmation where supported
- PDF creation button is protected against repeated taps

Existing app functions and layout are retained from the v19 CMR scanner build.

Important:
- Camera access requires HTTPS and browser permission.
- Email attachments are handed off through the phone's system Share menu; the recipient should be checked before sending.
- Settings remain local to the device.
