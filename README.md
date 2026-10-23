# The Outfit — Native PC

An unofficial native Windows revival of **The Outfit (2006)**, built on DohmBoy64Bit’s ReXGlue recompilation.

**[Download the Windows preview](https://github.com/matt090-0/TheOutfit-Native-PC/releases/tag/v0.1.0-preview)**

## Play

1. Download **TheOutfit-0.1.0-preview-Windows-x64.zip** from Releases.
2. Extract the whole ZIP and open **OutfitLauncher.exe**.
3. Choose **Import ISO** and select your own supported Xbox 360 disc image.
4. Choose **Play**. An Xbox controller is recommended.

An existing complete extracted folder also works. Import needs about 6.2 GB plus cache space; choose another storage folder in Settings if needed. Your original ISO is preserved. No game downloads, disc image or extracted game assets are supplied.

Windows 10/11 x64, .NET Framework 4.8, an AVX2-capable CPU and D3D12 graphics are required. Microsoft runtime DLLs are included. Supported USA/Europe retail default.xex: 9,056,256 bytes; SHA-256 `1bd7c232574681d51865c40383581f4157592991998bc6ce085e24ce38325654`.

## Included

- Minimal launcher with one-time ISO import and revision checks.
- Optional normal-speed 60 FPS rendering with the original 30 Hz world simulation.
- Optional 2× internal resolution and 16× eligible texture filtering.
- Startup, shader-constant, vertex-upload and shutdown corrections.
- Fullscreen and artwork selected locally. The download uses an original vector background and includes no game artwork.

Online multiplayer and Steam invitations are not implemented.

## Community preview

Mission one was completed on an earlier stable 30 FPS build. Later brief tests confirmed smoother normal-speed gameplay at about 60 presentations/s, sharper graphics and a clean shutdown. The publisher also tested Play from the packaged launcher and reported normal behavior. Full-game and multi-hardware stability are not established; audio decoding issues and broader mission, physics and cutscene testing remain open. Back up saves before trying a new preview.

The release includes 47 launcher/import checks, a full import with all 114 files hash-matched, cancellation cleanup, 80 native timing checks and 23 cheat-hook checks. The corresponding runtime source was independently rebuilt without game data and passed the same native checks.

Preferences, saves and logs are created locally under `%LOCALAPPDATA%\TheOutfitRecomp`. A custom game-storage folder changes the import location. The launcher has no accounts, updater, telemetry or automatic uploads. Review local logs for paths/hardware information before sharing them.
