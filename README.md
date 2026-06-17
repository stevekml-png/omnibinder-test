# OmniBinder Hosted Test v2

This version is for real HTTPS testing on GitHub Pages / Netlify / Vercel.

## What changed in v2

- Separate mobile buttons:
  - Choose from library
  - Take photo
- Uses `capture="environment"` only on the camera button.
- The library button has no `capture`, so iPhone should allow choosing from Photos.
- Photo previews are displayed as separate cards.
- Tap/click photo to enlarge.
- Photos are stored only in browser localStorage for demo testing.

## Deploy

Upload `index.html` and `README.md` to the root of your GitHub repository, replacing the old files.
