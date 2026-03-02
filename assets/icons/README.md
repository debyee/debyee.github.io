Place your favicon and app icons in this folder to override the theme defaults.

Required (recommended):
- favicon.ico (32x32 PNG saved as .ico or an actual .ico file)
- icon-192x192.png

Optional (for better PWA support):
- icon-512x512.png
- icon-384x384.png
- icon-152x152.png
- icon-144x144.png
- icon-128x128.png
- icon-96x96.png
- icon-72x72.png

Recommended workflow:
1. Start with a square PNG at least 512x512 pixels.
2. Use Maskable.app to generate a safe icon, then use a manifest generator (e.g., https://app-manifest.firebaseapp.com/) to create multiple sizes.
3. Copy the generated `icons/` folder into `assets/` and ensure `favicon.ico` and `icon-192x192.png` are present.

Example paths referenced by the site config in `_config.yml`:
- `/assets/icons/favicon.ico`
- `/assets/icons/icon-192x192.png`

After placing the files, run the dev server or build:

```bash
./tools/run.sh    # dev server with live reload
./tools/test.sh   # build for production
```
