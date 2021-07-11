## unicorn (toffeeOS) system compatibility
Due to the upcoming [x86 build deprecation](https://github.com/onetwentyfour/unicorndocs/blob/main/x86-build-support.md), we recommend installing unicorn on a 64-bit processor. 

The requirements below are subject to change at any time.

## unicorn 1.5 Dev Builds
unicorn 1.5 Dev 1 is officially compatible with the following system configurations:

### RAM
- Minimum: 512 MB (32-bit), 2GB (64-bit)
- Maximum (32-bit only): 4GB
- Recommended: 4GB (both)

### Components
- CPU: Intel CPU launched in 2010 or later; AMD A8 APUs released in 2014 and later, and Ryzen 1000 and later.
  - CPU must also support UEFI
  - For reference purposes only - we do not support the 2009 Intel Core 2 Duo or earlier due to processor issues.
- GPU (64-bit only): NVIDIA GPU launched in 2014 or later.
  - Specifics: GT 705 or later, GTX 745 or later, and GTX Titan or later. 

### Storage
- Minimum needed for install: 26GB (32-bit); 46GB (64-bit)
- Recommended storage: 256 GB HDD/SSD (or comparable Fusion/Hybrid drive)

## unicorn 1.4 Beta Builds
unicorn 1.4 Beta 1 is officially compatible with the following system configurations:

### RAM
- Minimum: 512 MB (32-bit), 2GB (64-bit)
- Maximum (32-bit only): 4GB
- Recommended: 4GB (both)

### Components
- CPU: Intel CPU launched in 2010 or later; AMD A8 APUs released in 2014 and later, and Ryzen 1000 and later.
  - CPU must also support UEFI
  - For reference purposes only - we do not support the 2009 Intel Core 2 Duo or earlier due to processor issues.
- GPU (64-bit only): NVIDIA GPU launched in 2014 or later.
  - Specifics: GT 705 or later, GTX 745 or later, and GTX Titan or later. 

### Storage
- Minimum needed for install: 20GB (32-bit); 40GB (64-bit)
- Recommended storage: 256 GB HDD/SSD (or comparable Fusion/Hybrid drive)

### Not currently supported
- GPU: All NVIDIA RTX cards (2080 or newer); All AMD cards
- MBO: All ASUS Motherboards manufactured prior to 2018

## unicorn 1.3.8 Beta 2 and earlier
unicorn 1.3.8 Beta 2 is officially compatible with the following system configurations:

### RAM
- Minimum: 512 MB (32-bit), 1 GB (64-bit)
- Maximum (32-bit only): 4 GB
- Recommended: 4 GB (both)

### Components
- CPU: Intel CPU launched in 2010 or later.
  - For reference purposes only - we do not support the 2009 Intel Core 2 Duo or earlier due to processor issues.
- GPU (64-bit only): NVIDIA GPU launched in 2014 or later.
  - Specifics: GT 705 or later, GTX 745 or later, and GTX Titan or later. 

### Storage
- Minimum needed for install: 16GB (32-bit); 32GB (64-bit)
- Recommended storage: 128 GB HDD/SSD (or comparable Fusion/Hybrid drive)

### Not currently supported
- TPM: Trusted Platform Module (all iterations)
  - unicorn will still install on TPM-enabled systems, but the security benefits of having such a module will not be present.
  - support for TPM is coming in a future update.
- CPU: All AMD CPUs
  - a fix for AMD CPUs is coming in a future update.
  - Workaround: Run toffeeOS 1.3.4, which was released prior to 1.3.6 and did not include the changes to supported processors.
- GPU: All NVIDIA RTX cards (2080 or newer); All AMD cards
- MBO: All ASUS Motherboards manufactured prior to 2018
