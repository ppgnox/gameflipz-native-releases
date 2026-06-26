# GamePulse Status And Roadmap

This page keeps the public status clear without turning the README into a changelog.

## Current Public Release

- Latest public release: `v0.4.22`
- Main highlight: new Benchmark page for baseline-to-comparison performance runs
- Release page: [GamePulse 0.4.22](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.22)
- Public updater feed: active

## Shipped In v0.4.22

- Adds a dedicated Benchmark page for guided baseline-to-comparison run readiness, target lock, live progress, and saved-run review.
- Saves baseline and comparison captures together in one report so setting changes are easier to judge.
- Explains average FPS, low-FPS evidence, frame consistency, and CPU/GPU pressure in player-facing language.
- Keeps benchmark history and public leaderboard sharing under player control.
- Keeps the `v0.4.21` FPS capture cleanup after game close, the `v0.4.20` direct update selection fix, the `v0.4.19` friendly FPS repair prompt, plus prior FPS repair guards, diagnostics, privacy, auth, public-data, feedback, and installer hardening.

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
