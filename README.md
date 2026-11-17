# SYSELIX for Windows

SYSELIX combines Windows cleanup, program removal, startup management, disk analysis and system diagnostics.

**Official website: [syselix.netlify.app](https://syselix.netlify.app/)** · [Русская версия](https://syselix.netlify.app/ru)

## Latest: 1.0.17

- Separate cleanup controls: CHECK PC always scans; CLEAN SELECTED shows the selected size and asks for confirmation. Starting a new scan clears the previous selection.
- Recovery storage manager with contents, sizes, retention review and a capacity limit. Retention does not automatically delete backups; shared driver exports are verified by content.
- Additional driver guards exclude active, boot-critical and critical-class packages; candidates are checked again before removal and backed up. Windows Update downloads require manual selection and servicing checks.
- Storage Insights reviews files and folders, marks incomplete results and skips inaccessible paths and links. Large or old files are not automatically treated as unnecessary.
- Additional review for crash dumps, browser on-device models and application/game data, including warnings about saves and cloud synchronization.
- Hibernation-file controls show the current mode and explain reduced/full modes; cleanup reports distinguish logical file sizes, measured free-space changes and backup/quarantine usage.
- Windows 10 and Windows 11 x64 support. Installation, startup and cleanup analysis were visually checked in a Windows 10 Pro 22H2 Hyper-V VM; Windows 11 installation and UI were also checked.
- Seven application languages. Existing Freemius activation and licensing remain in place.

189 regression checks passed on 1.0.17. All 493 installed files matched on Windows 11. These are internal checks, not independent certification. Real driver removal/restoration and changes to hibernation have not been validated end-to-end; no new temperature measurements are claimed. Windows 10 VM checks do not establish compatibility with every physical device.

## Download

[Get the latest release](https://github.com/syselyx-maker/SYSELIX-Releases/releases/latest) for Windows 10/11, 64-bit. Start with a 7-day Pro trial; Free mode remains available afterward.

The installer is currently unsigned and Windows may display an unknown-publisher warning. Do not disable Windows security protections. Updates are installed manually.

## Review before cleaning

- Inspect cleanup candidates and selected-file details.
- Keep persistent exclusions for files and folders.
- Quarantine eligible individual user temporary files and restore them through Recovery.
- Ordinary CLEAN permanently deletes selected files and has no Undo. Quarantine has separate eligibility and capacity limits; keep independent backups.

## Documentation and support

- [Installation and updates](https://syselix.netlify.app/installation)
- [Pro activation and device transfers](https://syselix.netlify.app/activation)
- [Verification results and limitations](https://syselix.netlify.app/checks)
- [Release history](https://syselix.netlify.app/updates)
- [Support and bug reports](https://syselix.netlify.app/support)
- [License agreement](https://syselix.netlify.app/license), [Privacy](https://syselix.netlify.app/privacy), [Refund policy](https://syselix.netlify.app/refunds)

Pro commercial payments and licenses are handled by Freemius. A one-time purchase grants lifetime use of SYSELIX 1.x for the selected number of PCs.

This repository hosts official downloads and release notes. Application source packages, when provided, are attached as named release assets. Verification results are internal checks, not independent certification or proof of superiority over competitors.
