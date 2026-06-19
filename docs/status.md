# GamePulse Status And Roadmap

This page keeps the public status clear without turning the README into a changelog.

## Current Public Release

- Latest public release: `v0.4.15`
- Main highlight: FPS capture repair follow-up with stronger diagnostics
- Release page: [GamePulse 0.4.15](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.15)
- Public updater feed: active

## Shipped In v0.4.15

- PresentMon Service can be restarted during FPS capture repair.
- Ready-but-zero-frame capture states can trigger bounded app-side repair.
- Native capture reconnects after FPS service readiness changes.
- Failed setup/app repair attempts can be retried instead of getting stuck.
- Diagnostics include detection, PID, helper, and startup repair clues.
- Prior privacy, auth, public-data, feedback, and installer hardening remains included.

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
