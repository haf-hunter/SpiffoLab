# SpiffoLab CC — Changelog

Complete version history for **SpiffoLab CC** (originally launched as *PZLogMonitor*) for Project Zomboid Build 41 & Build 42.  
For downloads and installation instructions, see [README.md](README.md). For upcoming plans, see [ROADMAP.md](ROADMAP.md).

---

## v2.10.0 (2026-11-26) — Make Your Own Lab
- **Custom Theme Studio (5 Independent Color Layers & HSV Color Wheel):** Customize **Background**, **Main Panels**, **Sub-Areas & Fields**, **Accent Color**, and **Text Color** independently. Switch cleanly between curated 4-dark / 4-light **Color Presets** and a native interactive **HSV Color Wheel** with brightness control, `#RRGGBB` hex input, live WCAG contrast checks (`AA` / `AAA`), one-click resets, and saveable custom theme presets.
- **Curated Fonts, Free `80% – 150%` UI Scaling & System-Wide Theme Sync:** Pick your preferred UI font family, scale both the app chrome and embedded views freely in `5%` steps from `80%` to `150%` with a 5-layer live preview, enjoy matching Windows 11 title bars and borders on every window/dialog, and carry your theme everywhere (`Live Log`, `Mod-Radar`, `Metrics`, `Help Center`, and exported HTML diagnostic reports).
- **Responsive Header & Active Highlight Across All Views:** The header automatically switches to a compact navigation dropdown on narrower screens or high zoom (`120%–150%`) without squeezing game controls, and the active accent highlight now covers `?` (**Help Center**) and the gear icon (**Settings**) too — alongside cleaner Settings sections with prominent **Maintenance, Updates & System** cards.
- **Collapsible Live Log Sidebar & `MOD-RADAR` Rename:** Collapse **Mod Rank** and **Lag Spikes** individually (`▾`/`▸` with live counts) or hide the whole sidebar for full-width logs (`Sidebar »`). Renamed `Dashboard` to **`MOD-RADAR`** / **`Mod-Radar`** and updated Help Center chapters across all 4 languages (`EN`, `DE`, `ES`, `PT`).

## v2.9.0 (2026-11-25)
- **New `START` Tab Command Center:** Dedicated launchpad left of `LAUNCHER` featuring a compact grunge-smoke hero banner (`Dark` & `Light` theme variants with theme-bound localized subtitles), configurable as your default startup tab in **Settings -> General**.
- **`Continue Last Run` with 30s Benchmark Hardfacts & Mod Updates Link:** Automatically detects your most recent save across both your default Zomboid folder and isolated `-cachedir` profiles in a clean 50/50 split — large save thumbnail, profile/mode/version pills, total available mod updates link (opens Mod Manager filtered to `Updates`), automatic profile switching on launch, and persisted 30s benchmark metrics (`Avg FPS`, `1% / 0.1% Low`, `Logic Time`, `CPU / GPU`, `Zombie AI`, `Heap RAM`) linking straight to the `REPORT` tab.
- **8 Quick Actions, 12 Rotating Tips & Live PZ News:** Balanced 2x2 overview with 8 instant shortcuts (including **Help Center & Cloud**), 12 rotating tips with clickable screenshots jumping into matching guides, and an anonymous Steam News / PZ Wiki fetcher (`AppID 108600`, 6h cache + offline fallback, toggleable in **Settings -> General**).
- **Updated Help Center & Screenshots:** Refreshed `START` and `Settings` Help Center chapters with new high-DPI screenshots across all 4 languages (`EN`, `DE`, `ES`, `PT`).

## v2.8.1 (2026-11-25)
- **Interactive Help Center Topic & Keyword Cloud:** Replaced the static keyword bar with a live interactive knowledge map right on the Help Center overview (25% live preview card with one-click **Maximize** into a full-screen explorer).
- **Visual Connections Across Guides & Tutorials:** Color-coded nodes for **Keywords**, **Guides**, and **Tutorials** highlight connected topics on hover with floating summaries, smooth zoom/pan/drag, and a slide-in Connected Topics drawer when clicking any keyword — adapting live across all 4 color themes and 4 languages.
- **Expanded Update Catalog Guide:** Added a dedicated Update Catalog & Update Lock guide block inside the Settings chapter with a direct **Open Update Catalog** jump button.

## v2.8.0 (2026-11-25)
- **Full Inline Settings Inside the Main Window:** All Settings tabs now open cleanly right inside SpiffoLab with a Back button (no separate popup window needed), keeping the interface seamless across every tab and theme.
- **Built-In App Update Catalog (`v2.5.2+`):** Browse available SpiffoLab releases directly inside the new **Updates** tab with readable release notes, version status badges, and one-click install or safe rollback to earlier versions (while preserving your latest Companion Mod files).
- **App Update Lock (Freeze Your App Version):** Lock your current SpiffoLab version right alongside your frozen game builds and mods. Startup update alerts still notify you when a new release is out, while preventing any accidental installation until you unlock it in the Update Catalog.
- **Updated Help Center & 4-Language Support:** Full localization across English, German, Spanish, and Portuguese, plus updated Settings documentation directly reachable via `?`.

## v2.7.1 (2026-11-24)
- **Clean Help Center Display Across All Tabs:** Fixed a visual overlap where opening the built-in Help Center from `LIVE LOG`, `DASHBOARD`, or `REPORT` could let the background view bleed through around the edges.
- **Cleaner In-App Update Notes:** The built-in update prompt now formats release highlights cleanly with readable bullet points instead of showing raw Markdown symbols.

## v2.7.0 (2026-11-24)
- **All-New Built-In Help Center (Inline & Pop-Out):** Opens directly inside SpiffoLab with a clean back button or in its own resizable window — automatically starting in the topic matching your current view.
- **Instant Search, Quick-Start Cards & 10 Feature Guides:** Search all guides and FAQs in real time, jump straight in via clickable topic tags or problem-oriented quick-start cards, and browse 10 complete chapters including **First-Time Setup** and **Settings** with zoomable high-DPI screenshots.
- **6 Interactive Step-by-Step Tutorials:** Follow practical walkthroughs for safe profile isolation, switching builds back to 2013 B19, locking mods, diagnosing FPS drops, and performance tuning — complete with direct one-click buttons to launch each action right inside SpiffoLab.
- **Seamless Theme & Live Language Sync:** Automatically adapts to all 4 built-in color themes (`Dark Purple`, `Light Blue`, `Rainbow Dark`, `Rainbow Light`) and switches languages live across English, German, Spanish, and Portuguese.

## v2.6.1 (2026-11-23)
- **Full Tooltips Across Build Manager & Profile Wizard:** Added helpful tooltips to every button, setting, search box, filter, and mod setup option across all 4 languages — including dynamic mod compatibility tooltips explaining why each mod matches (or conflicts with) your target build.
- **Instant Live Language Switching:** Switching between German, English, Spanish, and Portuguese now updates the entire open Build Manager, Profile Wizard, and status bar live right away without needing to reopen panels.

## v2.6.0 (2026-11-23)
- **Play Classic Builds Back to 2013 (B19 – B40):** Full support for historical Project Zomboid builds with automatic legacy Java 8 detection, smart launch presets (including direct offline/NoSteam support for B19), and guided hints when an external Java 8 runtime is needed.
- **Redesigned Build Manager Inside the Launcher:** Now opens in full view directly inside the Launcher with 4 clear era groups (`Build 42`, `Build 41`, `Build 34–40`, `Build 19–29`), curated release highlights for all 24 builds, and one-click **Patch Notes (PZ Wiki)** links.
- **Smart Profile Wizard with Integrated Mod Compatibility Picker:** Create isolated setups in a spacious two-column view with automatic mod compatibility checks for your chosen build — pick **No Mods**, **Take All Compatible**, or **Choose Manually** with instant search and status filters.
- **Profile Bar Sync Fix & Companion Mod Polish:** Fixed the Launcher profile dropdown resetting after refreshing mods, and streamlined the in-game Companion Mod prompt to copy the download link cleanly to your clipboard with clear setup instructions in EN / DE / ES / PT-BR.

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
