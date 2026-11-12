TRUCK CONNECT QUICK — v21 CMR document scanner

Files: index.html, manifest.webmanifest, sw.js and app icons.

Changes in v21:
- On-device document-edge detection for high-contrast paper backgrounds.
- Automatic crop and perspective correction when a page is detected.
- Preserves the page's original color information.
- Falls back to the full camera frame when edges cannot be detected reliably.
- Combines captured pages into one PDF.
- After the system share action completes, clears temporary scan images, generated PDF references and selected attachment references from app memory. If sharing is cancelled, files remain available for retry.
- No document archive or app-side scan history.

Important:
- Detection works best with a light sheet on a darker, contrasting, flat surface.
- The camera requires HTTPS and permission.
- The PDF is handed to the phone's share sheet; verify the recipient and press Send in the mail app. The app cannot verify that the email itself was sent.
- Settings remain stored locally as before.
