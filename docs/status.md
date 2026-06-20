# GamePulse Status And Roadmap

This page keeps the public status clear without turning the README into a changelog.

## Current Public Release

- Latest public release: `v0.4.19`
- Main highlight: friendly FPS capture repair prompt after updates
- Release page: [GamePulse 0.4.19](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.19)
- Public updater feed: active

## Shipped In v0.4.19

- Shows a friendly in-app prompt when FPS capture needs one repair step after an update.
- Uses the protected local helper when available.
- Downloads and verifies the official Friend Setup repair tool when the protected helper is missing.
- Warns clearly when the player chooses `Not now` so FPS/frame-time `N/A` is expected until repair is completed.
- Stops installed startup from silently requesting repair before the player chooses `Repair now`.
- Keeps prior FPS repair guards, diagnostics, privacy, auth, public-data, feedback, and installer hardening.

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
