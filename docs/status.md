# GamePulse Status And Roadmap

This page keeps the public status clear without turning the README into a changelog.

## Current Public Release

- Latest public release: `v0.4.3`
- Main highlight: signed-in feedback plus source/backend hardening
- Release page: [GamePulse 0.4.3](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.3)
- Public updater feed: active

## Shipped In v0.4.3

- Signed-in Discord feedback submission from the app.
- Bug reports create public GitHub issues; feature requests create public Ideas discussions.
- Public feedback shows a GamePulse support ID only; private submitter mapping stays in Supabase.
- Atomic Supabase quota guards for score and feedback submission.
- PresentMon setup uses verified helper/payload files for elevated service install/repair.
- PresentMon CLI fallback start/stop work no longer blocks the WPF UI thread.

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
