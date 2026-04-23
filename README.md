# 🥭🐒 Mango Monkey

A simple, kid-friendly web app for iPad and iPhone. Swipe your finger across the mango to slice it open and reveal a fortune!

## How to play
1. Open `index.html` in Safari (iPad / iPhone / desktop).
2. Swipe across the wiggling mango.
3. Watch it split open with a juice burst and read your fortune.
4. Tap **New Mango** to get another one.

## Features
- Single-file web app (no build, no dependencies).
- Works on iPad and iPhone in Safari, adds to Home Screen cleanly.
- Banana-print background, wiggling mango, sparkle + juice animation.
- ~30 kid-safe fortunes, easy to expand in `FORTUNES` array.
- Light haptic buzz on supported devices.

## Add to iPad/iPhone Home Screen
1. Open the page in Safari.
2. Tap the Share button → **Add to Home Screen** → name it *Mango Monkey*.
3. It launches full-screen like a native app.

## Local preview
```bash
cd mango-monkey
python3 -m http.server 8080
# then visit http://YOUR_MAC_IP:8080 from the iPad on the same Wi-Fi
```

## Deploy
Drop `index.html` into any static host (GitHub Pages, Vercel, Netlify, Cloudflare Pages). No build step needed.

Made with 🐒 for the Harvey kids.
