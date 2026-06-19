# GamePulse Status And Roadmap

This page keeps the public status clear without turning the README into a changelog.

## Current Public Release

- Latest public release: `v0.4.17`
- Main highlight: updater-capable protected FPS helper repair
- Release page: [GamePulse 0.4.17](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.17)
- Public updater feed: active

## Shipped In v0.4.17

- The updater path can repair FPS capture after Friend Setup seeds the protected helper.
- Stale protected helpers are used only after payload preflight passes.
- Unsafe writable helper elevation stays blocked.
- Diagnostics include updater repair capability, bootstrap status, selected helper, and preflight status.
- Missing protected-helper machines still need Friend Setup once.
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
