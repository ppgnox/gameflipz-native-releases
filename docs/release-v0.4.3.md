# GamePulse v0.4.3

`v0.4.3` connects signed-in app feedback and ships the source/backend hardening line that was tested after `v0.4.2`.

## Download

- Recommended installer: `GamePulse-Friend-Setup-0.4.3.exe`
- Release page: [GamePulse 0.4.3](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.3)

## Highlights

- Signed-in Discord users can submit bug reports and feature requests from GamePulse.
- Bugs create public GitHub issues; feature requests create public Ideas discussions.
- Public feedback shows a `GamePulse support ID` only, while private submitter mapping stays in Supabase.
- Feedback has conservative free-tier protections: per-user caps, a global daily cap, and a backend kill switch.
- Supabase score and feedback submissions use atomic quota reservations.
- PresentMon service install/repair verifies bundled payload hashes before elevation.
- PresentMon CLI fallback start/stop work no longer blocks the WPF UI thread.
- Native telemetry, diagnostics, Discord auth URL handling, HTTP client lifecycle, and runtime-data migration paths were hardened.
- LatencyMon app/runtime packaging was removed; the local Windows latency audit remains.

## Signing Note

This build is dev-signed, not production-trusted. Windows SmartScreen / unknown-publisher prompts are expected until production signing is configured.
