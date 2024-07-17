# voicemeeter-auto-affinity-hidden
<!-- URLS -->
[latest release]:https://github.com/devCKVargas/voicemeeter-auto-affinity-hidden/releases/latest
[latest release direct download URL]:https://github.com/devCKVargas/voicemeeter-auto-affinity-hidden/releases/download/v1.0/install-voicemeeter-fix.ps1

[![Github Downloads all Releases](https://img.shields.io/github/downloads/devCKVargas/voicemeeter-auto-affinity-hidden/total)](https://github.com/devCKVargas/voicemeeter-auto-affinity-hidden/releases)
[![Github Downloads latest Release](https://img.shields.io/github/downloads/devCKVargas/voicemeeter-auto-affinity-hidden/latest/total)](https://github.com/devCKVargas/voicemeeter-auto-affinity-hidden/releases/latest)
[![License](https://img.shields.io/github/license/devCKVargas/voicemeeter-auto-affinity-hidden)](https://github.com/devCKVargas/voicemeeter-auto-affinity-hidden/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/devCKVargas/voicemeeter-auto-affinity-hidden)](https://github.com/devCKVargas/voicemeeter-auto-affinity-hidden/issues)

> [!NOTE]
> The affinity will be set **every hour** instead of every 5 minutes and will now **hide the powershell pop-up**.

- Automatically sets the affinity of "**audiodg.exe**" to only 1 core (**CPU 0**).
  - Fix the crackling noises of VoiceMeeter.

## How to Install

Download & run [install-voicemeeter-fix.ps1][latest release direct download URL]. That's it!

## How to Uninstall

Open command prompt as an administrator and run the following commands:

```bat
schtasks /delete /f /tn audiodg-affinity
schtasks /delete /f /tn audiodg-affinity-recurring
```
