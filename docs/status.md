# GamePulse Status And Roadmap

This page keeps the public status clear without turning the README into a changelog.

## Current Public Release

- Latest public release: `v0.4.13`
- Main highlight: public feedback body redaction and PresentMon capture output boundary hardening
- Release page: [GamePulse 0.4.13](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.13)
- Public updater feed: active

## Shipped In v0.4.13

- Public feedback bodies redact GitHub-token, bearer-header, callback-query, and key/value secret-shaped text before publishing.
- PresentMon capture CSV output is kept inside GamePulse runtime data.
- Regression coverage was added for feedback body scrubbing and PresentMon CSV path enforcement.
- Prior v0.4.12 privacy, public-data, auth URL, CSV/export, telemetry, and display-name hardening remains included.
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
