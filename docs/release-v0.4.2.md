# GamePulse v0.4.2

Compact Mode is the main update in `v0.4.2`: a smaller always-on-top GamePulse widget for active play sessions. It keeps FPS, CPU, GPU, RAM, VRAM, and game-health context visible while the full dashboard stays out of the way.

## Download

- Recommended installer: `GamePulse-Friend-Setup-0.4.2.exe`
- Installed users can update from the in-app Package page.
- The updater feed assets are included in this release for GamePulse's Velopack update flow.

## What's New

- **Compact Mode:** smaller play-session cockpit with live readouts.
- **Counter-Strike 2 support:** added to the built-in game profile list for leaderboard matching.
- **CPU/RAM process popups:** now opt-in, lighter, and can hide GamePulse itself from the process list.
- **Chipset fallback:** Intel and AMD platform fallback copy is clearer when Windows does not list an exact chipset driver.
- **Latency page cleanup:** removed internal/dev-facing text from the release view.
- **Updater package:** includes the bundled PresentMon service payload used for FPS capture setup and repair.

## Safety And Privacy Notes

- GamePulse stays external to games: no overlays, injection, graphics hooks, game memory access, debugger attach, or game file modification.
- Public leaderboards are opt-in.
- Windows SmartScreen unknown-publisher prompts are still expected until production-trusted signing is configured.
- **Report a bug** is visible in the app, but it is not connected yet. Feedback wiring is planned for a later update.

## More Info

- Public homepage: https://github.com/ppgnox/gameflipz-native-releases
- Install guide: https://github.com/ppgnox/gameflipz-native-releases/blob/main/docs/install.md
- Screenshots: https://github.com/ppgnox/gameflipz-native-releases/blob/main/docs/screenshots.md
- Privacy and safety: https://github.com/ppgnox/gameflipz-native-releases/blob/main/docs/privacy-and-safety.md
