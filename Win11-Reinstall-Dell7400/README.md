# 💻 Project – Full Windows 11 Reinstallation on a Dell Latitude Laptop

This project documents the full process of reinstalling Windows 11 on a Dell Latitude 14 7400 2-in-1 laptop that had been inactive for two years. The system was outdated, with corrupted and unnecessary files, so I performed a **clean installation** and **driver reconfiguration** to restore full functionality.

---

## 🎯 Project Objectives

- Format the internal SSD drive
- Perform a clean installation of Windows 11 Pro
- Install essential drivers and updates
- Restore the laptop to a stable and usable state for academic or personal use

---

## 🖥️ System Specifications

| Component             | Details                              |
|----------------------|--------------------------------------|
| System Name          | FERNANDO_CRUZ                        |
| Manufacturer         | Dell Inc.                            |
| Model                | Latitude 7400 2-in-1                 |
| Processor            | Intel® Core™ i7-8665U (4C/8T @ 1.90GHz) |
| System Type          | x64-based PC                         |
| BIOS Version         | Updated from 1.17.0 → 1.34.0 (03/2025) |
| Windows Version      | Windows 11 Pro (Build 26100)         |

---

## 🛠️ Tools Used

- [Rufus](https://rufus.ie/) – USB bootable media creation
- [Windows 11 ISO](https://www.microsoft.com/software-download/windows11)
- Dell Support Assistant – Official driver updates
- [Snappy Driver Installer Origin](https://sdi-tool.org) – Driver detection and installation
- Windows Update – Patches and optional drivers

---

## 🧾 Installation Steps Summary

### Step 1: USB Bootable Creation

- Used Rufus to create a bootable USB with Windows 11 ISO.
- Selected GPT/UEFI configuration for compatibility.

### Step 2: OS Installation

- Booted from USB (F12).
- Deleted all partitions and created a new clean one.
- Installed Windows 11 from scratch.

### Step 3: Initial Setup

- Selected region, language, keyboard.
- Created a local account and configured privacy settings.
- Connected to Wi-Fi and finished initial boot.

### Step 4: Post-Installation

- Installed all updates from Windows Update.
- BIOS was updated automatically during this process.
- Created a restore point for system safety.

### Step 5: Driver Installation

- Used Dell Support Assistant to install missing drivers.
- Used Snappy Driver Installer as an additional check.
- Rebooted and verified all hardware was detected properly.

---

## ✅ Final Result

The Dell laptop is now running the latest version of **Windows 11 Pro**, with all drivers updated and a clean system ready for daily use. This project showcases key IT skills in:

- System formatting and OS reinstallation  
- BIOS update handling  
- Driver troubleshooting  
- Technical documentation

📄 [Read Full Documentation](Full%20Windows%2011%20Reinstallation%20on%20an%20DELL%20Laptop.pdf)

---

## 📁 Files Included

- `Full Windows 11 Reinstallation on an DELL Laptop.pdf` – Step-by-step detailed guide  
- `images/` – (Optional) Screenshots or photos of the installation process

---

## 🧠 Lessons Learned

- Importance of BIOS compatibility and driver updates
- Using restore points as a safety measure
- Documenting each step clearly to replicate the process on other devices

