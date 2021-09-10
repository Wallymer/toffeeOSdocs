## Version History (Archived)
For beta (more stable, current version), canary (semi-stable, tests of point releases for current version), dev (upcoming version, definitely not stable) rings.

## Dev Ring
### unicorn 1.6 Dev 1 [Build 16D1831] (latest release: August 31, 2021)
Before installing this release, please check the [changes to 1.6 system compatibility](https://github.com/OneTwentyFour/unicorndocs/blob/main/changes-to-system-compatibility-1.6.md) and [version support](https://github.com/onetwentyfour/unicorndocs/blob/main/version-support.md) docs.

**This build is not available for x86 testers.**

- Refinements to user interface
- Bug fixes

## Canary Ring
### unicorn 1.5.1 Canary 1 [Builds 15C1831 and 15C1831-x86] (latest release: August 31, 2021)
Before installing this release, please check the [system compatibility](https://github.com/onetwentyfour/unicorndocs/blob/main/system-compatibility.md) and [version support](https://github.com/onetwentyfour/unicorndocs/blob/main/version-support.md) docs.

- bug fixes

## Beta Ring
### unicorn 1.5 Beta 1 [Builds 15B1831 and 15B1831-x86] (latest release: August 31, 2021)
Before installing this release, please check the [system compatibility](https://github.com/onetwentyfour/unicorndocs/blob/main/system-compatibility.md) and [version support](https://github.com/onetwentyfour/unicorndocs/blob/main/version-support.md) docs.

- We've raised the minimum RAM requirements to 728MB for the 32-bit builds. 4GB remains as the absolute maximum RAM supported on 32-bit systems.
  - this is in preparation for the [32-bit build deprecation](https://github.com/onetwentyfour/unicorndocs/blob/main/x86-build-support.md) happening some time this year.
- PS/2 port devices are now supported
- ASUS motherboards are now supported
- toffeesync 2.0 is here! But, there's one problem: the name doesn't make sense... it's for syncing your phone to your computer, not the other way around as the name implies. So, we're changing the name! *drumroll please* Introducing "Syncfon", a new way to sync between devices running unicorn and narwhal.
  - the app will be distributed as "syncfon" going forward!
  - this feature is not available on x86 builds.
- Native Markdown support in the "Project Scratchpad" app (we used it to edit this changelog for GitHub! Hi GitHub!)
- visual changes to user interface
- Made changes to how currency is handled in Calculator
- Added tip calculation to Calculator for feature parity with narwhal.
- fixed an issue with memory leaks when opening the browser
- security updates from May 2021-July 2021 have been bundled with this update.
- dropped support for 2010 Intel processors, including the 2010 Intel Core 2 Duo
- (x86 only) Support for ISOs has been deprecated and will no longer be distributed. OTA updates are the only way to update x86 builds.
- (x86 only) Server Communicator in x86 is deprecated, but will continue to work until 1.6 reaches a user's selected testing ring and will be removed upon updating.

___

## Unsupported Build Changelogs
### unicorn 1.5 Dev 8 [Build 15D8804] (latest release: August 4, 2021)
Before installing this release, please check the [system compatibility](https://github.com/onetwentyfour/unicorndocs/blob/main/system-compatibility.md) and [version support](https://github.com/onetwentyfour/unicorndocs/blob/main/version-support.md) docs.

- Updated Project Scratchpad icons
- Made changes to how currency is handled in Calculator
- Added tip calculation to Calculator for feature parity with narwhal.

### unicorn 1.5 Dev 7 [Build 15D7801] (test ended: August 4, 2021)
- Bug fixes
- Native Markdown support in the "Project Scratchpad" app.
- Performance improvements for 2013/2014 computers (apologies for that!)
- ASUS Motherboard fix

### unicorn 1.5 Dev 6 [Build 15D6731] (test ended: August 1, 2021)
- Merged toffeesync mobile device syncing between unicorn and narwhal to the dev branch, meaning this is now accessible to all Dev testers.
  - This feature is not available on x86 builds.

### unicorn 1.5 Dev 5 (test ended: July 30, 2021)
- Ported 1.4.1 Privacy Hub and Device Type features to 1.5 Dev Channel.

### unicorn 1.5 Dev 4 (test ended: July 28, 2021)
- fixed an issue with memory leaks when opening the browser
- dropped support for 2010 Intel processors, including the 2010 Intel Core 2 Duo
- (x86 version only) fixed an issue with toffeesync-x86 package refusing to update

### unicorn 1.5 Dev 3 (test ended: July 21, 2021)
- We've raised the minimum RAM requirements to 728MB for the 32-bit builds. 4GB remains as the absolute maximum RAM supported on 32-bit systems.
  - this is in preparation for the [32-bit build deprecation](https://github.com/onetwentyfour/unicorndocs/blob/main/x86-build-support.md) happening some time this year.
- fixed an issue with PS/2 devices not working after a power failure.
- fixed a user interface bug that affected redesigned apps in this update, specifically in Planner.

### unicorn 1.5 Dev 2 (test ended: July 17, 2021)
- PS/2 port devices are now supported
- visual changes to user interface

### unicorn 1.5 Dev 1 (test ended: July 15, 2021)
- undisclosed feature update (private developer release)
- Experimental support update for PS/2 port devices

### unicorn 1.4.2 Canary 2 Release 2 (x86 only) [Build 14C2816R2] (latest release: August 16, 2021)
Before installing this release, please check the [system compatibility](https://github.com/onetwentyfour/unicorndocs/blob/main/system-compatibility.md) and [version support](https://github.com/onetwentyfour/unicorndocs/blob/main/version-support.md) docs.

- we recommend all users update to this release immediately.
- kernel panic fix for x86 systems.
- immediate security patch for web browser on x86 systems.

### unicorn 1.4.2 Canary 2 [Build 14C2801] (latest release: August 4, 2021)
Before installing this release, please check the [system compatibility](https://github.com/onetwentyfour/unicorndocs/blob/main/system-compatibility.md) and [version support](https://github.com/onetwentyfour/unicorndocs/blob/main/version-support.md) docs.

- updated Settings app to fix crashing bug when opening Content pane.

### unicorn 1.4.2 Canary 1 [Build 14C1801] (test ended: August 4, 2021)
- Performance improvements for 2015/2016 processors.
- ASUS Motherboard fix (backported from 1.5 Dev 7)

### unicorn 1.4.1 Canary 7 (Beta Release Candidate 2) [Build 14C7BRC2] (test ended and moved to Beta: August 1, 2021)
This release fixes some bugs that were reported to us by testers. Build 14C7BRC2 is now available for Canary branch

**[Draft Changelog]** This update is primarily focused on adding Privacy-centered features we were unable to add in unicorn's 1.4 Beta release.  
- New privacy features for all users include...
  - Mic Privacy: Microphone disabled at certain times or, better yet, all the time. Searches on web search engines can also be routed through an onboard VPN to hide your IP address and search history.
  - Location Privacy: Choice between approximate (at either a state or country level) and precise locations.
  - Camera Privacy: Software can discern what port a camera is plugged into and shut it off automatically during certain times (or all the time).
  - Transparency: There is a new Transparency menu in Settings which details Mic, Location, and Camera usage for up to 60 days after it is requested by apps on your computer.
- Renamed Privacy settings tile to Privacy Hub
- fixed issue with Privacy Hub not correctly displaying the history and usage of location requests in Transparency
- Other misc fixes for Privacy Hub
- We now require Wi-Fi g/n/ac/ax or later cards, as a rollback to a change we made in 1.4 Beta 1 (and its Canary builds).
- fixed issue with battery percentage not displaying correctly on certain resolutions
- the battery icon will now be prioritized in the Status Area when the device type "Laptop" is selected and a battery is detected.
- IoT devices can be auto disconnected from the internet during set routines.
- You can now set your Device Type at any time in Settings.
- (x86 version only) fixed an issue with toffeesync-x86 package refusing to update

### unicorn 1.4.1 Canary 6 (Beta Release Candidate 1) (latest release: July 29, 2021)
**[Draft Changelog]** This update is primarily focused on adding Privacy-centered features we were unable to add in unicorn's 1.4 Beta release.  
- New privacy features for all users include...
  - Mic Privacy: Microphone disabled at certain times or, better yet, all the time. Searches on web search engines can also be routed through an onboard VPN to hide your IP address and search history.
  - Location Privacy: Choice between approximate (at either a state or country level) and precise locations.
  - Camera Privacy: Software can discern what port a camera is plugged into and shut it off automatically during certain times (or all the time).
  - Transparency: There is a new Transparency menu in Settings which details Mic, Location, and Camera usage for up to 60 days after it is requested by apps on your computer.
- Renamed Privacy settings tile to Privacy Hub
- fixed issue with Privacy Hub not correctly displaying the history and usage of location requests in Transparency
- Other misc fixes for Privacy Hub
- We now require Wi-Fi g/n/ac/ax or later cards, as a rollback to a change we made in 1.4 Beta 1 (and its Canary builds).
- fixed issue with battery percentage not displaying correctly on certain resolutions
- the battery icon will now be prioritized in the Status Area when the device type "Laptop" is selected and a battery is detected.
- IoT devices can be auto disconnected from the internet during set routines.
- You can now set your Device Type at any time in Settings.
- (x86 version only) fixed an issue with toffeesync-x86 package refusing to update

### unicorn 1.4.1 Canary 5 (test ended: July 28, 2021)
- (x86 version only) fixed an issue with toffeesync-x86 package refusing to update

### unicorn 1.4.1 Canary 4 (test ended: July 21, 2021)
- fixed issue with battery percentage not displaying correctly on certain resolutions
- the battery icon will now be prioritized in the Status Area when the device type "Laptop" is selected and a battery is detected.

### unicorn 1.4.1 Canary 3 (test ended: July 17, 2021)
- fixed issue with Privacy Hub not correctly displaying the history and usage of location requests in Transparency
- Wi-Fi "g"-standard cards will now work as intended

### unicorn 1.4.1 Canary 2 (test ended: July 15, 2021)
- Renamed Privacy settings tile to Privacy Hub
- Bug fixes for Privacy Hub
- We now require Wi-Fi g/n/ac/ax or later cards, as a rollback to a change we made in 1.4 Beta 1 (and its Canary builds).

### unicorn 1.4.1 Canary 1 (test ended: July 12, 2021)
This update is focused on adding Privacy-centered features we were unable to add in unicorn's 1.4 Beta release.  
- New privacy features for all users include...
  - Mic Privacy: Microphone disabled at certain times or, better yet, all the time. Searches on web search engines can also be routed through an onboard VPN to hide your IP address and search history.
  - Location Privacy: Choice between approximate (at either a state or country level) and precise locations.
  - Camera Privacy: Software can discern what port a camera is plugged into and shut it off automatically during certain times (or all the time).
  - Transparency: There is a new Transparency menu in Settings which details Mic, Location, and Camera usage for up to 60 days after it is requested by apps on your computer.
- IoT devices will receive further updates to Privacy in Canary 4 (pushed back). 

### unicorn 1.4.1 Beta 2 [Build 14B2804] (unsupported as of: September 1, 2021)
Before installing this release, please check the [system compatibility](https://github.com/onetwentyfour/unicorndocs/blob/main/system-compatibility.md) and [version support](https://github.com/onetwentyfour/unicorndocs/blob/main/version-support.md) docs.

- updated Settings app to fix crashing bug when opening Content pane. (backported from 1.4.2)

### unicorn 1.4.1 Beta 1 [Build 14B1801] (test ended: August 4, 2021)
This update is primarily focused on adding Privacy-centered features we were unable to add in unicorn's 1.4 Beta release.  
- New privacy features for all users include...
  - Mic Privacy: Microphone disabled at certain times or, better yet, all the time. Searches on web search engines can also be routed through an onboard VPN to hide your IP address and search history.
  - Location Privacy: Choice between approximate (at either a state or country level) and precise locations.
  - Camera Privacy: Software can discern what port a camera is plugged into and shut it off automatically during certain times (or all the time).
  - Transparency: There is a new Transparency menu in Settings which details Mic, Location, and Camera usage for up to 60 days after it is requested by apps on your computer.
- Renamed Privacy settings tile to Privacy Hub
- fixed issue with Privacy Hub not correctly displaying the history and usage of location requests in Transparency
- Other misc fixes for Privacy Hub
- We now require Wi-Fi g/n/ac/ax or later cards, as a rollback to a change we made in 1.4 Beta 1 (and its Canary builds).
- fixed issue with battery percentage not displaying correctly on certain resolutions
- the battery icon will now be prioritized in the Status Area when the device type "Laptop" is selected and a battery is detected.
- IoT devices can be auto disconnected from the internet during set routines.
- You can now set your Device Type at any time in Settings.
- (x86 version only) fixed an issue with toffeesync-x86 package refusing to update

### unicorn 1.4 Beta 4 [Build 14B4729] (latest release: July 29, 2021)
- Backported Privacy Hub IoT device updates

### unicorn 1.4 Beta 3 (test ended: July 28, 2021)
- Kernel patch
- Fixed an issue with IoT devices not properly detecting an available internet connection.

### unicorn 1.4 Beta 2 (test ended: July 15, 2021)
- Bug fixes.

### unicorn 1.4 Beta 1 (test ended: July 11, 2021)
- Kernel patch
- IoT devices will now automatically recommend using Wi-Fi networks with "IoT" in their name (no matter the casing)
- Wi-Fi 4 or later (n/ac/ax) is required at minimum for cards to be compatible with unicorn 1.4.
  - You will still be able to connect to networks using Wi-Fi 3 and prior (a/b/g), but unicorn will no longer recognize these cards as valid.
  - We made this change for compatibility reasons. We're big believers in backwards compatibility, so this change is a sad one for us to make unfortunately. It is what it is, I suppose.
- Fixed an issue relating to Settings (ported from 1.3.8-b02)
- Graphics cards with more than 2GB of VRAM will no longer have graphic errors when entering Settings (sorry about that) (ported from 1.3.8 Beta 2)
- AMD processors now compatible: A8 APUs released in 2014 and later, and Ryzen 1000 and later.
- pushing security updates to main for April-July 2021.
  - backported to unicorn 1.3.4, since final update did not release on April 2, 2021 as originally intended.
- fixes for AMD processors
- updated unicorn Server to sv1.4
  - Active Directory integration is now supported.

### unicorn 1.3.8 Beta 2 (test ended: July 11, 2021)
- Bug fixes
  - Settings now functions normally when entering the Network tab.
- Graphics cards with more than 2GB of VRAM will no longer have graphic errors when entering Settings (sorry about that)

### unicorn 1.3.8 Beta 1 (test ended: July 8, 2021)
- Security updates pushed.
- Visual updates to Settings
  - Consolidated sidebar into new categories (documentation to be updated)
  - Redesigned update settings
  - Build string now visible in Settings
  - Confidentiality notice is now available in Settings > About my system > Testers > Confidentiality
- Compatibility patch implemented for 2010 Intel Core 2 Duo processors.

### unicorn 1.3.7 (test ended: July 8, 2021)
- Prepping for April-July 2021 security updates
- Beginning to push visual updates to Settings to main
- Updated unicorn Server to sv1.3.5
  - includes aforementioned security update prep
  - rebuild due to serious error where, in some cases, GUI would crash upon adding a new user to the system
  - patched additional graphical bugs

### unicorn 1.3.6 (test ended: March 30, 2021)
- Dropped support for most processors released in 2009 and prior (.05% of our user base). These devices are now unsupported though can still run unicorn 1.3.5 and earlier, and they won't be covered with security updates after April 2nd, 2021.
  - To clarify, Intel processors launched in 2010 and later is still fully supported. AMD processors, however, are currently not compatible.
- Performance improvements for devices released in 2010 and later.
- Important security fixes for January-March 2021. These have been backported to unicorn 1.3.4 for the aforementioned unsupported devices.
- Updated unicorn Server to sv1.3.4.