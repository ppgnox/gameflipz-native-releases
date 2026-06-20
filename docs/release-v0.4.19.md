# GamePulse v0.4.19

`v0.4.19` makes FPS capture repair clearer after updates. If the Windows capture helper needs attention, GamePulse now explains the repair path before asking for Windows approval.

## Download

- Recommended installer: `GamePulse-Friend-Setup-0.4.19.exe`
- Release page: [GamePulse 0.4.19](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.19)

## Highlights

- Adds a friendly repair prompt when FPS capture needs one Windows repair step after an update.
- `Repair now` uses the protected local helper when available.
- If the protected helper is missing, `Repair now` downloads and verifies the official Friend Setup repair tool before launching it.
- `Not now` opens the app and clearly warns that live FPS and frame-time capture may stay `N/A` until repair is completed.
- Stops installed startup from silently requesting PresentMon repair; Windows approval now follows the user's `Repair now` choice.
- Keeps the helper safety boundary intact: no elevation from updater-local writable helper paths.
- Dev-signed release: SmartScreen / unknown-publisher prompts remain expected until production signing is added.
