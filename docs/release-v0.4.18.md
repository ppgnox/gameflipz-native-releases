# GamePulse v0.4.18

`v0.4.18` is a public FPS capture repair hotfix. It keeps the updater-capable PresentMon repair path from `v0.4.17` and adds guards for unfocused/no-frame game states, no-op service repair, and existing-install setup.

## Download

- Recommended installer: `GamePulse-Friend-Setup-0.4.18.exe`
- Release page: [GamePulse 0.4.18](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.18)

## Highlights

- Stops automatic service repair when a detected game is unfocused or not presenting frames.
- Keeps no-op FPS repair from disrupting an already-running service.
- Rejects common World of Warcraft companion utilities as game targets.
- Keeps locked/captured `Wow.exe` targets from admitting companion utilities as game candidates.
- Adds diagnostics fields showing when no-frame repair was suppressed because the target is unfocused.
- Removes the launch-only bypass from the already-installed setup screen so Update / repair remains the default path.
- Dev-signed release: SmartScreen / unknown-publisher prompts remain expected until production signing is added.
