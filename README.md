Entrena Fuerte - PWA prototype
=============================

Contenido:
- Vite + React minimal project
- src/App.jsx: main prototype (React component)
- manifest.json + service-worker.js included for PWA features
- icons/EF-icon-*.png : launcher icons

Quick start (recommended on PC or cloud IDE):
1. npm install
2. npm run dev
3. Open the local URL (Vite will show it)
4. For production build: npm run build and deploy the `dist` folder

Notes for mobile-only users:
- You can upload the ZIP to Vercel by creating a new project and selecting "Upload" (Vercel supports drag & drop of folders/zip from mobile browser in modern mobile browsers).
- Alternatively, use a Git provider or a desktop later.

PWA specifics:
- manifest.json defines how the app installs.
- service-worker.js implements basic cache-first offline support.

If you want, I can next:
- Deploy this for you to a temporary hosting so you can test immediately.
- Or guide you step-by-step to upload to Vercel from your mobile.
