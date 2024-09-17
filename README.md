![photo](https://github.com/RubyFM1/dawfefsdfs/blob/main/images.png)
# Description
**This is a universal EFI for all versions of MacOS (Catalina and higher)**

All kext files are updated to the latest versions, Opencore also has the latest version

This EFI version is for configurations only:
1. Ryzen 5 3600
2. RX5700XT
3. GIGABYTE A520M K V2 (and B550, A520, including different versions and modifications of these motherboards).

**If you try to use this folder with a different configuration, you will get a kernel panic, and everything like that, the system simply won’t start**

# OS updates
You don't need any extra steps for updates, updating is done through settings or through the App Store
# SMBIOS
MacPro 7.1
# What works?
1. iCloud
2. All Apple services
3. Ethernet (not including Wi-Fi, because Apple systems do not support all Wi-Fi adapters, you will have to configure for your own adapters, also with the release of macOS Sequoia many network adapters are no longer supported)
# What's not working?
1. Wi-Fi
2. Sidecar
3. Bluetooth
4. Maybe sleep
# How to install?
Replace all files and folders in your EFI folder with those you download here
# Thanks
[@sileshn](https://github.com/sileshn) - his EFI helped solve the problem of upgrading to macOS 15 Sequoia by borrowing some settings that eventually helped the system upgrade
