# GamePulse Status And Roadmap

This page keeps the public status clear without turning the README into a changelog.

## Current Public Release

- Latest public release: `v0.4.28`
- Main highlight: Crosshair Studio, UI polish, and Palworld leaderboards
- Release page: [GamePulse 0.4.28](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.28)
- Public updater feed: active

## Shipped In v0.4.28

- Crosshair Studio adds presets, folders, monitor controls, and one saved global toggle while remaining external to games.
- Driver Health and Latency use clearer readiness meters, compact layouts, and review-first guidance.
- Typography, responsive sizing, navigation, Settings, Support, and the V3 startup animation are polished for release.
- Palworld replaces V Rising in the public leaderboard tracker.
- Fair-Play submission handling is more resilient to legitimate imperfect capture evidence.
- Updater identity, install paths, PresentMon repair, telemetry ABI, and user-triggered update behavior remain compatible.

## Known Notes

- Windows SmartScreen may show unknown-publisher prompts because this release is dev-signed, not production-trusted.
- Public leaderboards are opt-in, require Discord sign-in, and require verified Fair-Play evidence to rank.
- In-app feedback is public on GitHub and requires Discord sign-in.
- GamePulse is still evolving quickly, so release notes are the best source for what changed in a specific version.

## Near-Term Roadmap

- Improve production signing and Windows reputation.
- Continue reducing telemetry overhead and making optional diagnostics clearer.
- Keep expanding reviewed game profiles for leaderboard matching.
- Keep refining driver-family matching as more real hardware is tested.
- Add more user-facing install/update troubleshooting guidance as friend testing exposes issues.
