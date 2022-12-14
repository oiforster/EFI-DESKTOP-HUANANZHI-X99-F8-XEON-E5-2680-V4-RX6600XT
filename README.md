# Huananzhi X99-F8 + Xeon E5-2680 v4 + RX 6600 XT + Fenvi BCM94360NG

![Captura de Tela 2022-12-15 às 10 32 50](https://user-images.githubusercontent.com/120476538/207876445-2bf7e789-35ef-4d65-a2cd-f478c5a8f879.png)


**Latest working macOS**: 13.1
<br>
**Current OpenCore**: 0.8.7

## Complete hardware specs
- Intel Xeon E5-2680 v4
- Huananzhi X99-F8 @ BIOS (https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbEFqOXFadEdPTEhpUThWZFlmaHFQa21IdmVhUXxBQ3Jtc0ttaHQxX3R6NG5oUEZtWnhCa3NkTDRkYVVRTUtZZG5PcGpkRWJIbngwdzFYZV9ZTEZlalgwWlJCeDZzSFFLbFdVME9GdDRDajlSX2p3bUtkclhkUEJLZzdVZ2RPMU9vQWUtczdXeFlPYlBJYlJaRzdiTQ&q=https%3A%2F%2Fgithub.com%2Fluchina-gabriel%2Fyoutube-files%2Fraw%2Fmain%2FEFI-OC069-GL2.0-Generic-Catalina-e-BigSur.zip&v=zZPDmi02Kik)
- RX 6600 XT - JieShuo (Refurbished / Aliexpress) 
- 4x 8Gb DDR4 2133Mhz Atermite
- Wifi/BT replaced by Fenvi BCM94360NG - Work OOB

## What works
- macOS Ventura and macOS Monterey
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
- AirportBrcmFixup.kext
- AppleALC.kext
- AppleMCEReporterDisabler.kext
- CpuTscSync.kext
- Lilu.kext
- NVMeFix.kext
- RealtekRTL8111.kext
- RestrictEvents.kext
- USBInjectAll.kext
- VirtualSMC.kext
- WhateverGreen.kext
- XHCI-unsupported.kext

## Geekbench Results:
- https://browser.geekbench.com/v5/cpu/19168733
- https://browser.geekbench.com/v5/cpu/19168446
- https://browser.geekbench.com/v5/compute/6033679
- https://browser.geekbench.com/v5/compute/6033668

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [Gabriel Luchina](https://github.com/luchina-gabriel/)

## Discord - Universo Hackintosh
- [Access Discord](https://discord.universohackintosh.com.br)
