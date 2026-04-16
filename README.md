# WinDeclare

**A declarative engine for provisioning Windows and maintaining its desired state.**

WinDeclare allows you to define your Windows configuration in simple JSON files and apply it on a fresh install or on a recurring schedule for post‑update cleanup and drift correction.

## Features

- Declarative JSON configuration
- First‑run provisioning
- Optional scheduled enforcement
- App installation via Winget, Store, or custom installers
- System settings, privacy controls, UI preferences, and policy keys
- Silent operation with logging
- Dry‑run mode for safe testing

## Quick Start

Run WinDeclare on a fresh install:

```powershell
iwr https://raw.githubusercontent.com/<yourname>/WinDeclare/main/Bootstrap.ps1 | iex
