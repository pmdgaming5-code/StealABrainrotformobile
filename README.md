# Brainrot Heist

Offline-first, single-player browser game with 1 human + 7 simulated bots. Original content and systems; no copied game assets.

## Run
Open `index.html` directly in a modern browser. No server, backend, build step, or CDN is required.

## Controls
- Desktop: WASD / arrow keys, mouse drag to orbit camera, wheel to zoom, E to interact.
- Mobile/tablet: virtual joystick and action buttons.
- F1: debug panel.

## Android APK
The `android/` project wraps the same offline web source in a native Android WebView. GitHub Actions builds a debug APK automatically on pushes to `main` using Android Gradle Plugin 9.4.0 and Gradle 9.6.0.

## QA
Run:
`node tests/smoke.cjs`
`node tests/integration.cjs`
