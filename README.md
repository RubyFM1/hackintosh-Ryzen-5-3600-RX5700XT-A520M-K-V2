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
