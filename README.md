 ![photo_2023-10-24 12 54 22](https://github.com/RubyFM1/hackintosh-Ryzen-5-3600-RX5700XT-A520M-K-V2/assets/145806846/dfa53112-53ba-4a45-ba7d-7e0d8c81f9a5)
 # Update
 **V3 Ready**
 What's new?

SMBIOS updated, was iMacPro 7.1, became iMac 19.1
Added several kext files for stable operation of AMD processors
Rewritten config.plist file, more organized
Updated all kext files to the latest version
Updated Opencore to the latest version available
In the Drivers folder I left only the most necessary drivers
Improved overall system stability

**What about MasOS 15?**

At this time installing macOS 15 on this configuration is not available for reasons unknown to me, I have been trying to resolve the issue for several days but without success, if you have any information regarding installing macOS 15 on this configuration please let me know.
As soon as I find a solution to this problem, I will upload a new version under macOS 15.

 **What's new?**
**Install the new version in the release** 
You will probably have to do USB Mapping using USBToolBox, otherwise there is a chance that nothing will work 
1. The previous version had some critical bugs that caused kernel panic, the new version is adapted for motherboards: B550, and A520 (including different versions and modifications of these motherboards).
2. Removed all unnecessary kext files that made no sense or caused errors 
3. Updated version of OpenCore to the latest actual version
4. Updated kext files to the latest actual versions.
5. Rewritten config.plist file

This version is configured for ryzen5 3600, rx5700xt, a520m k v2 system, but you can use this EFI with rx 5xxx or 6xxx video cards without additional customization, in order to adapt this configurator for other ryzen processors you need to make some changes in config.plist, if you don't know it, it's better not to do anything and ask for advice on forums.
# Description
This EFI folder is only suitable for this configuration:
CPU - Ryzen 5 3600
GPU - RX 5700 XT
MB - Gigabyte A520M K V2
if you try to use this folder with a different configuration, you will get a kernel panic, and everything like that, the system simply won’t start
# OS updates
To update your system, no additional steps are required in the bootloader files, installed from the Apple app store
# SMBIOS
iMacPro 1,1
I advise you to change the device serial number in the config.plist file
# What works?
Internet, sound, all other basic functions of a regular computer, no additional kext files are required.
All Apple services are working fine, no critical errors were found.
# How to install?
Replace all files and folders in your EFI folder with those you download here
# Other
The installed kext files related to monitoring processor temperatures do not work on versions of MacOS Sonoma, Ventura, and there is no need for them, but in order not to break anything, it is better to leave them as they are, they do not affect the operation of the system in any way
# P.S.
In kext files there is an error in the form of different files performing the same task, it is better not to touch anything, everything works fine anyway and does not cause errors
