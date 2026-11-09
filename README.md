# PlayGround

<!-- omgithub:readme:start -->
## 🚀 Build, play, and remix with OMGithub

**Created using [OMGithub.com](https://go.ondev.store/).**

[![OMGithub](https://img.shields.io/badge/OMGithub-Open%20project-orange?style=for-the-badge)](https://go.ondev.store/LeoV1997/PlayGround)
[![GitHub](https://img.shields.io/badge/GitHub-Source-181717?logo=github&style=for-the-badge)](https://github.com/LeoV1997/PlayGround)

- 🎮 [Open the project](https://go.ondev.store/LeoV1997/PlayGround).
- ✨ [Remix this project](https://go.ondev.store/LeoV1997/PlayGround?remix=1).
- 💻 [Explore the source](https://github.com/LeoV1997/PlayGround).
- 🛠️ [Check build runs](https://github.com/LeoV1997/PlayGround/actions).
- 🐛 [Report an issue](https://github.com/LeoV1997/PlayGround/issues).
- 👤 [Explore the creator's projects](https://go.ondev.store/LeoV1997).
- 🌍 [Create with OMGithub](https://go.ondev.store/).
<!-- omgithub:readme:end -->

## Run locally

This prototype is a static browser game. From the project directory, start a local web server:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in a modern browser. Your progress is saved in that browser's local storage; offline rewards are calculated on the next visit and capped at 8 hours.

## Prototype limitations

The game uses a canvas-rendered 2D combat scene rather than 3D graphics. Android packaging, Google Play Billing, advertising, and server-backed saves are not connected. Shop products are informational only, and the local save is not protected against editing.
