# GamePulse v0.4.12

`v0.4.12` focuses on privacy, public-data, auth-launch, telemetry, and display-name hardening while keeping the app workflow and native layout unchanged.

## Download

- Recommended installer: `GamePulse-Friend-Setup-0.4.12.exe`
- Release page: [GamePulse 0.4.12](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.12)

## Highlights

- Hardens diagnostics and public feedback text so secrets, local paths, and backend details are scrubbed before public submission.
- Tightens Discord sign-in browser launch handling with a strict trusted auth URL allow-list.
- Protects CSV/session exports from spreadsheet formulas and oversized public text fields.
- Fixes a native telemetry start/stop race and normalizes full PresentMon process paths before game matching.
- Caps oversized legacy runtime migration files and keeps frame-time averages based on valid frame samples.
- Normalizes game/process display names across dashboard, ranks, recent sessions, settings, and public score payloads.
- Dev-signed release: SmartScreen / unknown-publisher prompts remain expected until production signing is added.
