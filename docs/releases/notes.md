---
title: Current Release Notes
---
## toffeeOS Dev Version Alpha Channel
These releases are currently in-ring and are [supported](/releases/lifecycle/).

### toffeeOS Dev Version 1.6.4
| **Released** December 14, 2021 for x86_64 systems |
|--------------------------------|
| **Build**: 163rk3 |

64-bit only.
- System: December security patches
- Android Subsystem: security updates for November-December 2021

| **Released** December 4, 2021 for x86_64 systems |
|--------------------------------|
| **Build**: 163rk2 | 

**Please update to build 163rk3 for important fixes.**

- added new integrated controls for Syncfon in the system manager.
- (Linux) Linux ``kernel`` updated to version ``5.10`` from version ``5.4``.

### toffeeOS Dev Version 1.6.4 LTS
| **Released** December 4, 2021 for x86 (32-bit) systems |
|--------------------------------|
| **Build**: 163rl2 |
| **LTS Support Ends On** March 1, 2021 (Stable) |

- (Linux) unicorn LTS 1.6.4 remains on Linux ``kernel`` version ``5.4``.
- deprecated `syncfon` package officially for 32-bit systems.

## toffeeOS Dev Version Beta Channel
These releases are currently in-ring and are [supported](/releases/lifecycle/). 

### toffeeOS Dev Version 1.6.3
| **Released** December 15, 2021 for x86_64 systems |
|--------------------------------|
| **Build**: 163rk2b |

64-bit only. x86 (32-bit) systems already have the latest fixes included in this update.

- bug fixes
	- fixed system instability bug with storing files on spinning media (hard drives) under the deprecated ext3 file system. 
- System: December security patches
- Android Subsystem: security updates for November-December 2021

| **Released** December 4, 2021 for x86_64 systems |
|--------------------------------|
| **Build**: 163rk1 |
**Please update to build 163rk2b for important fixes.**

- bug fixes
	- this release fixes an issue with UX in the Settings app
	- this release fixes an issue where, in some cases, Syncfon would crash upon automatic sync with a narwhal client device.
	- this release addresses an issue with `apt` and the graphical package manager that allowed users to effectively destroy `unicorn-desktop` (and all related) packages, removing access to their desktop environment.
- performance improvements
- new system requirements announced earlier this year are now enforced.

### toffeeOS Dev Version 1.6.3 LTS
| **Released** December 4, 2021 for x86 (32-bit) systems |
|--------------------------------|
| **Build**: 163rl1 |
| **LTS Support Ends On** March 1, 2021 (Stable) |

- unicorn LTS is available as upgrade-only for x86 systems as of right now, no ISOs are being distributed. This is easily worked around by grabbing an older ISO from the Jira and going from there, but we aren't providing any directly.
- bug fixes
	- this release fixes an issue with UX in the Settings app
	- this release addresses an issue with `apt` and the graphical package manager that allowed users to effectively destroy `unicorn-desktop` (and all related) packages, removing access to their desktop environment.

## toffeeOS Dev Version Stable Channel
These releases are currently in-ring and are [supported](/releases/lifecycle/).

### toffeeOS Dev Version 1.6.2
| **Released** December 4, 2021 |
|--------------------------------|
| **Build**: 161rk2 |

- bug fixes
	- this release fixes an issue with UX in the Settings app
	- this release fixes an issue where, in some cases, Syncfon would crash upon automatic sync with a narwhal client device.
- performance improvements
- new system requirements announced earlier this year are now enforced.

### toffeeOS Dev Version 1.6.2 LTS
| **Released** December 13, 2021 |
|--------------------------------|
| **Build**: 161rk3 |

- Android security patches for November-December 2021
- OS security patches for December 2021
- updated software repositories
- patched apt to prevent removing the desktop environment (for real this time)
- Linux kernel updated to stable release of 5.4.164

| **Released** December 4, 2021 |
|--------------------------------|
| **Build**: 161rk2 |

**Please update to build 161rk3 for important security fixes.**

- x86 builds are now LTS by default. We plan to service 1.6.x with new x86 builds (with the latest security enhancements) until at least February 1, 2022.
	- Release notes will be separated from x86_64 versions, as LTS support is paused for the architecture.
	- LTS versions will be branded as "unicorn LTS"
- Server Communicator has been removed from the x86 build.
- users enrolled in a server environment on x86 builds of unicorn will have their user accounts converted into local ones.
- users enrolled in a server environment on x86 builds of unicorn will be prompted to contact their administrators about switching to an x86_64 (64-bit) build.
- Enterprise Mode and Education Mode have been deprecated and are no longer supported on x86 builds. Switch to a x86_64 (64-bit) build to continue receiving support after January 1, 2022. **Updates will continue per the x86 build deprecation timeline.**
