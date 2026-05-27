# Black Widow 🕷️ — Salesforce Debug Log Analyzer

**The only Salesforce log tool that shows you the complete user experience journey.**

Unlike traditional tools that show one log at a time, Black Widow groups related logs from a single user action and tells you:
- Total user wait time (backend + frontend)
- Which triggers, flows, and callouts fired
- Where the time actually went
- What to fix and how

---

## Download

**[→ Get the latest installer](https://github.com/felisbinofarms/black-widow-releases/releases/latest)**

| Platform | File |
|----------|------|
| 🪟 **Windows (x64)** | `BlackWidow-<version>-win-x64-Setup.exe` (Installer, no admin required) |
| 🍎 **macOS Apple Silicon** (M1/M2/M3) | `BlackWidow-<version>-macos-arm64.dmg` (ARM64 native) |
| 🍎 **macOS Intel** | `BlackWidow-<version>-macos-x64.dmg` (x64) |
| 🐧 **Linux (x64)** | `BlackWidow-<version>-linux-x64.tar.gz` (Ubuntu 22+ tested) |

→ **[See all releases](../../releases)**  ·  [Latest release notes](../../releases/latest)

---

## Installation

### Windows
1. Download `BlackWidow-<version>-win-x64-Setup.exe` from the [latest release](../../releases/latest).
2. Run it — no admin rights needed, installs to `%LocalAppData%\Black Widow`.
3. Launch from Start Menu or Desktop shortcut.

> **SmartScreen warning?** The installer is not yet code-signed. Click **More info → Run anyway**. Code-signing is in progress.

### macOS
1. Download the `.dmg` matching your chip (M1/M2/M3 → `arm64`, older Mac → `x64`).
2. Open the `.dmg` and drag **BlackWidow** to your Applications folder.
3. First launch only: **right-click → Open** to bypass the Gatekeeper warning (app is not yet Apple-signed).

### Linux
```bash
tar -xzf BlackWidow-*-linux-x64.tar.gz -C ~/blackwidow
cd ~/blackwidow
./BlackWidow
```

---

## System Requirements

- **Windows**: Windows 10 21H2+ or Windows 11 (x64)
- **macOS**: macOS 12 Monterey or later
- **Linux**: Ubuntu 22.04+ or equivalent (glibc 2.35+)
- No .NET installation required — all runtimes are bundled

---

## Features

- 📂 **Open any debug log** — drag-and-drop or file picker
- 🔗 **Transaction grouping** — see all logs from one user action together
- ⏱️ **Phase detection** — Backend (triggers/flows) vs Frontend (component loading)
- 🔍 **SOQL/DML analysis** — N+1 detection, execution plans, governor limit usage
- 🔐 **PII scanner** — flags sensitive data in logs
- 🌲 **Execution tree** — visualize the full call stack
- ⚡ **Connect to Salesforce** — re-run queries live, stream logs in real time
- 📤 **Export** — PDF/HTML reports

---

## Feedback &amp; Support

- **💬 Discussions** — questions, ideas, and show &amp; tell → [Discussions](../../discussions)
- **🐛 Bug reports &amp; feature requests** → [open an issue](../../issues)
- **🔐 Security vulnerabilities** → email victorfelisbino@gmail.com (do not open a public issue)

---

## Source Code

This is the public **distribution repo** — releases, landing page, and community channels live here. The application source is currently private during the v1.x MVP.

---

## License

Black Widow is **proprietary software** — Copyright © 2026 Victor Felisbino. All rights reserved.

Free to download and use. Redistribution, modification, or reverse engineering is not permitted. See the [LICENSE](LICENSE) file for full terms.
