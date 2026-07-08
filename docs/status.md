# GamePulse Status And Roadmap

This page keeps the public status clear without turning the README into a changelog.

## Current Public Release

- Latest public release: `v0.4.27`
- Main highlight: Theme Studio and Overlay Studio customization
- Release page: [GamePulse 0.4.27](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.27)
- Public updater feed: active

## Shipped In v0.4.27

- Theme Studio adds app-wide Dashboard palette presets, saved custom colors, and instant preview updates.
- Overlay Studio adds Compact Mode styling controls while staying outside the game.
- Dashboard Studio and Overlay Studio now sit together in the customization flow.
- Theme switching persists cleaner with less settings churn.
- Private feedback and score-submission ledger tables use explicit service-role-only database policies.
- Keeps the `v0.4.26` Driver Health and Latency controls, `v0.4.25` Fair-Play V2.1 leaderboard hardening, Store prototype source, FPS repair guards, diagnostics, privacy, auth, public-data, feedback, and installer hardening.

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
