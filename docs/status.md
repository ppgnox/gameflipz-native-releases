# GamePulse Status And Roadmap

This page keeps the public status clear without turning the README into a changelog.

## Current Public Release

- Latest public release: `v0.4.16`
- Main highlight: protected FPS helper repair hotfix
- Release page: [GamePulse 0.4.16](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.16)
- Public updater feed: active

## Shipped In v0.4.16

- Friend Setup can refresh the protected FPS helper by itself.
- Unsafe writable helper elevation stays blocked.
- Diagnostics include helper-refresh evidence.
- PresentMon fallback cleanup logs are less noisy.
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
