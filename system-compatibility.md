## unicorn (toffeeOS) system compatibility
unicorn 1.3.7 (Beta Ring), unicorn 1.3.8 and unicorn 1.4 (Canary Ring), the most recent releases, are officially compatible with the following system configurations:

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
