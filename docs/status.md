# GamePulse Status And Roadmap

This page keeps the public status clear without turning the README into a changelog.

## Current Public Release

- Latest public release: `v0.4.14`
- Main highlight: FPS capture repair plus Discord/auth and public-data boundary hardening
- Release page: [GamePulse 0.4.14](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.14)
- Public updater feed: active

## Shipped In v0.4.14

- PresentMon Service repair is improved for broken FPS capture cases after install or update.
- Elevated FPS helper results are reported more clearly when capture setup needs repair.
- Discord auth and session boundaries are hardened without changing the sign-in workflow.
- Public feedback and public-data paths redact more secret-shaped text before publication.
- Prior privacy, public-data, feedback, capture-output, and installer hardening remains included.

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
