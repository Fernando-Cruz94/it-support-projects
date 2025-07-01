# 🔧 Project – Driver Check Before Updating the BIOS

This project is part of my IT support portfolio. It documents the full process of verifying and updating system drivers before performing a BIOS update on a high-end PC. Keeping drivers up to date is a critical step to ensure compatibility and system stability—especially before flashing firmware.

> 📁 Folder includes the full project guide in PDF and screenshots in the `/images` folder.

---

## 💻 System Overview

- **Motherboard**: ASUS ROG STRIX Z690-A GAMING WIFI D4  
- **CPU**: Intel Core i9-12900K  
- **OS**: Windows 11 Pro (64-bit)  
- **Target BIOS Version**: 4301 (Released May 26, 2025)

---

## 🎯 Objective

- Verify all essential drivers are correctly installed and up to date.
- Replace any generic or outdated drivers with official versions from ASUS.
- Create a restore point before BIOS update to ensure system safety.

---

## 🛠️ Tools Used

- ⚙️ Windows Device Manager  
- 🔄 Windows Update (Optional Updates)  
- 🌐 [ASUS Driver Support](https://rog.asus.com/motherboards/rog-strix/rog-strix-z690-a-gaming-wifi-d4-model/helpdesk_download)  
- 🧰 [Snappy Driver Installer Origin](https://sdi-tool.org/)  
- 💾 System Restore utility  

---

## 🔎 Driver Validation Process

### 1. Check for missing drivers
`Settings > Windows Update > Advanced Options > Optional Updates`

### 2. Verify with Device Manager  
`Windows + X > Device Manager`

Check for key components:
- Intel(R) Management Engine Interface
- Intel I225-V LAN
- Intel WiFi 6 AX201
- Intel Bluetooth
- Realtek Audio
- SATA AHCI Controller

### 3. Compare vs ASUS support page  
Visit: [https://rog.asus.com](https://rog.asus.com)

---

## 📋 Final Driver Review Summary

| Component          | Status            | Action |
|--------------------|-------------------|--------|
| LAN (Ethernet)     | Newer version installed, but ASUS version used | ✅ Updated |
| Wi-Fi AX201        | Already up to date | ✅ No action |
| Bluetooth AX201    | Already up to date | ✅ No action |
| Realtek Audio      | Newer version installed | ✅ No action |
| SATA AHCI          | Generic Microsoft driver found | ✅ Updated |
| Intel ME (Chipset) | Outdated | ✅ Updated |

📸 See `/images/` folder for detailed screenshots of each driver state.

---

## 🔄 Restore Point and SDIO

Before updating anything:
- ✅ Created system restore point

Then used:
- ✅ Snappy Driver Installer Origin  
- Compared old/new versions  
- Selected and installed appropriate updates  
- Restarted the system

---

## 📘 References

- [ASUS Support – Z690-A Drivers](https://rog.asus.com/motherboards/rog-strix/rog-strix-z690-a-gaming-wifi-d4-model/helpdesk_download)  
- [Snappy Driver Installer Origin](https://sdi-tool.org/)  
- `Settings > Windows Update > Advanced Options > Optional Updates`  
- `Windows + X > Device Manager`

---

📄 **Full Documentation**: [Project Driver Check Before Updating the BIOS (PDF)](./Project%20Driver%20Check%20Before%20Updating%20the%20BIOS.pdf)  
📂 **Screenshots**: See [`/images`](./images) folder for visual proof of each step.
