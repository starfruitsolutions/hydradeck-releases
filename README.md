# Hydradeck

**One deck for all your coding agents, on your own machine or any SSH host.**

Run Claude Code, Codex, Cursor and Copilot side by side and see at a glance which ones are working,
which are waiting on you and which are done. Your terminals live on the host, not in the app, so
they keep running when you close the laptop, lose the connection or update Hydradeck.

This repository holds Hydradeck's downloads. The source code is not published here.

## Download

Get the newest build from [Releases](https://github.com/starfruitsolutions/hydradeck-releases/releases).

| Platform | File | Updates |
| --- | --- | --- |
| Windows | `Hydradeck-Setup-x.y.z.exe` | Automatic |
| Linux | `Hydradeck-x.y.z.AppImage` | Automatic |
| Debian / Ubuntu | `hydradeck_x.y.z_amd64.deb` | Install the newer `.deb` |

The other files on each release (`latest.yml`, `latest-linux.yml`, `.blockmap`) are what the app
reads to update itself; you don't need them.

The Windows installer isn't code-signed, so SmartScreen warns about an unknown publisher the first
time. Choose **More info**, then **Run anyway**.

## Updates

The Windows installer and the AppImage check for a new version when Hydradeck starts and every few
hours after. It downloads in the background, and the status bar then offers to restart into it.

## Requirements

Hydradeck connects to a host that runs your agents: Linux (glibc 2.28+) or macOS, x64 or arm64.
Remote hosts use your normal SSH setup. On Windows, the local host is WSL.

## License

Copyright © Starfruit Solutions. All rights reserved. The downloads here are provided for use as
they are; they may not be redistributed or modified.
