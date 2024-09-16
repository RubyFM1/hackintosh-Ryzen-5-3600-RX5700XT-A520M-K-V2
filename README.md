 ![photo](https://github.com/RubyFM1/phototototot/blob/main/Снимок%20экрана%202024-09-16%20в%2017.11.31.png)
 # Update
 **V3 Ready**
 
 What's new?

1. SMBIOS updated, was iMacPro 7.1, became iMac 19.1
2. Added several kext files for stable operation of AMD processors
3. Rewritten config.plist file, more organized
4. Updated all kext files to the latest version
5. Updated Opencore to the latest version available
6. In the Drivers folder I left only the most necessary drivers
7. Improved overall system stability

This version is configured for ryzen5 3600, rx5700xt, a520m k v2 system, but you can use this EFI with rx 5xxx or 6xxx video cards without additional customization, in order to adapt this configurator for other ryzen processors you need to make some changes in config.plist, if you don't know it, it's better not to do anything and ask for advice on forums.

**What about MasOS 15?**

At this time installing macOS 15 on this configuration is not available for reasons unknown to me, I have been trying to resolve the issue for several days but without success, if you have any information regarding installing macOS 15 on this configuration please let me know.
As soon as I find a solution to this problem, I will upload a new version under macOS 15.

# Description
This EFI folder is only suitable for this configuration:
CPU - Ryzen 5 3600
GPU - RX 5700 XT
MB - Gigabyte A520M K V2
if you try to use this folder with a different configuration, you will get a kernel panic, and everything like that, the system simply won’t start
# OS updates
To update your system, no additional steps are required in the bootloader files, installed from the Apple app store
# SMBIOS
iMac 19,1
I advise you to change the device serial number in the config.plist file
# What works?
Internet, sound, all other basic functions of a regular computer, no additional kext files are required.
All Apple services are working fine, no critical errors were found.
# How to install?
Replace all files and folders in your EFI folder with those you download here
