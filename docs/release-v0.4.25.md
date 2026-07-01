# GamePulse v0.4.25

`v0.4.25` ships Fair-Play V2.1 public leaderboard hardening. Public boards now default to verified ranked rows only, with server-side evidence checks before a score can rank.

## Download Links

- Recommended installer: [GamePulse-Friend-Setup-0.4.25.exe](https://github.com/ppgnox/gameflipz-native-releases/releases/download/v0.4.25/GamePulse-Friend-Setup-0.4.25.exe)
- Release page: [GamePulse 0.4.25](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.25)

## Highlights

- Adds server-issued one-use score tickets before public-ranked submissions.
- Blocks tiny-resolution, unfocused, long-idle, unstable-capture, target-switch, and weak-evidence sessions from public ranking.
- Routes menu-like or suspicious score evidence to review instead of ranking it.
- Keeps legacy public rows stored but hidden from default verified/ranked boards.
- Preserves enough resolution and evidence data to support public resolution buckets later.
- Preserves the external telemetry boundary: no overlays, injection, hooks, game memory access, or game-file changes.
- Dev-signed release: SmartScreen / unknown-publisher prompts are still expected.
