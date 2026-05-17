# Yugen Exchange

An atmospheric live currency converter built as a polished Progressive Web App.

Yugen Exchange combines a cinematic blue-black visual style with a compact conversion interface designed for mobile-first use, Safari Home Screen installation, and fast everyday currency checks.

## Live App

Try it here:

https://yugenexchange.netlify.app/

## Features

- Live exchange rates via the Frankfurter API
- Installable PWA with custom iOS Home Screen icon
- Mobile-first single-screen interface
- Typed currency codes with a custom animated picker
- Currency symbol formatting for supported currencies
- Offline-ready app shell through a service worker
- iOS safe-area and standalone display polish

## Preview

The app is designed around a dark, cinematic visual identity with a quiet glass-panel converter over full-bleed artwork.

```text
Amount + From
Swap
To + Result
Live rate line
```

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- Progressive Web App manifest
- Service worker caching
- Frankfurter exchange-rate API

No build step is required for the web app.

## Project Structure

```text
.
|-- index.html
|-- style.css
|-- app.js
|-- manifest.json
|-- sw.js
|-- assets/
|   |-- bg.png
|   |-- apple-touch-icon.png
|   |-- icon-192.png
|   |-- icon-512.png
|   `-- icon.svg
|-- ios-native/
`-- ios-widget/
```

## Installing on iPhone

1. Open https://yugenexchange.netlify.app/ in Safari on iPhone.
2. Tap the Share button.
3. Select **Add to Home Screen**.
4. Confirm the app name: `Yugen Exchange` or the configured Japanese display name.

The app will launch as a standalone PWA from the Home Screen.

## Privacy

The app does not require user accounts or API keys. Conversion requests are made directly to the Frankfurter API.

## Credits

Created by `@crisroma`.
