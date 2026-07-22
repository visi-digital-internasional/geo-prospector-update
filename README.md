# Geo Prospector Established Edition

Geo Prospector is a Windows desktop application by **Visi Digital Internasional** for discovering, collecting, and exporting business prospect data by category and location.

> This public repository distributes the official Windows installer and update manifest. The application source code and private signing material are not published here.

## Current Release

| Property | Value |
|---|---|
| Version | **v6.7.22.1** |
| Release date | **2026-07-22** |
| Platform | Windows 10/11, 64-bit |
| Installer | `GeoProspectorSetup.exe` |
| Size | `264426395 bytes` |
| SHA-256 | `6C6FC5EB5277B8A81F43E1DD154F16A332AFF97B4D23A515D8B9477CA8E688B7` |

[Download Geo Prospector v6.7.22.1](https://github.com/visi-digital-internasional/geo-prospector-update/releases/download/v6.7.22.1/GeoProspectorSetup.exe)

[View release notes](https://github.com/visi-digital-internasional/geo-prospector-update/releases/tag/v6.7.22.1)

## Highlights in v6.7.22.1

- Country Engine 3-Stage v5.0
- Province Engine v4.8 frozen
- Exact-category business searches
- Country, province/state, and locality targeting
- Result targets up to 500 records
- Single-category and multi-category workflows
- Saved categories and persistent settings
- Duplicate filtering and current-result deduplication
- Email Finder backend
- CSV, Excel, TXT, and JSON exports
- Device-bound license activation
- Centralized membership and credit controls
- Signed security anchor and build-integrity verification
- Clock rollback protection
- Bundled Node.js and Playwright browser runtime

## Installation

1. Download `GeoProspectorSetup.exe` from the current release.
2. Run the installer.
3. Launch **Geo Prospector**.
4. Open the Activation page.
5. Activate the device using a valid license token.

Existing application data under `C:\GeoProspector` is preserved when the application is uninstalled.

## Verify the Installer

Run this command in PowerShell from the folder containing the installer:

```powershell
Get-FileHash -LiteralPath ".\GeoProspectorSetup.exe" -Algorithm SHA256
```

The result must match:

```text
6C6FC5EB5277B8A81F43E1DD154F16A332AFF97B4D23A515D8B9477CA8E688B7
```

Do not install the application when the hash is different.

## Automatic Updates

Geo Prospector checks the public update manifest when the application starts:

[View `version.json`](https://raw.githubusercontent.com/visi-digital-internasional/geo-prospector-update/main/version.json)

Current manifest values:

```json
{
    "latest_version":  "6.7.22.1",
    "version":  "6.7.22.1",
    "download_url":  "https://github.com/visi-digital-internasional/geo-prospector-update/releases/download/v6.7.22.1/GeoProspectorSetup.exe",
    "release_notes":  "Country Engine 3-Stage v5.0, frozen Province Engine v4.8, exact-category search, target options up to 500 records, bundled Node.js and Playwright runtime, protected Email Finder backend, signed security anchor, and final UI result-import and estimated-time corrections.",
    "force_update":  false,
    "sha256":  "6C6FC5EB5277B8A81F43E1DD154F16A332AFF97B4D23A515D8B9477CA8E688B7",
    "published_at":  "2026-07-22",
    "release_url":  "https://github.com/visi-digital-internasional/geo-prospector-update/releases/tag/v6.7.22.1"
}
```

## Security

Geo Prospector Established Edition uses:

- Ed25519 public-key verification
- Signed security-anchor manifests
- Runtime build-integrity checks
- Device-bound license activation
- Clock rollback protection
- External private signing-key storage during official builds

The private signing key is not included in the repository, application, or installer.

## Official Links

- [Official website](https://geoprospector.id)
- [Latest Windows release](https://github.com/visi-digital-internasional/geo-prospector-update/releases/latest)
- [Update manifest](https://raw.githubusercontent.com/visi-digital-internasional/geo-prospector-update/main/version.json)
- [Documentation](https://visi-digital-internasional.gitbook.io/geo-prospector)

## Support

Use **Send Activation Request** inside Geo Prospector to contact Customer Support regarding activation and license assistance.

## Publisher

**Visi Digital Internasional**

Copyright © 2026 Visi Digital Internasional. All rights reserved.
