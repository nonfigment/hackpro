# Hackintosh, powered by OpenCore on a ROG STRIX B460-I + i5-10600

## Current config (at the time of writing):
* Mac Model: iMac20,1 (Retina 5K, 2019)
* MoBo: [ASUS ROG STRIX B460-I GAMING WiFi](https://rog.asus.com/motherboards/rog-strix/rog-strix-b460-i-gaming-model/spec/)
* CPU: [Intel i5-10600 @3.2GHz](https://www.intel.com/content/www/us/en/products/sku/199273/intel-core-i510600-processor-12m-cache-up-to-4-80-ghz/specifications.html)
* GPU: iGPU (UHD630)
* PSU: Corsair SF450
* WiFi: Broadcom BCM94360NG (replaced stock Intel AX200 which is not supported [(see the Dortania Wireless Buyers Guide)](https://dortania.github.io/Wireless-Buyers-Guide/unsupported.html#supported-chipsets))  
* RAM: Transcend JM3200HLE 2x16 
* NVMe: ADATA SX8200PNP 1Tb
* SATA: SSD Samsung 860EVO 1Tb + HDD HGST 1TB for backups

## What is working:

* System boots
* Display connection via DP/HDMI
* WiFi
* Bluetooth
* USB (incl. 3.2 Gen 2x2 20gbps)
* Apple features: Universal Control, Handoff, AirDrop, iServices.

## Not working:
* On-board audio (was working, but FakePCII caused system to crash right after boot).

## Repository guide:
### Branches:
* Master/Main: the current EFI, which I use right now.
* Experimental: the experimental branch fotr the tests/fixes. Probably stable. 
* AMD: I've also managed to build a Hackintosh on an AMD platform, using B450/B550 chipset-based motherboards with R5-2600X and RX5700XT, so, here's the last working EFI for them. I've abandoned it, and keeping a copy if I ever need it. 

## References:

* [Jann Röder repo] (https://github.com/roederja/asus-rog-strix-b460I-hackintosh)(the ultimate guide for the same motherboard/CPU, a million thanks!)
* [OpenCore Install Guide by Dortania](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html)



