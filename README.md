# Geo Prospector Established Edition

Geo Prospector is a Windows desktop application for discovering, collecting, and exporting business prospect data by category and location.

> This repository distributes the official Windows installer and the application update manifest.

## Current Release

| Property | Value |
|---|---|
| Version | `6.7.25.1` |
| Release date | `2026-07-24` |
| Platform | Windows 10/11, 64-bit |
| Installer | `GeoProspectorSetup.exe` |
| File size | `273765875 bytes` (261.08 MiB) |
| SHA-256 | `49ACD03FDAEC621B9CFD5A45FB9CF51F90BC55197DE8381C37A072192BDE519F` |

- [Download the latest installer](https://github.com/visi-digital-internasional/geo-prospector-update/releases/download/v6.7.25.1/GeoProspectorSetup.exe)
- [View the release notes](https://github.com/visi-digital-internasional/geo-prospector-update/releases/tag/v6.7.25.1)
- [Open the documentation](https://visi-digital-internasional.gitbook.io/geo-prospector)
- [Visit the official website](https://geoprospector.id)

## What Is New in 6.7.25.1

- Structured Country → Province/State → City targeting.
- Plan-based limits: Free 50, Starter 500, Business 1,000, and Enterprise 5,000.
- Controlled related-category matching for improved Google Maps relevance.
- Nonfatal handling when no valid matching businesses are available.
- Accurate progress based on valid rows instead of the requested target.
- Zero lead-credit usage when a valid search returns zero rows.
- Complete self-contained Node.js, Playwright Chromium, scraper, and protected Email Finder runtime.
- Established public-key verification, signed security anchor, device-bound activation, and clock rollback protection.
- Stable GitHub installer asset name: `GeoProspectorSetup.exe`.

## Main Features

- B2B prospect discovery by canonical category and location
- Single-category and multi-category searches
- Country, province, and city selection
- Saved Categories
- Persistent duplicate filtering
- Email Finder with manual and CSV website input
- CSV, Excel, TXT, and JSON export
- Device-bound license activation
- Remote membership, plan, and credit controls
- Automatic application updates
- Signed security anchor and build-integrity verification

## Installation

1. Download `GeoProspectorSetup.exe`.
2. Close Geo Prospector when it is currently running.
3. Run the installer.
4. Complete the installation wizard.
5. Open Geo Prospector and confirm version `6.7.25.1`.
6. Confirm the active license status.

Existing application data under `C:\GeoProspector` is preserved.

## Installer Verification

**Version:** `6.7.25.1`
**File name:** `GeoProspectorSetup.exe`
**File size:** `273765875 bytes` (261.08 MiB)
**SHA-256:**

```text
49ACD03FDAEC621B9CFD5A45FB9CF51F90BC55197DE8381C37A072192BDE519F
```

Verify the installer with PowerShell:

```powershell
Get-FileHash -LiteralPath ".\GeoProspectorSetup.exe" -Algorithm SHA256
```

Do not install the file when the hash is different.

## Update Manifest

The application reads the public update manifest from:

[View `version.json`](https://raw.githubusercontent.com/visi-digital-internasional/geo-prospector-update/main/version.json)

The stable latest-installer URL is:

[Download `GeoProspectorSetup.exe`](https://github.com/visi-digital-internasional/geo-prospector-update/releases/latest/download/GeoProspectorSetup.exe)

## Build Security

Geo Prospector Established Edition uses:

- Ed25519 public-key verification
- Signed security-anchor manifest and signature
- Runtime build-integrity verification
- Device-bound license activation
- Clock rollback protection
- External private signing-key storage during official builds

The private signing key is not included in the repository, application, installer, or release assets.

## Support

Use the **Send Activation Request** action inside the application to contact Customer Support.

## Publisher

Visi Digital Internasional

Copyright 2026 Visi Digital Internasional. All rights reserved.
