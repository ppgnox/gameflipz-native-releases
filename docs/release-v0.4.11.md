# GamePulse v0.4.11

`v0.4.11` focuses on the installer and PresentMon service lifecycle while keeping the feedback, backend, and reliability hardening shipped in `v0.4.4`.

## Download

- Recommended installer: `GamePulse-Friend-Setup-0.4.11.exe`
- Release page: [GamePulse 0.4.11](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.11)

## Highlights

- Fixes the PresentMon setup/repair path so successful setup should not be followed by a duplicate first-launch admin prompt.
- Fixes reinstall handling for existing GamePulse installs so PresentMon setup runs only when needed.
- Fixes uninstall cleanup for the GamePulse-owned PresentMon service and ProgramData payload.
- Adds branded GamePulse setup wizard imagery while keeping the native Windows installer flow.
- Removes the retired LatencyMon note from setup copy; LatencyMon is not part of the current packaged runtime.
- Keeps normal GamePulse startup non-admin; only setup, repair, or uninstall cleanup may ask for Windows admin approval.
- Dev-signed release: SmartScreen / unknown-publisher prompts remain expected until production signing is added.
