# GamePulse v0.4.15

`v0.4.15` is an FPS capture repair follow-up for cases where the PresentMon Service is installed but still not delivering frame samples.

## Download

- Recommended installer: `GamePulse-Friend-Setup-0.4.15.exe`
- Release page: [GamePulse 0.4.15](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.15)

## Highlights

- Restarts PresentMon Service during FPS capture repair.
- Auto-repairs ready FPS service when game frames stay at zero.
- Reconnects native capture after FPS service readiness changes.
- Retries FPS repair when setup/app repair leaves service broken.
- Adds clearer capture and repair context to diagnostics.
- Dev-signed release: SmartScreen / unknown-publisher prompts remain expected until production signing is added.
