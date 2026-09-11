<div align="center">
  <img src="https://i.ibb.co.com/2Yc0dJHY/file-000000002aec8211833c370d3bc3fdfe.png" alt="VenForce" width="100%">
</div>

<div align="center">

<a href="https://sfl.gl/zrLiDYoa"><img src="https://img.shields.io/badge/Download-VenForce-0A84FF?style=flat-square&logo=android&logoColor=white" alt="Download VenForce" style="border:2px solid #0A84FF;border-radius:8px;padding:2px;"></a>
<a href="https://t.me/Vennec"><img src="https://img.shields.io/badge/Support-Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Support Channel" style="border:2px solid #0A84FF;border-radius:8px;padding:2px;"></a>

</div>

<hr>

## Overview

VenForce is a lightweight, root‑based system module for Android, built to improve performance, responsiveness, and stability across a broad range of devices and chipset configurations. It applies a set of system‑level tuning routines at boot and exposes a WebUI for live configuration on supported manager apps.

## Highlights

- System‑level performance and responsiveness tuning
- Adaptive display refresh‑rate handling
- GPU driver tuning for Adreno and Mali platforms
- Network stack tuning
- Memory management tuning
- Configurable WebUI control panel
- Broad root manager compatibility
- Minimal footprint, no persistent background overhead

## Module Information

| Field | Value |
| --- | --- |
| Name | VenForce |
| Module ID | `ven_force` |
| Version | 13.0-stable-fix |
| Version Code | 1229 |
| Author | [@vennec](https://t.me/Vennec) |
| Status | Stable |
| WebUI | Supported |
| Minimum Android | 10 (API 29) |

## Compatibility

VenForce detects the active root solution at install time and adapts accordingly. Supported managers:

| Manager | Notes |
| --- | --- |
| Magisk | Including Kitsune and Alpha builds |
| KernelSU | |
| KernelSU Next | |
| APatch | |
| MamboSU | |
| KOWSU | |
| AXManager / Axeron | |

Devices reporting an API level below 29 (Android 10) are flagged as unsupported during installation.

## Root and Non-Root Support

Both rooted and non-rooted devices are supported.

**Non-Root (AXManager)**
Provides access to WebUI features and a set of basic system optimizations offered by VenForce.

**Root (all supported root managers)**
Unlocks the full capability of VenForce, including system‑level optimizations that require root access.

For VenForce to operate at its maximum capability, root access is recommended.

## Repository Structure

```text
VenForce/
├── META-INF/
│   └── com/
│       └── google/
│           └── android/
│               ├── update-binary
│               └── updater-script
├── webroot/
│   └── index.html
├── customize.sh
├── module.prop
├── post-fs-data.sh
├── service.sh
└── ven.png
```

## Installation

1. Download the latest VenForce release from the link above.
2. Open a compatible root manager, or AXManager on non-root devices (see Compatibility).
3. Flash the module ZIP.
4. Reboot the device.
5. Open the WebUI from your manager app to configure the module.

## WebUI

VenForce ships with a WebUI for managers that support the WebUI interface. It surfaces device, storage, and battery information alongside module controls.

## Changelog

### 13.0-stable-fix

- System optimization improvements
- Performance improvements
- System responsiveness improvements
- WebUI improvements
- Script improvements
- Stability improvements
- Compatibility improvements

## Attribution and Redistribution Policy

Re-uploading, mirroring, or redistributing VenForce is permitted under the following terms.

**Attribution is required.** Every redistribution must clearly and visibly credit the original source:

> Source: @vennec

This attribution must not be removed, hidden, or replaced.

**Not permitted:**

- Claiming VenForce as original work
- Removing, hiding, or replacing the `@vennec` attribution
- Presenting an unofficial build as an official VenForce release
- Removing the original source or download information
- Changing, shortening, redirecting, or hiding the official links without authorization
- Using modified links in a way that misleads users about the project's origin

## Link Policy

Official links associated with VenForce (download, source, and release links) must not be changed, replaced, shortened, redirected, or hidden without prior written permission from [Telegram : @ellioth7207](https://github.com/ellioth7207). This applies to links in redistribution posts and repackaged copies of the module alike.

## Disclaimer

VenForce modifies Android system behavior. The author assumes no responsibility for bootloops, system instability, data loss, device malfunction, incompatibility with specific devices, conflicts with other modules, or any other damage resulting from use of this module. Install and use at your own risk.

## Credits

| Role | Handle |
| --- | --- |
| Development and maintenance | [@vennec](https://t.me/Vennec) |
| Link authorization | [@ellioth7207](https://github.com/ellioth7207) |

<hr>

<p align="center"><sub>Copyright ©VENNEC . All attribution and link‑policy terms above apply to any redistribution of this project.</sub></p>

<div align="center">

<a href="https://i.ibb.co.com/TxNqw4c4/qr-ID1026576754000-03-09-26-1788411437-1788411438034.jpg"><img src="https://img.shields.io/badge/Donate-Support%20VenForce-FF9500?style=flat-square" alt="Donate" style="border:2px solid #0A84FF;border-radius:8px;padding:2px;"></a>

</div>
