# Black Widow 🕷️ — Salesforce Debug Log Analyzer

**The only Salesforce log tool that shows you the complete user experience journey.**

Unlike traditional tools that show one log at a time, Black Widow groups related logs from a single user action and tells you:
- Total user wait time (backend + frontend)
- Which triggers, flows, and callouts fired
- Where the time actually went
- What to fix and how

---

## Download

| Platform | File | Notes |
|----------|------|-------|
| 🪟 **Windows (x64)** | `BlackWidow-{version}-win-x64-Setup.exe` | Installer, no admin required |
| 🍎 **macOS Apple Silicon** (M1/M2/M3) | `BlackWidow-{version}-macos-arm64.zip` | ARM64 native |
| 🍎 **macOS Intel** | `BlackWidow-{version}-macos-x64.zip` | x64 |
| 🐧 **Linux (x64)** | `BlackWidow-{version}-linux-x64.tar.gz` | Ubuntu 22+ tested |

→ **[See all releases](../../releases)**

---

## Installation

### Windows
1. Download `BlackWidow-{version}-win-x64-Setup.exe`
2. Run it — no admin rights needed, installs to `%LocalAppData%\Black Widow`
3. Launch from Start Menu or Desktop shortcut

### macOS
1. Download the `.zip` matching your chip (M1/M2/M3 → arm64, older Mac → x64)
2. Unzip and drag `BlackWidow` to your Applications folder
3. First launch: right-click → **Open** (bypasses Gatekeeper warning for unsigned apps)

### Linux
```bash
tar -xzf BlackWidow-{version}-linux-x64.tar.gz -C ~/blackwidow
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

## Source Code

This is the distribution repo — **releases only**.

The source code is developed at:
**[felisbinofarms/salesforce-debug-log-analyzer](https://github.com/felisbinofarms/salesforce-debug-log-analyzer)**

Issues, feature requests, and bug reports → [open an issue](https://github.com/felisbinofarms/salesforce-debug-log-analyzer/issues) in the source repo.

---

## License

Freeware — free to use. All features unlocked.
