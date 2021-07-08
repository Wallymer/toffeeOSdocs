## Version History
For beta (more stable, released whenever) and canary (dev branch, 3 times a week builds) 

## Canary Ring
### unicorn 1.4 (latest release: July 8, 2021)
Before installing this release, please check the [system compatibility Doc](https://github.com/onetwentyfour/unicorndocs/blob/main/system-compatibility.md).
- we're internally processing the final changelog for 1.4 that will be shown in the update window prompt for those on Beta channel
  - of the internal release steps, we are now on step 3 of 6 (weeks). aiming for a release target of late July, early August
- pushing security updates to main for April-July 2021.
  - backported to unicorn 1.3.4, since final update did not release on April 2, 2021 as originally intended.
- fixes for AMD processors
- updated Toffee Server to sv1.4
  - Active Directory integration is now supported.

## Beta Ring
### unicorn 1.3.8 (latest release: July 8, 2021)
The 1.3.8 soak test is over, users must update to the new Beta Ring build by July 9, 2021, to continue receiving software support.
- Security updates pushed.
- Visual updates to Settings
  - Consolidated sidebar into new categories (documentation to be updated)
  - Redesigned update settings
  - Build string now visible in Settings
  - Confidentiality notice is now available in Settings > About my system > Testers > Confidentiality
- Compatibility patch implemented for 2010 Intel Core 2 Duo processors.

### unicorn 1.3.7 (test ending: July 9, 2021)
Update to unicorn 1.3.8 by July 9, 2021, to continue receiving software support.
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
