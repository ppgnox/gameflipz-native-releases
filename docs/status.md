# GamePulse Status And Roadmap

This page keeps the public status clear without turning the README into a changelog.

## Current Public Release

- Latest public release: `v0.4.2`
- Main highlight: Compact Mode
- Release page: [GamePulse 0.4.2](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.2)
- Public updater feed: active

## Shipped In v0.4.2

- Compact Mode for a smaller always-on-top play-session widget.
- Opt-in CPU/RAM process popups with an option to include or hide GamePulse itself.
- Counter-Strike 2 built-in game profile support for leaderboard matching.
- Clearer Intel/AMD chipset fallback when Windows does not list an exact chipset driver.
- Cleaner Latency page copy and fewer internal/dev-facing messages.
- PresentMon service payload included for FPS capture setup and repair.

## Known Notes

- **Report a bug** is visible in the app, but it is not connected yet.
- Windows SmartScreen may show unknown-publisher prompts until production-trusted signing is configured.
- Public leaderboards are opt-in and require Discord sign-in.
- GamePulse is still evolving quickly, so release notes are the best source for what changed in a specific version.

## Near-Term Roadmap

- Wire the in-app bug report flow to the support backend.
- Improve production signing and Windows reputation.
- Continue reducing telemetry overhead and making optional diagnostics clearer.
- Keep expanding reviewed game profiles for leaderboard matching.
- Add more user-facing install/update troubleshooting guidance as friend testing exposes issues.
