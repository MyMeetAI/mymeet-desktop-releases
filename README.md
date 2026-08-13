# Mymeet.ai Desktop releases

Public installer binaries and updater manifests for Mymeet.ai Desktop on macOS and Windows.

Source repositories are private. Downloadable binaries are published on the
[Releases](../../releases) page.

## Platform update channels

The update feeds are intentionally isolated by platform:

- macOS: [`macos/latest-mac.yml`](macos/latest-mac.yml), with release tags such as `mac-v0.1.54`;
- Windows: [`windows/latest.yml`](windows/latest.yml), with release tags such as `win-v0.1.55`.

Each release workflow updates only its own manifest. Manifest asset URLs are
immutable GitHub Release URLs, so publishing one platform cannot redirect or
roll back the other platform's update channel.

## Current releases

- macOS: `mac-v0.1.54` (arm64 and x64);
- Windows: `win-v0.1.55` (x64 and ia32).

The Windows release contains signed NSIS installers, blockmaps, SHA-256
checksums, and a provenance manifest.

## Install notes

On macOS, download the appropriate DMG, move the app to Applications, and use
right-click → Open or System Settings → Privacy & Security → Open Anyway if
macOS blocks the first launch.

The Windows installers use the project's pinned self-signed Authenticode
identity. Windows can show SmartScreen / Unknown Publisher during the first
manual installation. The application updater independently verifies the exact
pinned certificate and artifact identity for later updates.
