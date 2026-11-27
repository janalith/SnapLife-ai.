# SnapLife AI — free starter prototype

## What's included
- Responsive web app that also supports installation as a mobile PWA.
- Upload a JPG, PNG or WEBP image.
- Browser-based OCR using Tesseract.js (loaded from a free CDN).
- Edit recognized text, add a title/category/reminder, and save.
- Search saved titles, notes and recognized text.
- IndexedDB storage local to the browser/device.

## Run it
For a quick local preview, open `index.html` in a modern browser. OCR may be more reliable when served from a local web server or HTTPS.

## Publish free with GitHub Pages
1. Create/sign in to a GitHub account.
2. Create a new public repository named `snaplife-ai`.
3. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to the repository root.
4. Open repository Settings → Pages.
5. Under Build and deployment, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
6. Wait for the published Pages URL.
7. Open that URL on Android Chrome. Use the browser menu → Add to Home screen / Install app.

## Important limitations of this first prototype
- No accounts, cloud sync, shared access, or server backup.
- Saved items are stored only in the browser on the device used to add them. Clearing browser data can erase them.
- OCR uses a third-party CDN and needs internet access to load the OCR library/language data.
- OCR results can be wrong. Users must review extracted information.
- This is not yet a production-grade AI product. Do not upload passwords, payment card numbers, Social Security numbers, medical records, or other highly sensitive information.
- No reminders are sent in the background; reminder dates are saved and displayed only.
- Test with non-sensitive sample images before inviting customers.
