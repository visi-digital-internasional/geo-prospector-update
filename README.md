
<!-- RELEASE-6.7.19.1 -->
## Latest release: 6.7.19.1

Geo Prospector 6.7.19.1 introduces the redesigned website-list Email Finder powered by a protected Python backend, inline B2B prospecting results, remote plan quotas, and Custom license support.

- [Release notes](docs/releases/6.7.19.1.md)
- [Download installer](https://github.com/visi-digital-internasional/geo-prospector-update/releases/download/v6.7.19.1/GeoProspectorSetup.exe)
- SHA-256: 8B06EA61BA153523BC108A0053F0C3D3714C7976B70DF26920CBAB108AD21885
<!-- /RELEASE-6.7.19.1 -->
# Geo Prospector Established Edition

**Geo Prospector** is a Windows desktop application designed to help users discover and collect business prospect data based on business categories and locations.

> This repository is used to distribute the installer, publish version information, and deliver application updates for Geo Prospector Established Edition.

## Official Website

[**Visit the Official Geo Prospector Website**](https://geoprospector.id/)

## Download the Application

[**Download the Latest Geo Prospector Installer**](https://github.com/visi-digital-internasional/geo-prospector-update/releases/latest/download/GeoProspectorSetup.exe)

Latest version: **v6.7.15.1**

[**View the Latest Release**](https://github.com/visi-digital-internasional/geo-prospector-update/releases/latest)

## Documentation

Installation, activation, B2B Finder, Market Research, Email Finder, data export, and troubleshooting guides are available in the official GitBook documentation:

[**Open the Geo Prospector Documentation**](https://visi-digital-internasional.gitbook.io/geo-prospector)

## Security Scan

View the URL scan result on VirusTotal:

[**View the VirusTotal Report**](https://www.virustotal.com/gui/url/17506a6fdfab37537bec95b3b24ca4052470dbcfc262532bfc0825098b430249?nocache=1)

> Download Geo Prospector only from the official website or the official GitHub release link provided in this repository.

## Main Features

- Business discovery by category and location
- Single-category and multi-category searches
- Country, province, and city selection
- Target Market Research
- Saved Categories
- Duplicate filtering
- Email Finder
- CSV, Excel, TXT, and JSON export
- Device Activation
- Dynamic Customer Support WhatsApp configuration
- Automatic application updates
- Signed security anchor for build-integrity verification

## System Requirements

- Windows 10 or Windows 11
- 64-bit operating system
- Internet connection
- Sufficient storage for the application and browser runtime

## Installation

1. Download `GeoProspectorSetup.exe`.
2. Run the installer as Administrator.
3. Follow the installation steps until completion.
4. Open Geo Prospector.
5. Go to the **Activation** page to activate your license.

## License Activation

1. Copy your **Device ID**.
2. Click **Send Activation Request**.
3. Send the activation request to Customer Support.
4. Enter the license token provided by Customer Support.
5. Complete the activation process.

[**Open the Activation Guide**](https://visi-digital-internasional.gitbook.io/geo-prospector)

## Application Updates

Geo Prospector checks for updates when the application starts. When a newer version is available, the application displays an update notification and directs the user to the latest installer.

[**View the Update Manifest**](https://raw.githubusercontent.com/visi-digital-internasional/geo-prospector-update/main/version.json)

## Installer Verification

**Version:** `v6.7.15.1`  
**File name:** `GeoProspectorSetup.exe`  
**File size:** `253264229 bytes`  
**SHA-256:**

```text
FE3CFADD45DA098984318BCA64B2C9A65B9174F657048EBA4A80568A14855829
```

Verify the installer with PowerShell:

```powershell
Get-FileHash `
  -LiteralPath ".\GeoProspectorSetup.exe" `
  -Algorithm SHA256
```

## Build Security

Geo Prospector Established Edition uses:

- Ed25519 public-key verification
- Signed security anchor manifest
- Build-integrity verification
- Device-bound license activation
- Clock rollback protection

The private signing key is not included in the application or installer.

## Important Links

- [Official Website](https://geoprospector.id/)
- [Download Application](https://github.com/visi-digital-internasional/geo-prospector-update/releases/latest/download/GeoProspectorSetup.exe)
- [Latest GitHub Release](https://github.com/visi-digital-internasional/geo-prospector-update/releases/latest)
- [GitBook Documentation](https://visi-digital-internasional.gitbook.io/geo-prospector)
- [VirusTotal Report](https://www.virustotal.com/gui/url/17506a6fdfab37537bec95b3b24ca4052470dbcfc262532bfc0825098b430249?nocache=1)

## Support

Use the **Send Activation Request** button inside the application to contact Customer Support.

## Publisher

**Visi Digital Internasional**

Copyright 2026 Visi Digital Internasional. All rights reserved.

<!-- ESTABLISHED_RELEASE_6_7_16_3_START -->
## Latest Established Release v6.7.16.3

Geo Prospector Established Edition v6.7.16.3 is a maintenance release based on the verified v6.7.15.1 source.

- Installer: [GeoProspectorSetup.exe](https://github.com/visi-digital-internasional/geo-prospector-update/releases/latest/download/GeoProspectorSetup.exe)
- SHA-256: $installerHash
- Size: $(C:\APKPC\geo_prospector_editions\established_6_7_16_3\dist_installer\GeoProspectorSetup.exe.Length) bytes
- Security manifest: 6.7.16.3
- Mandatory update: alse

The Established public key and application business logic are unchanged.
<!-- ESTABLISHED_RELEASE_6_7_16_3_END -->

## Version 6.7.17.1

Released 17 July 2026.

### Improvements

- Expanded Google Maps coverage using multiple geographic viewports.
- Improved persistent duplicate filtering.
- Continues collecting candidates after previous results are skipped.
- Added data-count options: 200, 300, 400, and 500.
- Dynamic scraping estimates with and without Email Finder.
- Enterprise supports up to 500 data per search.
- Business supports up to 300 data per search.
- UTF-8 BOM-safe dedupe index reader.
- Improved Google Maps Place ID identity matching.
- Shared domains such as Linktree are no longer treated as unique business identities.

### Download

[Download GeoProspectorSetup.exe](https://github.com/visi-digital-internasional/geo-prospector-update/releases/download/v6.7.17.1/GeoProspectorSetup.exe)

<!-- GEO_PROSPECTOR_CURRENT_RELEASE_START -->
## Current release

Geo Prospector Established Edition is currently available as version **6.7.19.2**.

| Property | Value |
|---|---|
| Version | 6.7.19.2 |
| Release date | 20 July 2026 |
| Platform | Windows 64-bit |
| Installer | GeoProspectorSetup.exe |

- [Download the latest installer](https://github.com/visi-digital-internasional/geo-prospector-update/releases/download/v6.7.19.2/GeoProspectorSetup.exe)
- [View the GitHub release](https://github.com/visi-digital-internasional/geo-prospector-update/releases/tag/v6.7.19.2)
- SHA-256: EBB61EEA5F08D61382D8ABD354773B734258C6D03CF4F7B85B382D15223D6CED
<!-- GEO_PROSPECTOR_CURRENT_RELEASE_END -->

<!-- ESTABLISHED_RELEASE_6_7_19_2_START -->
## Established Edition v6.7.19.2

Geo Prospector 6.7.19.2 introduces centralized membership and credit management.

- Automatic membership registration during license generation.
- Server-controlled membership status and credit balance.
- Administrative credit additions through Google Sheets.
- Remote membership blocking using the active field.
- Membership restoration after application restart.
- Protected Python Email Finder backend.
- Signed Established Edition security manifest.

- [Windows installer](https://github.com/visi-digital-internasional/geo-prospector-update/releases/download/v6.7.19.2/GeoProspectorSetup.exe)
- [GitHub release](https://github.com/visi-digital-internasional/geo-prospector-update/releases/tag/v6.7.19.2)
- SHA-256: EBB61EEA5F08D61382D8ABD354773B734258C6D03CF4F7B85B382D15223D6CED
<!-- ESTABLISHED_RELEASE_6_7_19_2_END -->
