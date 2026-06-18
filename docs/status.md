# GamePulse Status And Roadmap

This page keeps the public status clear without turning the README into a changelog.

## Current Public Release

- Latest public release: `v0.4.12`
- Main highlight: privacy/public-data hardening, auth URL allow-listing, telemetry stability, and display-name cleanup
- Release page: [GamePulse 0.4.12](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.12)
- Public updater feed: active

## Shipped In v0.4.12

- Diagnostics and public feedback text scrub secrets, local paths, and backend details more aggressively.
- Discord sign-in browser launches are restricted to trusted auth URLs.
- CSV/session exports are protected from spreadsheet formulas and oversized public text fields.
- Native telemetry start/stop handling is more stable.
- PresentMon full executable paths are normalized before game matching.
- Oversized legacy runtime migration files are skipped safely.
- Session frame-time averages use valid frame samples.
- Game/process display names are normalized across dashboard, ranks, recent sessions, settings, and public score payloads.
- Prior v0.4.11 installer and PresentMon setup/reinstall/uninstall fixes remain included.

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
