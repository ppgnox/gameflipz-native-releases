# GamePulse v0.4.26

`v0.4.26` upgrades Driver Health and Latency controls with clearer guidance, conservative online driver checks, and explicit reversible Windows tweaks.

## Download Links

- Recommended installer: [GamePulse-Friend-Setup-0.4.26.exe](https://github.com/ppgnox/gameflipz-native-releases/releases/download/v0.4.26/GamePulse-Friend-Setup-0.4.26.exe)
- Release page: [GamePulse 0.4.26](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.26)

## Highlights

- Separates installable driver updates, attention items, real devices, and optional vendor tools.
- Adds clearer GPU, chipset, BIOS, network, audio, and input-driver support actions.
- Keeps NVIDIA online version checks conservative by tying results to the detected product family.
- Falls back to official NVIDIA/vendor guidance when compatibility cannot be proven.
- Expands Latency checks across Windows, input, display, network, service, overlay, and security settings.
- Adds explicit Apply/Revert actions for selected HKCU latency tweaks and restores original values or original absence.
- Preserves the external telemetry boundary: no overlays, injection, hooks, game memory access, or game-file changes.
- Dev-signed release: SmartScreen / unknown-publisher prompts are still expected.
