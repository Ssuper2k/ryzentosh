# 💻 EFI for Dell Precision 5550 (macOS)

This repository contains a custom OpenCore EFI configuration for running macOS on the **Dell Precision 5550** with the following hardware:

## 🧰 System Specs

- **CPU**: AMD Ryzen 9 9950X  
- **GPU**: AMD Radeon 6900XT (16GiB)  
- **SSD**: Samsung 990 Pro 2TiB  
- **RAM**: 48GiB (2x24GiB @ 8000MTs)  
- **Display**: Samsun Odyssey 57" (PbP 3x)
- **macOS Version**: Sequoia 15.71  
- **OpenCore Version**: 1.05  

---

## ✅ What Works

- **Network**: *Intel Ethernet I225-V (2.5 Gbit):*
- **Bluetooth 5.0**: *(Asus Dongle AC55BT)*
- **Heyborad Media/Volume controls**
- **Video-output** DP + HDMI + usbC*
- **All/most USB ports**
- **SLEEP** after resume I loose anlalog sound, though

---

## ⚠️ Important Notes

- **SMBIOS**: Please generate your own SMBIOS data using [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) to avoid iCloud and serial number conflicts.


---

## 📁 Folder Structure

This repo contains the full EFI folder, including:
- `ACPI/`
- `Drivers/`
- `Kexts/`
- `OC/config.plist`

Make sure to mount your EFI partition and replace its contents with this folder.

Actualiza el nombre de tu CPU con:
https://github.com/corpnewt/CPU-Name

Also don't forget to  generate your own SMBIOS data

I used MacPro7,1

More info:

https://www.reddit.com/r/hackintosh/comments/1fdkkbc/updated_macos_ryzen_9950x/

---

## 🛠️ Credits

Thanks to the Hackintosh community and tools like OpenCore, Dortania guides, and GenSMBIOS.

---

## 📌 Disclaimer

This EFI is provided as-is for educational and testing purposes. Use at your own risk. Always back up your data before making system-level changes.

