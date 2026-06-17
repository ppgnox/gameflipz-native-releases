<div align="center">

<img src="assets/banner.png" alt="GamePulse" width="560">

### Native Windows performance companion for PC gaming

**Compact Mode | live FPS | frame pacing | Game Health | public leaderboards**

![Latest release](https://img.shields.io/badge/latest-v0.4.4-2ea043)
![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20x64-0078D6)
![Feedback](https://img.shields.io/badge/new-app%20feedback-00d9ff)
![Anti-cheat conservative](https://img.shields.io/badge/no%20overlays%20%2F%20hooks-anti--cheat%20conservative-8957e5)
![Updater](https://img.shields.io/badge/updater-Velopack-2ea043)
[![Signing status](https://img.shields.io/badge/signing-SmartScreen%20prompt%20expected-e3b341)](#is-this-safe-to-run)

[![Download GamePulse for Windows](https://img.shields.io/badge/Download%20GamePulse%200.4.4-Windows%2010%20%2F%2011%20x64-2ea043?style=for-the-badge)](https://github.com/ppgnox/gameflipz-native-releases/releases/download/v0.4.4/GamePulse-Friend-Setup-0.4.4.exe)

[Install](docs/install.md) |
[Screenshots](docs/screenshots.md) |
[Privacy & Safety](docs/privacy-and-safety.md) |
[Status](docs/status.md) |
[Support](docs/support.md) |
[All releases](https://github.com/ppgnox/gameflipz-native-releases/releases)

</div>

---

![GamePulse Compact Mode hero](assets/hero-compact-mode.png)

GamePulse is a lightweight Windows app that shows your real-time gaming performance without becoming a game overlay. It tracks FPS, frame timing, system pressure, game sessions, public leaderboard results, driver readiness, and latency signals from outside the game using native Windows telemetry paths.

Your data stays on your PC unless you choose to share public leaderboard stats.

## New In v0.4.4: Reliability Hardening

`v0.4.4` ships the latest bug-hunt hardening on top of the signed-in feedback and FPS capture work from v0.4.3. It improves session-save ordering, feedback API failure handling, trusted GitHub feedback links, process cleanup, and updater Patch Highlights formatting.

![GamePulse Compact Mode](assets/compact-mode.png)

- Signed-in Discord users can submit bug reports and feature requests from the app.
- Public feedback shows a support ID only; private identity mapping stays in Supabase.
- Supabase score and feedback submissions use atomic quota guards.
- PresentMon service setup verifies bundled payload hashes before elevation.
- Latest hardening preserves newer game sessions during shutdown and tightens feedback/update error handling.
- No overlays, injection, hooks, game memory access, or game-file changes.
- Dev-signed release: SmartScreen / unknown-publisher prompts are still expected.

## Download

**Recommended:** [Download GamePulse-Friend-Setup-0.4.4.exe](https://github.com/ppgnox/gameflipz-native-releases/releases/download/v0.4.4/GamePulse-Friend-Setup-0.4.4.exe)

Prefer to read the notes first? Open [GamePulse 0.4.4](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.4) and download the branded setup from the release assets.

GamePulse is self-contained. You do not need to install .NET separately.

## Feature Highlights

| Area | What it gives players |
| --- | --- |
| Compact Mode | A smaller always-on-top readout for live FPS, CPU, GPU, RAM, VRAM, and game-health context. |
| Performance cockpit | Full dashboard with FPS, frame time, capture health, bottleneck context, and system pressure. |
| Public leaderboards | Opt-in Discord-linked score sharing across supported games and performance boards. |
| Driver and latency checks | Local inventory cards, chipset/GPU guidance, read-only Windows latency checks, and input-stack summaries. |
| Player-controlled diagnostics | CPU/RAM process popups are opt-in and clearly labeled because they use extra CPU while open. |
| Updater support | Installed builds check this public release feed and install only after the user chooses to update. |

## Screenshots

![GamePulse performance leaderboards](assets/leaderboard-public-stats.png)

![GamePulse player-controlled diagnostics](assets/settings-process-popups.png)

More screenshots: [docs/screenshots.md](docs/screenshots.md)

## Is This Safe To Run?

Windows may show **SmartScreen / unknown publisher** when you run the installer. That is expected right now because GamePulse is not yet signed with a production-trusted certificate. It is a Windows publisher-reputation prompt, not a malware detection.

To continue, choose **More info**, then **Run anyway**.

Each release lists hashes for its assets, and installed builds update only from this public GitHub release feed over HTTPS.

## Privacy And Safety

GamePulse is intentionally anti-cheat conservative:

- no game overlay,
- no DLL injection,
- no DirectX/Vulkan/OpenGL hooks,
- no game memory reads or writes,
- no debugger attach,
- no game file modification,
- no kernel driver,
- no hidden background capture behavior.

Public leaderboards are opt-in. Nothing uploads until you sign in and choose to share eligible stats.

Read the full page: [Privacy and Safety](docs/privacy-and-safety.md)

## How Updates Work

GamePulse uses Velopack and this public GitHub repo as the update feed. Updates are not silent:

1. Open GamePulse.
2. Go to the **Package** page.
3. Choose **Check for Update**.
4. Download and restart only when you choose to install.

## Current Notes

- Latest public version: `v0.4.4`.
- **Report a bug** and **Request a feature** submit public GitHub feedback after Discord sign-in.
- Production-trusted signing is planned; SmartScreen prompts remain expected for now.
- Public stats and leaderboards are opt-in.

See: [Status and Roadmap](docs/status.md)

## About This Repository

This is the public release and updater-feed repository for GamePulse. It hosts installer assets, Velopack packages, release metadata, screenshots, and public-facing support docs.

The application source code is maintained separately.

## Social Preview

Use `assets/social-preview.png` for this repository's GitHub social preview image. See [docs/github-social-preview.md](docs/github-social-preview.md).

## License

**Proprietary - Copyright GamePulse. Free for personal use; all rights reserved.**

The published binaries may be downloaded and used at no cost. The source code is not open-source.
