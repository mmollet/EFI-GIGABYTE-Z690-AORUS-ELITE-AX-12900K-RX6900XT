# Gigabyte Z690 Aorus Elite DDR4 + i9 12900K + RX 6600 XT + Fenvi BCM94360NG

![about-12 3 1](https://user-images.githubusercontent.com/23700365/161353027-9aaeddf5-7457-49a8-b322-4e99ab94c679.png)

**Latest working macOS**: 12.4
<br>
**Current OpenCore**: 0.7.8

-> Important, Disable CSM and Secure Boot in Bios
-> You need to make SMBIOS SystemInfo Strings using genSMBIOS and edit the config.plist file.

## Complete hardware specs
- Intel i9 12900K @ Stock (All cores (P+E+HT) activated)
- Gigabyte Z690 Aorus Elite DDR4 @ BIOS F6
- RX 6600 XT - Arock Challenger 6600XT
- 2x 16Gb DDR4 4133Mhz Corsair Dominator XMP Enabled
- Fenvi BCM94360NG PCI-E Addon Card - Work OOB (https://www.amazon.de/dp/B081CFM2J4?ref_=cm_sw_r_cp_ud_dp_SZ9Z5ESKVWG71M838DBW)

## What works
- macOS Monterey 12.4
- Audio
- HDMI/DP (in dGPU - Works OOB)
- All USB ports
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Temperature monitoring for everything except GPU
- DRM content (Netflix, ATV+, Airplay 2 mirroring etc)
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't work
- Sleep? Never got the chance to test it, my hackintosh is up 24/7

## Kexts used:
- AppleALC.kext
- Lilu.kext
- LucyRTL8125Ethernet.kext
- SMCSuperIO.kext
- SMCProcessor.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext

## Geekbench Results:
- https://browser.geekbench.com/v5/cpu/11647562
- https://browser.geekbench.com/v5/compute/3921810
- https://browser.geekbench.com/v5/compute/3921809

## Thanks/Credits
- Thanks to Luchina-gabriel for the Base EFI !
- [Opencore Team](https://dortania.github.io/getting-started/)
- [BASE EFI - for 11th Intel Gen - Rocket Lake](https://github.com/luchina-gabriel/BASE-EFI-INTEL-DESKTOP-11THGEN-ROCKET-LAKE)
- tonymacx86.com - in special @etorix and @CaseySJ

## Discord - Universo Hackintosh
- [Access Discord](https://discord.universohackintosh.com.br)
