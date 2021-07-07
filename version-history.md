## Version History
For beta (more stable, released whenever) and canary (dev branch, 3 times a week builds) 

## Canary Ring
There are currently two ongoing tests in the Canary Ring.

### unicorn 1.4 (latest release: July 2, 2021)
Before installing this release, please check the [system compatibility Doc](https://github.com/onetwentyfour/unicorndocs/blob/main/system-compatibility.md).
- pushing security updates to main for April-July 2021.
  - backported to unicorn 1.3.4, since final update did not release on April 2, 2021 as originally intended.
- fixes for AMD processors
- updated Toffee Server to sv1.4
  - Active Directory integration is now supported.

### unicorn 1.3.8 (latest release: July 7, 2021)
Users may select to participate in 1.3.8's soak test or choose to stay on the more stable 1.3.7 build for testing purposes.
- Security updates pushed.
- Visual updates to Settings
  - Consolidated sidebar into new categories (documentation to be updated)
  - Redesigned update settings
  - Build string now visible in Settings
  - Confidentiality notice is now available in Settings > About my system > Testers > Confidentiality
- Compatibility patch implemented for 2010 Intel Core 2 Duo processors.

## Beta Ring
### unicorn 1.3.7 (current test; latest release: July 7, 2021)
- Prepping for April-July 2021 security updates
- Beginning to push visual updates to Settings to main
- Updated Toffee Server to sv1.3.5
  - includes aforementioned security update prep
  - rebuild due to serious error where, in some cases, GUI would crash upon adding a new user to the system
  - patched additional graphical bugs

### unicorn 1.3.6 (test ended: March 30, 2021)
- Dropped support for most processors released in 2009 and prior (.05% of our user base). These devices are now unsupported though can still run toffeeOS 1.3.5 and earlier, and they won't be covered with security updates after April 2nd, 2021.
  - To clarify, Intel processors launched in 2010 and later is still fully supported. AMD processors, however, are currently not compatible.
- Performance improvements for devices released in 2010 and later.
- Important security fixes for January-March 2021. These have been backported to unicorn 1.3.4 for the aforementioned unsupported devices.
- Updated Toffee Server to sv1.3.4.
