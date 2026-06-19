# GamePulse Status And Roadmap

This page keeps the public status clear without turning the README into a changelog.

## Current Public Release

- Latest public release: `v0.4.18`
- Main highlight: safer FPS capture repair and already-installed setup flow
- Release page: [GamePulse 0.4.18](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.18)
- Public updater feed: active

## Shipped In v0.4.18

- Stops automatic service repair when a detected game is unfocused or not presenting frames.
- Keeps no-op PresentMon helper repair from stopping an already-running service when payload hashes match.
- Rejects common World of Warcraft companion utilities as game targets.
- Keeps locked/captured `Wow.exe` targets from admitting companion utilities as game candidates.
- Removes the launch-only bypass from the already-installed setup screen so Update / repair remains the default path.
- Keeps prior updater-capable helper repair, diagnostics, privacy, auth, public-data, feedback, and installer hardening.

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
