# Privacy And Safety

GamePulse is built as an external Windows performance companion. The goal is useful gaming telemetry without hidden capture behavior or anti-cheat-sensitive techniques.

## What GamePulse Does Not Do

- No game overlay.
- No DLL injection.
- No DirectX, Vulkan, or OpenGL hooks.
- No game memory reads or writes.
- No debugger attach.
- No game file modification.
- No kernel driver.
- No anti-cheat bypass.
- No ads or tracking telemetry.

## Local Data

GamePulse stores local settings and history under `%LOCALAPPDATA%\GamePulse`.

Legacy GAME FLIPZ native data may be copied forward from `%LOCALAPPDATA%\GAME FLIPZ\Native` without deleting the old files.

## Public Stats

Public leaderboards are opt-in. Nothing is submitted to public boards until the player signs in and chooses to share eligible stats. Public ranking also requires verified Fair-Play evidence; low-evidence, low-resolution, idle, unfocused, unstable, or review/quarantine sessions do not appear on default public boards.

When public stats are used, GamePulse may submit:

- selected performance/session results,
- the reviewed game/profile key,
- display name and avatar information used for leaderboard presentation.

GamePulse should not expose Discord access tokens, refresh tokens, or raw Discord user IDs in public leaderboard data.

## Process Diagnostics

CPU/RAM process popups are opt-in. They sample local Windows process metrics only while open, and the Settings page warns that this uses extra CPU while active.

## Updates

Installed builds check the public GitHub release feed. Updates are downloaded and installed only after the user chooses that action in the app.

## Signing Status

Current public artifacts may still trigger Windows SmartScreen unknown-publisher prompts. Production-trusted signing is planned, but not configured yet.
