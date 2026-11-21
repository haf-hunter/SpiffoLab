# SpiffoLab CC — Public Changelog

Player-focused summary of notable updates for **SpiffoLab CC** (Project Zomboid Build 41 & Build 42).  
For downloads and installation instructions, see [README.md](README.md). For upcoming plans, see [ROADMAP.md](ROADMAP.md).

---

## v2.5.2 (2026-11-21)
- **Self-Contained Windows Installer:** `SpiffoLab-Setup.exe` now bundles everything needed out of the box — no external `.NET` runtime download required.
- **Per-Profile External Optimizer Preservation:** Third-party performance setups (such as `pzopt` / Java AOT caches) are now safely preserved per profile when switching profiles or game builds.
- **More Accurate Zombie AI & Benchmark Advice:** Zombie AI telemetry now measures total AI load per frame, and the 30-second Benchmark highlights Zombie AI, Chunk, and Collision spikes with practical tips.
- **Polished Tuning Tab & Floating Tooltips:** Clear active preset highlight, cleaner graphics advice text, and metric tooltips that never clip at window edges.
- **In-Game Setup Prompt Hotfix (Workshop Mod):** Fixed the in-game "Open Download" button not launching the browser and added missing translations (DE, EN, ES, PT-BR).

## v2.5.1 (2026-11-21)
- **Live GPU Load & Dedicated VRAM:** Reliable real-time GPU usage tracking plus a dedicated VRAM metric card with accurate 64-bit GPU memory detection.
- **Clean Idle Reset & Unified Colors:** All live metrics and charts reset cleanly to `--` when the game is not running, with consistent theme colors and dynamic FPS-cap scaling.
- **Automatic Conflict Detection:** Detects third-party JVM/AOT optimizers automatically and warns before applying conflicting settings.

## v2.5.0 (2026-11-20)
- **New `TUNING` Tab:** 1-click performance presets tailored to your PC memory, granular Java tuning toggles, easy Java/GraalVM switching, and live graphics settings advice.

## v2.4.0 – v2.4.1 (2026-11-20)
- **In-App Game Build Downloader:** Download archived Project Zomboid builds (B42 back to 2013 Build 19) directly inside SpiffoLab with live progress and Steam Guard support.
- **Safer Profile Switching:** Checks for unsaved mod changes, preserves custom Java runtimes per profile, and displays a clean loading overlay during build switches.
- **Refreshed Loading Branding & Full Translations:** Updated splash branding and completed 4-language coverage across dialogs.

## v2.3.0 – v2.3.4 (2026-11-18 – 2026-11-19)
- **4 Built-In Color Themes:** Choose between `Dark Purple`, `Light Blue`, `Rainbow Dark`, and `Rainbow Light`.
- **Full 4-Language Support:** Complete English, German, Spanish, and Portuguese UI, dialogs, and diagnostic reports.
- **Cleaner Mod Manager & Live Log:** Unified badges, faster mod filtering, and smoother auto-scrolling during heavy log bursts.

## v2.0.0 – v2.1.6 (2026-11-17)
- **Signed Automatic In-App Updates:** Seamless one-click updates via signed `.slupd` packages after the initial Windows installer setup.
- **Guided 5-Step Setup Wizard & Workshop Companion:** Smooth first-time setup and automatic detection of Project Zomboid and installed mods.
