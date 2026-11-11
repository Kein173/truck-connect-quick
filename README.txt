TRUCK CONNECT QUICK — browser prototype

Files:
- index.html: responsive interface and interactions
- manifest.webmanifest: installable web app metadata
- sw.js: basic offline cache

Prototype features:
- Main screen with agreed button layout
- WhatsApp click-to-chat with event text and local time
- Five language options
- One WhatsApp number and one CMR email in local settings
- CMR photo/file selection and system share sheet where supported
- Custom WhatsApp message

Important limitations:
- This is a prototype, not a published or hosted app.
- WhatsApp opens with a prefilled message; the user must press Send.
- Browsers cannot guarantee automatic return from WhatsApp or Mail.
- A browser PWA cannot reliably prefill the recipient in Apple Mail and attach multiple files in the same composer. The attachment action uses the system share sheet; choose Mail and verify the recipient.
- For fully integrated CMR email with fixed recipient, multiple attachments, and more reliable app switching, a native iOS/Android app is the appropriate next implementation.
- Settings are stored locally in the browser; no server or message history is used.

To test as a web app, host these files over HTTPS. PWA installation and camera/share capabilities vary by browser and device.
Update Truck Connect Quick
