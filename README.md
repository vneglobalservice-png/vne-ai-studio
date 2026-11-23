# VNE AI Studio — zero-budget starter

## Included
- Responsive multilingual website prototype (English, Telugu, Hindi, Spanish, French, Arabic)
- Local photo preview and demo filters (browser effects, not AI)
- PWA manifest, offline cache and app icons
- Android install path: install the website as a PWA from Chrome, giving an app-like icon without an APK or Play Store listing fee.

## Free-first publishing path
1. Create a GitHub account and a public repository.
2. Upload all files in this folder.
3. Enable GitHub Pages for the repository (HTTPS hosting).
4. Open the HTTPS website in Android Chrome.
5. Choose Chrome menu > Install app / Add to Home screen.

## Limitations
This is a starter prototype, not a production AI product. Photo preview filters run locally; real AI generation, background removal, upscaling, accounts, cloud storage, payments, ads, moderation and admin tools are not connected. GitHub Pages is static hosting and cannot safely store API keys or run a private backend. A native APK / Play Store release needs Android build tooling, testing, signing and developer registration; the PWA is the zero-cost first step. Free AI quotas can change. Never put private API keys in website JavaScript. Displayed prices are examples only.

## Next phase
Add a server-side API proxy and connect AI photo services with quotas, upload limits, privacy controls and moderation. Keep all API keys on the server.
