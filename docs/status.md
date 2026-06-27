# GamePulse Status And Roadmap

This page keeps the public status clear without turning the README into a changelog.

## Current Public Release

- Latest public release: `v0.4.23`
- Main highlight: tighter Benchmark targeting and cleaner compact overlays
- Release page: [GamePulse 0.4.23](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.23)
- Public updater feed: active

## Shipped In v0.4.23

- Benchmark now waits for an active game target before naming or starting a run.
- Dashboard and Benchmark are less likely to identify background utility apps as games.
- More reviewed titles show clean player-facing names across Dashboard, Benchmark, saved runs, and exports.
- Compact Dashboard and Benchmark overlays have clearer labels, tighter controls, and a direct close affordance.
- Keeps the `v0.4.22` Benchmark Lab and universal GPU telemetry improvements, plus prior FPS repair guards, diagnostics, privacy, auth, public-data, feedback, and installer hardening.

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
