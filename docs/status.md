# GamePulse Status And Roadmap

This page keeps the public status clear without turning the README into a changelog.

## Current Public Release

- Latest public release: `v0.4.25`
- Main highlight: Fair-Play V2.1 verified public leaderboards
- Release page: [GamePulse 0.4.25](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.25)
- Public updater feed: active

## Shipped In v0.4.25

- Default public boards show only verified/ranked Fair-Play V2 rows.
- Public score submits require a server-issued one-use score ticket.
- Low-resolution, unfocused, idle, target-switch, unstable-capture, and weak-evidence sessions do not rank publicly.
- Menu-like or suspicious sessions can be stored for review without appearing on public boards.
- Legacy/unverified leaderboard rows stay stored but are hidden from default public boards.
- Keeps the `v0.4.24` Driver Health Console, Latency page redesign, Store prototype package lane, and prior FPS repair guards, diagnostics, privacy, auth, public-data, feedback, and installer hardening.

## Known Notes

- Windows SmartScreen may show unknown-publisher prompts because this release is dev-signed, not production-trusted.
- Public leaderboards are opt-in, require Discord sign-in, and require verified Fair-Play evidence to rank.
- In-app feedback is public on GitHub and requires Discord sign-in.
- GamePulse is still evolving quickly, so release notes are the best source for what changed in a specific version.

## Near-Term Roadmap

- Improve production signing and Windows reputation.
- Continue reducing telemetry overhead and making optional diagnostics clearer.
- Keep expanding reviewed game profiles for leaderboard matching.
- Evaluate public resolution buckets after real-world Fair-Play V2.1 results.
- Add more user-facing install/update troubleshooting guidance as friend testing exposes issues.
