# GamePulse v0.4.21

`v0.4.21` is a post-game FPS capture cleanup release. It reduces stale capture state after a game closes, so GamePulse is less likely to prompt for repair when the session is already over.

## Download

- Recommended installer: `GamePulse-Friend-Setup-0.4.21.exe`
- Release page: [GamePulse 0.4.21](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.21)

## Highlights

- Reduces unnecessary FPS capture repair prompts after a game closes.
- Clears stale capture targets when the active game has ended.
- Keeps new sessions from inheriting old capture state.
- Improves post-game session cleanup so stale FPS samples are not saved after exit.
- Adds regression coverage around game close, retargeting, repair restart, and session cleanup.
- Dev-signed release: SmartScreen / unknown-publisher prompts remain expected until production signing is added.
