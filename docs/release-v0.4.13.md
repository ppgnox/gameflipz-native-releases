# GamePulse v0.4.13

`v0.4.13` focuses on public feedback body redaction and PresentMon capture output boundary hardening while keeping the app workflow and native layout unchanged.

## Download

- Recommended installer: `GamePulse-Friend-Setup-0.4.13.exe`
- Release page: [GamePulse 0.4.13](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.13)

## Highlights

- Redacts GitHub-token, bearer-header, callback-query, and key/value secret-shaped text before public feedback bodies are published.
- Keeps PresentMon capture CSV output inside GamePulse runtime data instead of honoring arbitrary external CSV paths.
- Adds regression coverage for feedback body scrubbing and PresentMon CSV path enforcement.
- Keeps prior v0.4.12 privacy, public-data, auth URL, CSV/export, telemetry, and display-name hardening.
- Dev-signed release: SmartScreen / unknown-publisher prompts remain expected until production signing is added.
