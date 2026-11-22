# SpiffoLab CC — Changelog

Complete version history for **SpiffoLab CC** (originally launched as *PZLogMonitor*) for Project Zomboid Build 41 & Build 42.  
For downloads and installation instructions, see [README.md](README.md). For upcoming plans, see [ROADMAP.md](ROADMAP.md).

---

## v2.5.5 (2026-11-22)
- **Critical Build 42 Main Menu Fix (Companion Mod):** Fixed a Lua Mod Options error in `SpiffoLab_Onboarding.lua` that could block the Project Zomboid Build 42 main menu from loading on fresh installations. Now uses native `PZAPI.ModOptions:addButton` with full `pcall` safety guards.
- **Build 41 Companion Mod Polish:** Synced the improved download prompt (`openURl` browser launch + centered buttons) and added missing DE/EN/ES/PT-BR translations to all Build 41 `UI_*.txt` files.

## v2.5.4 (2026-11-22)
- **Instant External Optimizer Memory Settings on First Launch:** Switching profiles alongside external performance tools (such as `pzopt`) now preserves custom `-Xms`, `-Xmx`, and `-XX:+AlwaysPreTouch` settings right away — no second game launch required.
- **Cleaner Launch Configs:** Prevents stale profile memory flags from overriding an active external optimizer, keeps external settings intact when selecting SpiffoLab's `Default (Off)` tuning preset, and removes duplicate JVM unlock flags automatically.

## v2.5.3 (2026-11-22)
- **External AOT Optimizer Conflict Guard:** Prevents Java 25 startup aborts when switching profiles or launching alongside external AOT optimizers (such as `pzopt`), and automatically heals affected launch configs.
- **In-Game Setup Prompt & Mod Poster Update:** Fixed the in-game "Open Download" button not opening the browser, completed all DE/EN/ES/PT-BR prompt translations, and refreshed the mod poster with a clear `B41 & B42` badge.

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

## v2.2.0 (2026-11-18)
- **Offline `NoSteam` Launch Mode:** Launch Project Zomboid directly without Steam (`-nosteam`), including a 1-click fallback prompt if Steam is not running.

## v2.0.0 – v2.1.6 (2026-11-16 – 2026-11-17)
- **Signed Automatic In-App Updates:** Seamless one-click updates via cryptographically verified `.slupd` packages after initial installation.
- **Guided 5-Step Setup Wizard & Workshop Companion:** Smooth first-time setup, Steam health checks, and automatic detection of Project Zomboid and installed mods.

## v1.45.0 – v1.47.0 (2026-11-14 – 2026-11-15)
- **Isolated Launcher Profiles & Profile Wizard:** Run completely separate Solo, Testing, and Multiplayer setups with isolated save/config folders (`-cachedir`) and custom Java runtimes.
- **Mod Update Locks & Workshop Grouping:** Lock individual mods or multi-mod Workshop packs against updates, browse local rollback snapshots, and review Steam changelogs before updating.
- **Windows Installer & Clean Uninstaller:** Dedicated Windows setup with opt-in shortcuts and a clean uninstaller that safely removes Steam update locks on uninstall.

## v1.40.0 – v1.44.0 (2026-11-10 – 2026-11-14)
- **Pre-Flight Mod Manager (`LAUNCHER` Tab):** Visual mod list with thumbnails, load-order sorting, active/inactive toggles, and pre-launch integrity checks.
- **Automatic Local Mod Freeze & Rollback:** Protects subscribed Workshop mods locally so forced Steam updates never break an active savegame.
- **24-Build Game Archive & Steam Update Locks:** Bundled archived manifests covering Build 19 (2013) through Build 42 with isolated build switching and optional Steam game/workshop update locks.
- **Build 42 Workshop Discovery Showcase:** Browse curated Build 42 Workshop picks (*For you*, *Popular*, *Newest*) right inside the launcher.

## v1.35.0 – v1.39.0 (2026-11-07 – 2026-11-10)
- **Automatic Update Checker & Setup Wizard:** Built-in update notifications and guided first-time configuration.
- **1-Click Companion Mod & ZombieBuddy Setup:** Automated health check and one-click installation of the in-game telemetry companion with non-destructive config backups.
- **Frame-Budget Dashboard & Rule-Based Advisor:** Measures per-mod frame cost against a 60 FPS (16.6 ms) budget, separates steady load from one-off spikes, and generates actionable optimization advice.

## v1.28.0 – v1.34.0 (2026-10-31 – 2026-11-06)
- **Error & Runtime Cascade Analysis:** Identifies root-cause mods behind multi-mod crash chains and frame-spike domino effects.
- **30-Second Benchmark Cockpit HUD:** Live in-game countdown overlay tracking FPS, frame-budget spikes, CPU, GPU, and RAM with real-time bar charts.
- **Modern Exportable HTML Diagnostic Report:** Shareable visual performance and error reports with charts for Discord or bug tracking.
- **High-Resolution Mod & Engine Profiling:** Microsecond-level Lua profiling plus engine timing hooks for main logic, rendering, Zombie AI, chunk streaming, and map collision (Build 41 & Build 42).

## v1.22.0 – v1.27.0 (2026-09-22 – 2026-10-04)
- **Live System & Graphics Telemetry:** Added real-time FPS, 1% / 0.1% Low FPS, GPU load, frame jitter, and heap memory monitoring.
- **First Diagnostic Reports & Global Hotkeys:** Exportable session summaries and keyboard shortcuts for quick benchmarking while playing.

## v1.8.0 – v1.14.0 (2026-09-19 – 2026-09-20)
- **First Mod Performance Evaluation Dashboard:** Introduced the dedicated dashboard view to rank mods by runtime cost, errors, and memory usage.
- **Companion Mod Integration (`TelemetrieClient`):** Connected the desktop app to the in-game Java telemetry companion for live per-mod profiling.
- **Themes, Persistent Settings & Built-In Help:** Added Dark/Light mode switching, saved user preferences, sortable tables, and in-app help documentation.

## v1.2.0 – v1.7.4 (2026-09-17 – 2026-09-19)
- **Launch & Stop Project Zomboid from the App:** Start and cleanly close the game directly from the monitor window.
- **Log Search, Filtering & Quick Copy:** Added live search, severity filters, lag log reset on startup, and one-click copy of selected log lines.

## v1.0.2 – v1.1.8 (2026-09-12 – 2026-09-15)
- **Initial Release (`PZLogMonitor.exe`, 219 KB):** The very first version — a lightweight, non-blocking real-time viewer for Project Zomboid's `console.txt` with live error highlighting and early Lua bridge experiments.
