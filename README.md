# Water

A daily water tracker that works as a home-screen app. Log drinks, watch the figure fill up, and check your last 7 days.

## Run it on GitHub Pages

1. Upload every file in this folder to the root of a GitHub repository.
2. In the repo, open **Settings > Pages**.
3. Under **Build and deployment**, set Source to **Deploy from a branch**, pick `main` and `/ (root)`, then save.
4. After a minute or two, the site is live at `https://<your-username>.github.io/<repo-name>/`.

## Add it to your home screen

- **iPhone:** open the link in Safari, tap Share, then **Add to Home Screen**.
- **Android:** open the link in Chrome, tap the menu, then **Add to Home screen** or **Install app**.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole app |
| `manifest.webmanifest` | App name, colors, and icons for Android |
| `apple-touch-icon.png` | Home-screen icon for iPhone |
| `icon-192.png`, `icon-512.png` | Icons for Android and the browser tab |
| `icon.svg` | Source artwork for the icon |

Data is saved in the browser on each device, so your phone and laptop keep separate logs.
