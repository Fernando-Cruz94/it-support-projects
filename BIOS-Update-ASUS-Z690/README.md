# 🧠 BIOS Update Procedure for ASUS Z690-A + Intel Core i9-12900K

This project covers a complete and secure BIOS update process on a high-performance desktop PC. It is divided into two main stages:

1. ✅ Verifying and updating critical drivers  
2. ✅ Updating the BIOS using ASUS EZ Flash utility

The combination of both steps ensures system stability, prevents errors, and demonstrates responsible firmware management.

---

## 🖥️ System Information

| Component     | Specification |
|---------------|----------------|
| Motherboard   | ASUS ROG STRIX Z690-A GAMING WIFI D4 |
| CPU           | Intel Core i9-12900K |
| OS            | Windows 11 Pro (Build 22600) |
| RAM           | 64 GB DDR4 |
| BIOS Versions | 2103 → 4301 (May 26, 2025) |

---

## 📌 Step 1 – Pre-BIOS Driver Verification

Before updating the BIOS, I reviewed all important system drivers, especially:

- Intel Management Engine (IMEI)
- SATA AHCI Controller
- Intel LAN (I225-V)
- Intel WiFi & Bluetooth
- Realtek Audio

✅ I used **Windows Update**, **Device Manager**, and **ASUS Support Site**  
✅ Missing/outdated drivers were installed manually or via **Snappy Driver Installer Origin**  
✅ A **restore point** was created before proceeding

📄 Full Details: [Driver Check Before BIOS Update (PDF)](https://github.com/Fernando-Cruz94/it-support-projects/blob/main/Driver-Check-BIOS/Project%20Driver%20Check%20Before%20Updating%20the%20BIOS.pdf)  
📂 Screenshots available in the [`images`](./images) folder.

---

## 🔄 Step 2 – BIOS Update Procedure

The update was performed using **ASUS EZ Flash 3 Utility** built into the BIOS interface.

### 🧭 Procedure Summary

1. Identify current BIOS version: `msinfo32` or `wmic bios get smbiosbiosversion`
2. Download BIOS 4301 `.CAP` file from [ASUS Support](https://rog.asus.com/)
3. Format USB drive as FAT32 and copy the `.CAP` file to the root directory
4. Boot into BIOS → Enter Advanced Mode (F7) → Tool → EZ Flash 3
5. Select file from USB → Start update (2–5 min)
6. Reboot, load defaults, confirm BIOS version in Windows

---

## 🧠 What This Project Demonstrates

- 💡 Safe firmware handling and BIOS flashing  
- 🔍 Proactive driver maintenance  
- 🛠️ Use of vendor tools (ASUS, Windows, SDIO)  
- 🧾 Professional documentation and screenshots  
- 🧰 Risk mitigation with system restore points  

This type of real-world project is essential for IT support roles, particularly in system administration and troubleshooting hardware-level issues.

---

## 📘 References

- [ASUS Support – BIOS & Drivers](https://rog.asus.com/motherboards/rog-strix/rog-strix-z690-a-gaming-wifi-d4-model/helpdesk_download)  
- [Snappy Driver Installer Origin](https://sdi-tool.org/)  
- `Settings > Windows Update > Advanced Options > Optional Updates`  
- `Windows + X > Device Manager`  
- `msinfo32` and `wmic bios` to verify versions  

---

📂 **Screenshots**: Check the [`images`](./images) folder  
📄 **Full Documentation**:  
- [Driver Check (PDF)](https://github.com/Fernando-Cruz94/it-support-projects/blob/main/Driver-Check-BIOS/Project%20Driver%20Check%20Before%20Updating%20the%20BIOS.pdf)  
- [BIOS Update (PDF)](./BIOS%20Update%20Procedure%20for%20ASUS%20Z690-A%20with%20Intel%20Core%20i9-12900K.pdf)
