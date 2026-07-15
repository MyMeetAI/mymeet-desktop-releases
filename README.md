# Mymeet.ai Desktop releases

Public installer binaries for Mymeet.ai Desktop (macOS and Windows).

> Source code: [`mymeet-desktop-recorder`](https://github.com/mymeet-ai-first-company/mymeet-desktop-recorder) (private)
> Landing page: [suite.mymeet.ai/desktop](https://suite.mymeet.ai/desktop)

## Latest release

See [Releases](../../releases) tab for `.dmg` and `.exe` downloads.

- Latest macOS tag: `v0.1.42`
- Latest Windows tag: `v0.1.40`
- macOS Apple Silicon: `Mymeet.ai-0.1.42-arm64.dmg`
- macOS Intel: `Mymeet.ai-0.1.42.dmg`
- macOS update: onboarding, Recordings, Settings, notifications, app/tray
  icons, and the native menu-bar context menu now share the redesigned Mymeet
  interface. Explicit launches open Recordings; login-item startup stays in the
  menu bar.
- Windows installer: `Mymeet.ai.Setup.0.1.40.exe`
- Windows SHA256: `FB443095F01F0D07472CB87BD461A2721A2C912437F1F41488C3EA14805B80EF`
- Windows update: reopening the app from the desktop or Start shortcut now
  opens `Recordings` after onboarding, and double-clicking the tray icon opens
  the same primary screen. Expired backend auth now returns users to login
  cleanly, and backend-ready meetings are marked sent without repeated retries.
  Previous 0.1.39 upload and mic-source fixes remain included.

## Available builds

| Release | macOS | Windows | Architecture |
|---|---|---|---|
| v0.1.42 | 14.4+ | - | macOS arm64/x64 |
| v0.1.41 | 14.4+ | - | macOS arm64/x64 |
| v0.1.40 | 14.4+ | 10/11 | macOS arm64/x64 + Windows x64/ia32 |
| v0.1.39 | - | 10/11 | Windows x64/ia32 |
| v0.1.38 | - | 10/11 | Windows x64/ia32 |
| v0.1.37 | 14.4+ | 10/11 | macOS arm64/x64 + Windows x64/ia32 |
| v0.1.36 | 14.4+ | 10/11 | macOS arm64/x64 + Windows x64/ia32 |
| v0.1.10 | 14.4+ | - | Apple Silicon (arm64) + Intel (x64) |
| v0.1.9 | 14.4+ | - | Apple Silicon (arm64) + Intel (x64) |
| v0.1.8 | 13+ | - | Apple Silicon (arm64) + Intel (x64) |
| v0.1.0 | 13+ | - | Apple Silicon (arm64) + Intel (x64) |

## Install

Скачайте `.dmg` подходящий вашему Mac, перетащите в Applications, при первом запуске right-click → Open или System Settings → Privacy & Security → Open Anyway (билд не подписан Apple Developer ID).

Полная инструкция: [suite.mymeet.ai/desktop](https://suite.mymeet.ai/desktop).
