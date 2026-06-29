# GamePulse Status And Roadmap

This page keeps the public status clear without turning the README into a changelog.

## Current Public Release

- Latest public release: `v0.4.24`
- Main highlight: Driver Health Console and redesigned Latency page
- Release page: [GamePulse 0.4.24](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.24)
- Public updater feed: active

## Shipped In v0.4.24

- Adds the Driver Health Console with clearer real-device buckets, driver freshness, and safer update guidance.
- Adds the Windows driver update-center flow for selectable driver offers.
- Redesigns the Latency page into a structured console with a pylon hero, readiness summary, attention rows, and aligned Windows checks.
- Fixes latency audit classification so GPU interrupt mode and default display composition report as ready when Windows exposes safe values.
- Adds the Microsoft Store prototype package lane while keeping the normal Friend Setup updater path available.
- Keeps the `v0.4.23` Benchmark targeting, compact overlay clarity, cleaner player-facing game names, and prior FPS repair guards, diagnostics, privacy, auth, public-data, feedback, and installer hardening.

## Known Notes

- Windows SmartScreen may show unknown-publisher prompts because this release is dev-signed, not production-trusted.
- Public leaderboards are opt-in and require Discord sign-in.
- In-app feedback is public on GitHub and requires Discord sign-in.
- GamePulse is still evolving quickly, so release notes are the best source for what changed in a specific version.

## Near-Term Roadmap

- Improve production signing and Windows reputation.
- Continue reducing telemetry overhead and making optional diagnostics clearer.
- Keep expanding reviewed game profiles for leaderboard matching.
- Add more user-facing install/update troubleshooting guidance as friend testing exposes issues.
