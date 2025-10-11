![photo](https://github.com/RubyFM1/hackintosh-Ryzen-5-3600-RX5700XT-A520M-K-V2/blob/main/images.png?raw=true)
# Description
**This is a universal EFI for all versions of MacOS (Catalina and higher)**

All kext files are updated to the latest versions, Opencore also has the latest version

This EFI version is for configurations only:
1. Ryzen 5 3600
2. RX5700XT
3. GIGABYTE A520M K V2 (and B550, A520, including different versions and modifications of these motherboards, however, it requires additional configuration)

**If you try to use this folder with a different configuration, you will get a kernel panic, and everything like that, the system simply won’t start**

# MacOS Tahoe Update Info
**Sound may not work on ALC897/887, use [THIS](https://olarila.com/topic/42836-easy-audio-solution-on-hackintosh-on-macos-tahoe/) guide**

To update to MacOS 26 (Tahoe), you need to follow a few important steps, otherwise you will not be able to update
1. Disable Whatevergreen.kext in config.plist by switching it to Disable
2. Create your USBMap.kext using the guide [Corpnewt](https://github.com/corpnewt/USBMap)
3. Start the system update. After the update, you can enable Whatevergreen.kext in config.plist

# OS updates
You don't need any extra steps for updates, updating is done through settings or through the App Store
# SMBIOS
MacPro 7.1
# What works?
1. iCloud
2. All Apple services
3. Wired Internet (except for WiFi and Bluetooth, you need to configure EFI for your WiFi adapter yourself, since I don't need Bluetooth or WiFi, I didn't configure anything)
4. Sound
5. Everything else except for what is listed below
# What's not working?
1. Wi-Fi
2. Sidecar
3. Bluetooth
4. Sleep (in some cases, the system may freeze after waking up from sleep mode)
# How to install?
Place the folder downloaded from the Releases section into your EFI partition.
# Thanks
[@sileshn](https://github.com/sileshn) - his EFI helped solve the problem of upgrading to macOS 15 Sequoia by borrowing some settings that eventually helped the system upgrade
