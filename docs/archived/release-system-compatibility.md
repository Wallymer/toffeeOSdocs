---
title: System Compatibility
---


*Archived and no longer updated by Wallymer. Applies to unicorn Development 1.6.1 and earlier.*

## unicorn (toffeeOS) system compatibility
Due to the upcoming [x86 build deprecation](https://github.com/onetwentyfour/unicorndocs/blob/main/x86-build-support.md), we recommend installing unicorn on a 64-bit processor. 

The requirements below are subject to change at any time.

## unicorn 1.6.1 and later

### RAM
- Minimum: 4GB
- Recommended: 8GB

### Components
- CPU: Intel CPU launched in 2013 or later; AMD A8 APUs released in 2014 and later, and Ryzen 1000 and later.
  - CPU and Motherboard (MBO) pairing must also support UEFI. CPU and MBO pairings without UEFI cannot boot the OS.
  - Intel processors from 2012 and earlier are no longer supported and will remain on unicorn 1.5 non-LTS.
  - We do not support AMD CPUs prior to Ryzen 1000 or AMD APUs prior to 2014 A8 due to technical limitations.
- GPU (64-bit only): NVIDIA GPU launched in 2014 or later.
  - Specifics: GT 705 or later, GTX 745 or later, and GTX Titan or later. 
  - GPU must support Vulkan.

### Storage
- Minimum storage space needed for install: 75 GB
- Recommended storage space (after install): 320+ GB HDD/SSD  
Fusion/Hybrid drives are not supported.  

## unicorn 1.5.x and earlier

### RAM
- Minimum: 728MB (32-bit), 2GB (64-bit)
- Maximum (32-bit only): 4GB
- Recommended: 4GB (both)

### Components
- CPU: Intel CPU launched in 2011 or later; AMD A8 APUs released in 2014 and later, and Ryzen 1000 and later.
  - CPU and Motherboard (MBO) pairing must also support UEFI. CPU and MBO pairings without UEFI cannot boot the OS.
  - We do not support the 2010 Intel Core 2 Duo or earlier due to technical limitations.
  - We do not support AMD CPUs prior to Ryzen 1000 or AMD APUs prior to 2014 A8 due to technical limitations.
- GPU (64-bit only): NVIDIA GPU launched in 2014 or later.
  - Specifics: GT 705 or later, GTX 745 or later, and GTX Titan or later. 

### Storage
- Minimum needed for install: 26GB (32-bit); 46GB (64-bit)
- Recommended storage: 256 GB HDD/SSD  
Fusion/Hybrid drives are no longer supported.  
