# Write Time

Write Time is an AI writing assistant for Windows, based on PI-Desktop and the Pi SDK.

## Download

- **Windows installer (recommended):** [Download setup 0.18.0](https://github.com/xunnia/WriteTime-Releases/releases/download/v0.18.0/WriteTime-Setup-0.18.0.exe)
- [All versions and portable packages](https://github.com/xunnia/WriteTime-Releases/releases)
- [Current release details](https://github.com/xunnia/WriteTime-Releases/releases/latest)

Download `WriteTime-Setup-<version>.exe`, run it, and follow the installation wizard.
The Windows installer supports in-app updates. ZIP and portable executable
distributions use manual download and replacement.

Windows 10/11 x64 is required. This first release is an early preview. The
installer is currently unsigned, so Windows may display an unknown-publisher
prompt. Check the download against the release's `SHA256SUMS.txt` when needed.
No API key or paid model access is included; configure your own AI service.

## Updates

Use **Settings → About → Check for updates** in Write Time. Stable release
installers, `latest.yml`, and blockmaps are published together in this repository.
Future Windows installer releases must use a higher version number and preserve
the same application identity and update feed.

The versioned direct link above points to 0.18.0. After later releases, use the
current release details page to choose the matching installer.

## Source and licenses

Write Time is a modified distribution of [PI-Desktop](https://github.com/vastsa/PI-Desktop),
licensed under LGPL-3.0-or-later. Each release includes its corresponding source
archive and build instructions alongside the binaries. The development
repository remains private; no development account is needed to download the
released source snapshot.

Pi SDK and other components retain their respective licenses. License texts and
dependency notices are included in the application's `resources/licenses`
directory and in the source archive. Electron also includes its own notices.

This repository distributes released files. It contains no user data, API keys,
signing certificates, or private project handoff documents.
