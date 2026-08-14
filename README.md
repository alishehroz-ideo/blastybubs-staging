# BlastyBubs — WebGL staging build (GameBull)

Staging deploy of the BlastyBubs WebGL build, served via GitHub Pages.

- **Play:** https://alishehroz-ideo.github.io/blastybubs-staging/
- Unity 6000.4.3f1 · WebGL · IdeofuzionBridge template · 1080x1920 portrait
- GameBull API: `https://api.staging.g-b.store`
- GameBull lobby canvas lives in `scn_boot` (DontDestroyOnLoad), shows in `scn_game`.
- Single-scene gameplay: `gameplaySceneName` is empty; runs start via `onStartSolo`.
- Score submission + game-end panel via `GameBullBlastyBridge`.
