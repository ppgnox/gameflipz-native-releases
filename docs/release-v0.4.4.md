# GamePulse v0.4.4

`v0.4.4` ships the latest bug-hunt hardening on top of the feedback, backend, and PresentMon service work from `v0.4.3`.

## Download

- Recommended installer: `GamePulse-Friend-Setup-0.4.4.exe`
- Release page: [GamePulse 0.4.4](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.4)

## Highlights

- Fixed a shutdown race so the latest game session is not overwritten by an older background save.
- Hardened feedback submission result recording after GitHub side effects.
- Added cheaper fake/oversized bearer-token rejection for backend feedback, score, and deletion requests.
- Added bounded GitHub response parsing, timeouts, and clearer try-later handling for feedback.
- Tightened trusted feedback URLs to exact issue or discussion links in the feedback repo.
- Preserved updater release-note line breaks so Patch Highlights stay readable in the app.
- Hardened process scanning, process-handle disposal, background command errors, and PresentMon payload validation tests.
- Dev-signed release: SmartScreen / unknown-publisher prompts remain expected until production signing is added.
