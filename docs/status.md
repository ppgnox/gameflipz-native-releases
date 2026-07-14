# GamePulse Status And Roadmap

This page keeps the public status clear without turning the README into a changelog.

## Current Public Release

- Latest public release: `v0.4.29`
- Main highlight: Smooth small-window and maximized scaling
- Release page: [GamePulse 0.4.29](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.29)
- Public updater feed: active

## Shipped In v0.4.29

- Normal windows scale one stable composition continuously through the supported minimum size.
- Dashboard and Benchmark no longer switch topology or enlarge the FPS meter at the rejected resize thresholds.
- Image and live-preview pages remain edge-to-edge when resized or maximized.
- Dashboard texture-tuning guidance is shorter while its full detail remains available on hover.
- Updater identity, install paths, PresentMon repair, telemetry ABI, and user-triggered update behavior remain compatible with v0.4.28 installs.

## Known Notes

- Windows SmartScreen may show unknown-publisher prompts because this release is dev-signed, not production-trusted.
- Public leaderboards are opt-in, require Discord sign-in, and require verified Fair-Play evidence to rank.
- In-app feedback is public on GitHub and requires Discord sign-in.
- GamePulse is still evolving quickly, so release notes are the best source for what changed in a specific version.

## Near-Term Roadmap

- Improve production signing and Windows reputation.
- Continue reducing telemetry overhead and making optional diagnostics clearer.
- Keep expanding reviewed game profiles for leaderboard matching.
- Keep refining driver-family matching as more real hardware is tested.
- Add more user-facing install/update troubleshooting guidance as friend testing exposes issues.
