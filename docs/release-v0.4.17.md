# GamePulse v0.4.17

`v0.4.17` is an updater-capable FPS helper repair hotfix. It lets GamePulse repair FPS capture through the protected ProgramData helper after Friend Setup has seeded that helper once.

## Download

- Recommended installer: `GamePulse-Friend-Setup-0.4.17.exe`
- Release page: [GamePulse 0.4.17](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.17)

## Highlights

- Lets the updater path repair FPS capture after Friend Setup has seeded the protected helper.
- Allows a stale protected helper to repair the current PresentMon payload only after payload preflight passes.
- Keeps blocking unsafe helper elevation from normal user-writable app folders.
- Makes diagnostics clearer about updater repair capability, bootstrap requirements, selected helper, and preflight status.
- Keeps missing-helper machines on the one-time Friend Setup repair path.
- Dev-signed release: SmartScreen / unknown-publisher prompts remain expected until production signing is added.
