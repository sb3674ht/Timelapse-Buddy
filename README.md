[README.md](https://github.com/user-attachments/files/21740435/README.md)
# TimeLapse Calculator PWA

A simple Progressive Web App (PWA) that calculates the shooting interval, total photos, and estimated storage for creating time-lapse videos.

## Features

- **Event Duration Input** – Set how long your real-world event lasts (in minutes).
- **Final Video Length Input** – Desired length of your final time-lapse video (in seconds).
- **Frame Rate Input** – Choose your frames per second (fps).
- **Exposure Time Input** – Optional, to check if exposure time fits within the interval.
- **File Size Input** – Estimated size per photo (in MB).
- **Instant Calculations** – Shows total frames, shooting interval, total photos, and estimated storage.
- **Offline Ready** – Works without internet once loaded (PWA).
- **Installable** – Add to your home screen on mobile or desktop.

## How to Use

1. Enter your **Event Duration** in minutes.
2. Enter your **Final Video Length** in seconds.
3. Set your **Frame Rate (fps)**.
4. Optionally set **Exposure Time** to check for interval warnings.
5. Set estimated **File Size per Photo** in MB.
6. View your results instantly in the Results section.

If the exposure time is longer than the interval, a warning will be displayed.

## Installation as PWA

Once the app is deployed:
- Open the site in Chrome/Edge on desktop or mobile.
- Click the **Install App** button (or use browser's install prompt).
- The app will now be available offline and launch in standalone mode.

## Deployment Instructions

1. **Download the ZIP** and extract it.
2. Upload the contents to a static hosting provider such as:
   - [Netlify Drop](https://drop.netlify.com/)
   - GitHub Pages
   - Vercel
3. Ensure `manifest.json` and `service-worker.js` are in the root of your site.
4. Visit the deployed URL in your browser.

## Project Structure

```
index.html           # Main app
manifest.json        # PWA metadata (icons, name, colors)
service-worker.js    # Caches files for offline use
icon-192.png         # App icon (192x192)
icon-512.png         # App icon (512x512)
README.md            # This file
```

## License

This project is released under the MIT License.
