# Install GamePulse

GamePulse is a self-contained Windows app. You do not need to install .NET or a separate runtime.

## Recommended Download

Download the current friend/tester setup from the latest public release:

[Download GamePulse-Friend-Setup-0.4.22.exe](https://github.com/ppgnox/gameflipz-native-releases/releases/download/v0.4.22/GamePulse-Friend-Setup-0.4.22.exe)

You can also open the release page first:

[GamePulse 0.4.22 release](https://github.com/ppgnox/gameflipz-native-releases/releases/tag/v0.4.22)

## Windows SmartScreen

Windows may show an unknown-publisher SmartScreen prompt. That is expected right now because GamePulse is dev-signed, not signed with a production-trusted certificate. It is a Windows publisher-reputation warning, not a malware detection.

To continue, choose **More info**, then **Run anyway**.

## FPS Capture Setup

GamePulse uses Intel PresentMon and Windows ETW telemetry from outside the game. The installer/update package includes the PresentMon service payload used for no-admin FPS capture setup, repair, and uninstall cleanup.

The app may request a one-time UAC prompt when setting up or repairing that service. Normal app use should stay non-elevated. If an update leaves FPS capture needing repair, GamePulse now explains the issue first and waits for you to choose **Repair now**.

## Updating

Installed builds check this public GitHub release feed. Updates are not silent:

1. Open GamePulse.
2. Go to the **Package** page.
3. Choose **Check for Update**.
4. Download and restart only when you choose to install.

## Uninstalling

Use Windows **Installed apps** / **Apps & features** and uninstall GamePulse from there.

GamePulse keeps local app data under `%LOCALAPPDATA%\GamePulse`. Removing local data is optional and should only be done if you intentionally want to reset settings and saved local history.
