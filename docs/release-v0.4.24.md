# GamePulse v0.4.24

`v0.4.24` is the current public GamePulse release. It adds a Driver Health
Console, improves Windows driver update guidance, and redesigns the Latency
page around clearer readiness signals.

## Download Links

- Recommended installer: [GamePulse-Friend-Setup-0.4.24.exe](https://github.com/ppgnox/gameflipz-native-releases/releases/download/v0.4.24/GamePulse-Friend-Setup-0.4.24.exe)
- Release page: [GamePulse 0.4.24](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.24)

## Highlights

- Adds the Driver Health Console with clearer real-device buckets, driver freshness, and safer update guidance.
- Adds the Windows driver update-center flow for selectable driver offers.
- Redesigns the Latency page into a structured console with a pylon hero, readiness summary, attention rows, and aligned Windows checks.
- Fixes latency audit classification so GPU interrupt mode and default display composition report as ready when Windows exposes safe values.
- Adds the Microsoft Store prototype package lane while keeping the normal Friend Setup updater path available.
- Preserves the external telemetry boundary: no overlays, injection, hooks, game memory access, or game-file changes.
- Dev-signed release: SmartScreen / unknown-publisher prompts are still expected.
