# 🛠️ DimisM Ultimate Windows Repair Tool

> **The ultimate "Swiss Army Knife" for Windows maintenance, repair, and optimization.**

![Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-blue) ![Language](https://img.shields.io/badge/Language-Batch-green) ![License](https://img.shields.io/badge/License-MIT-orange)

## 📖 About
**DimisM Ultimate Windows Repair** is a lightweight, menu-driven Batch script designed to simplify common troubleshooting and maintenance tasks on Windows systems. Instead of remembering complex command-line arguments, you can perform deep system repairs, cleanups, and diagnostics with a single keystroke.

## 🚀 Features

### 🛡️ Safety First
* **System Restore Point:** Create a restore point with one click before applying changes.

### 🔧 Repair & Fix
* **SFC Scannow:** Fixes corrupted system files.
* **DISM RestoreHealth:** Repairs the Windows System Image using Windows Update.
* **CHKDSK:** Checks and fixes file system errors on the C: drive.
* **Time Sync:** Forces synchronization with time servers to fix clock issues.
* **Windows Store Reset:** Fixes issues with the Microsoft Store and modern apps (`wsreset`).

### 🧹 Cleanup & Optimization
* **Turbo Temp Clean:** deeply cleans temporary files, prefetch, and cache to free up space.
* **Component Store Cleanup:** Removes obsolete Windows Updates (`WinSxS` folder).
* **Winget Upgrade:** Automatically detects and updates all installed applications via Windows Package Manager.
* **TCP Autotuning Disable:** Optimizes network stability for certain connections.

### 🌐 Network
* **Full Network Reset:** Flushes DNS, resets Winsock and IP stack to fix internet connectivity issues.

### 📊 Diagnostics
* **Battery Report:** Generates a detailed HTML report of battery health (for Laptops).
* **Disk Health:** Checks S.M.A.R.T. status of all connected drives.
* **RAM Test:** Launches the Windows Memory Diagnostic tool (`mdsched`).
* **WinSat:** Runs a system performance assessment (CPU, Disk, Graphics benchmarks).

## 📥 How to Use

1.  Download the `DimisM_Repair.bat` file.
2.  **Right-click** on the file.
3.  Select **"Run as Administrator"** (Required for repair commands).
4.  Choose an option from the menu by typing the corresponding number or letter.

## ⚠️ Disclaimer
This tool uses powerful built-in Windows commands. While it is designed to be safe (and includes a Restore Point feature), **please use it at your own risk**. Always backup your important data before running deep system repairs.

---
*Created by DimisM*
