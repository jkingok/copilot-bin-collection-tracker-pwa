# Bin Collection Tracker PWA

A simple, installable Progressive Web App (PWA) for tracking rubbish bin collection cycles at multiple locations. Designed to work offline and on iOS/Android, with geolocation support and a user-friendly Bulma CSS interface.

## Features

- Add and manage multiple locations for bin collection
- For each location, specify bins (number, size, color) and collection patterns (days in fortnight)
- Geolocate your device to find the nearest saved location and view next bin collection
- Works offline (service worker)
- Fully client-side, no build step, no dependencies besides Bulma CSS (via CDN)
- Installable as an app on iOS and Android

## How to Use

1. [Download the single HTML file](./bin-collection-tracker.html) and open it in your browser.
2. Click "Add to Home Screen" in your mobile browser for the best experience.
3. Replace `YOUR_API_KEY` in the HTML file with your own key from [OpenCage](https://opencagedata.com/), [Mapbox](https://www.mapbox.com/), or [Google Maps Geocoding](https://developers.google.com/maps/documentation/geocoding/start).
4. Start adding locations and bins!

## Attribution

This project was generated with assistance from [GitHub Copilot](https://github.com/features/copilot).

## License

This code is released under the MIT License. See [LICENSE](./LICENSE) for details.