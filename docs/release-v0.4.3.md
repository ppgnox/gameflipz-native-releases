# GamePulse v0.4.3

`v0.4.3` connects signed-in app feedback and ships the source/backend hardening line that was tested after `v0.4.2`.

## Download

- Recommended installer: `GamePulse-Friend-Setup-0.4.3.exe`
- Release page: [GamePulse 0.4.3](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.3)

## Highlights

- Signed-in Discord users can submit bug reports and feature requests from GamePulse.
- Bugs create public GitHub issues; feature requests create public Ideas discussions.
- Public feedback shows a `GamePulse support ID` only, while private submitter mapping stays in Supabase.
- Feedback has conservative submission limits and a backend safety switch.
- Score and feedback submissions handle usage limits more reliably.
- FPS capture setup and repair validate bundled components before requesting elevation.
- FPS capture repair work no longer blocks the app UI.
- Native telemetry, diagnostics, sign-in URL handling, networking, and local-data migration paths were hardened.
- LatencyMon app/runtime packaging was removed; the local Windows latency audit remains.

## Signing Note

This build is dev-signed, not production-trusted. Windows SmartScreen / unknown-publisher prompts are expected until production signing is configured.
