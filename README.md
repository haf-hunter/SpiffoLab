# SpiffoLab - Project Zomboid Live Log, Mod Manager & Telemetry Suite

**Official Distribution, Release & Issue Tracker Repository**  
**Author:** Haf Hunter  
**License:** Proprietary Freeware (All Rights Reserved — see [`LICENSE.txt`](LICENSE.txt))

---

## Overview

**SpiffoLab** is a specialized desktop companion suite for **Project Zomboid (Build 42+)** players, modpack curators, and mod authors. It combines real-time log diagnostics, load-order and conflict analysis, JVM/hardware telemetry, and automated crash-cascade protection in a single native Windows application.

### Core Highlights
- **Live Log & Error Cascade Analysis:** Real-time parsing of `console.txt` with root-cause attribution across Lua scripts, Java stacktraces, and mod dependencies.
- **Pre-Flight Mod Manager:** Dependency graph validation, load-order sorting, Workshop integration, and collection snapshots before launching the game.
- **Real-Time Telemetry Dashboard:** Live FPS/frametime histograms, JVM heap/GC monitoring, Lua memory tracking, and zombie/chunk metrics via the bundled `TelemetrieClient` and optional `ZombieBuddyBridge` (ZBB).
- **Automated Crash-Cascade Shield:** Optional bytecode-level protection against broken mod hooks and error-log I/O stalls.

---

## Installation

1. Go to the [**Releases**](https://github.com/haf-hunter/SpiffoLab/releases) page.
2. Download the latest **`SpiffoLab-Setup-vX.Y.Z.exe`** installer.
3. Run the installer and follow the setup wizard:
   - Installs SpiffoLab into your user program directory (`%LOCALAPPDATA%\Programs\SpiffoLab`).
   - Optionally installs/updates the `TelemetrieClient` companion mod directly into `%USERPROFILE%\Zomboid\mods\TelemetrieClient`.
   - Registers Start Menu and Desktop shortcuts as well as a clean Windows Uninstaller entry.

### System Requirements
- **OS:** Windows 10 / Windows 11 (64-bit)
- **Runtime:** [Microsoft .NET 8.0 Desktop Runtime (x64)](https://dotnet.microsoft.com/en-us/download/dotnet/8.0) (the installer checks for this automatically)
- **Game:** Project Zomboid (Build 42 unstable / stable)

---

## Automatic Updates

SpiffoLab checks this repository (`https://api.github.com/repos/haf-hunter/SpiffoLab/releases/latest`) automatically on startup for new releases and offers one-click in-app updates while preserving your personal configuration (`settings.json`).

---

## License & Copyright Notice

**Copyright (c) 2026 Haf Hunter. All Rights Reserved.**

SpiffoLab is distributed as **Proprietary Freeware**, **not** Open Source:
- **Free to Use:** You may download, install, and use SpiffoLab free of charge for private, non-commercial use.
- **No Modification / No Forking:** Modifying, decompiling, reverse engineering, or creating derivative works of the software is strictly prohibited.
- **No Unauthorized Redistribution:** Re-uploading or mirroring the software or its installers on third-party sites or Workshop uploads without written permission is prohibited. Sharing links to this official repository is welcome.

See [`LICENSE.txt`](LICENSE.txt) for the complete End User License Agreement (DE / EN).

