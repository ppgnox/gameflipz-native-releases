# GamePulse v0.4.20

`v0.4.20` fixes an updater edge case where an older downloaded update could install before the newest release was shown.

## Download

- Recommended installer: `GamePulse-Friend-Setup-0.4.20.exe`
- Release page: [GamePulse 0.4.20](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.20)

## Highlights

- Checks the public update feed even when an older update is already staged for restart.
- Shows the newest available release instead of forcing players through unnecessary multi-step updates.
- Download and restart paths choose the newest ready package.
- Adds updater smoke coverage for stale pending packages and version selection.
- Keeps the `v0.4.19` friendly FPS repair prompt and earlier PresentMon/FPS repair safeguards.
- Dev-signed release: SmartScreen / unknown-publisher prompts remain expected until production signing is added.
