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

## Important:

Remember to fill-in fields in PLatformInfo section, there are placeholders, so it will not work until you insert your data. [More on this.](https://github.com/nonfigment/hackpro/wiki/PlatformInfo-placeholders)

## References:

* [Jann Röder repo](https://github.com/roederja/asus-rog-strix-b460I-hackintosh) (the ultimate guide for the same motherboard/CPU, a million thanks!)
* [OpenCore Install Guide by Dortania](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html)



