# Black Widow ðŸ•·ï¸ â€” Salesforce Debug Log Analyzer

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
| ðŸªŸ **Windows (x64)** | `BlackWidow-{version}-win-x64-Setup.exe` | Installer, no admin required |
| ðŸŽ **macOS Apple Silicon** (M1/M2/M3) | `BlackWidow-{version}-macos-arm64.zip` | ARM64 native |
| ðŸŽ **macOS Intel** | `BlackWidow-{version}-macos-x64.zip` | x64 |
| ðŸ§ **Linux (x64)** | `BlackWidow-{version}-linux-x64.tar.gz` | Ubuntu 22+ tested |

â†’ **[See all releases](../../releases)**

---

## Installation

### Windows
1. Download `BlackWidow-{version}-win-x64-Setup.exe`
2. Run it â€” no admin rights needed, installs to `%LocalAppData%\Black Widow`
3. Launch from Start Menu or Desktop shortcut

### macOS
1. Download the `.zip` matching your chip (M1/M2/M3 â†’ arm64, older Mac â†’ x64)
2. Unzip and drag `BlackWidow` to your Applications folder
3. First launch: right-click â†’ **Open** (bypasses Gatekeeper warning for unsigned apps)

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
- No .NET installation required â€” all runtimes are bundled

---

## Features

- ðŸ“‚ **Open any debug log** â€” drag-and-drop or file picker
- ðŸ”— **Transaction grouping** â€” see all logs from one user action together
- â±ï¸ **Phase detection** â€” Backend (triggers/flows) vs Frontend (component loading)
- ðŸ” **SOQL/DML analysis** â€” N+1 detection, execution plans, governor limit usage
- ðŸ” **PII scanner** â€” flags sensitive data in logs
- ðŸŒ² **Execution tree** â€” visualize the full call stack
- âš¡ **Connect to Salesforce** â€” re-run queries live, stream logs in real time
- ðŸ“¤ **Export** â€” PDF/HTML reports

---

## Feedback & Support

- **ðŸ’¬ Discussions** â€” questions, ideas, and show & tell â†’ [Discussions](../../discussions)
- **ðŸ› Bug reports & feature requests** â†’ [open an issue](https://github.com/felisbinofarms/salesforce-debug-log-analyzer/issues) in the source repo
- **ðŸ” Security vulnerabilities** â†’ email victorfelisbino@gmail.com (do not open a public issue)

---

## Source Code

This is the distribution repo â€” **releases only**.

The source code is developed at:
**[felisbinofarms/salesforce-debug-log-analyzer](https://github.com/felisbinofarms/salesforce-debug-log-analyzer)**

---

## License

Black Widow is **proprietary software** â€” Copyright Â© 2026 Victor Felisbino. All rights reserved.

Free to download and use. Redistribution, modification, or reverse engineering is not permitted.
See the [LICENSE](https://github.com/felisbinofarms/salesforce-debug-log-analyzer/blob/master/LICENSE) for full terms.
