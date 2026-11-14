# Mamento

A gentle daily recovery tracker. One page, no build step.

## Put it on GitHub Pages
1. Create a new repository on github.com (for example `mamento`). Public is fine; the app keeps your data only on your phone.
2. Upload everything in this folder (drag the files and the `icons` folder into the repo page), then commit.
3. Open the repo's **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, pick **main** and **/ (root)**, then Save.
4. After a minute your app is at `https://YOUR-NAME.github.io/mamento/`.

## Put it on your home screen
- **iPhone (Safari):** Share → Add to Home Screen.
- **Android (Chrome):** menu → Install app.

## Updating
Replace `index.html` in the repo with the new file, then change `VERSION` in `sw.js` (for example `mamento-v2`) so phones refresh their saved copy.

## Your data
It is stored on each device. A new web address starts empty, so pick your final address first. Use **Profile → Your data → Backup** to save or restore a file.
