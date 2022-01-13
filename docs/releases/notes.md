---
title: Current Release Notes
---

## toffeeOS Dev Version - Alpha Channel
These releases are currently in-ring and are [supported](/releases/lifecycle/).

### toffeeOS 1.6.5
| **Released** January 12, 2022 for x86_64 (64-bit) systems |
|--------------------------------|
| **Build**: 165rk1 |
| **LTS Support Ends On** March 1, 2021 (Stable) |

- bug fixes

### toffeeOS 1.6.5 (x86) LTS
| **Released** January 12, 2022 for x86 (32-bit) systems |
|--------------------------------|
| **Build**: 165rl1 |
| **LTS Support Ends On** March 1, 2021 (Stable) |

- bug fixes


## toffeeOS Dev Version - Beta Channel
These releases are currently in-ring and are [supported](/releases/lifecycle/). 

### toffeeOS 1.6.4
| **Released** January 12, 2022 for x86_64 (64-bit) systems |
|--------------------------------|
| **Build**: 163rk4 |
| **LTS Support Ends On** March 1, 2021 (Stable) |

- added new integrated controls for Syncfon in the system manager.
- (Linux) Linux ``kernel`` updated to version ``5.10`` from version ``5.4``.

### toffeeOS 1.6.4 (x86) LTS
| **Released** January 12, 2022 for x86 (32-bit) systems |
|--------------------------------|
| **Build**: 163rl2 |
| **LTS Support Ends On** March 1, 2021 (Stable) |

- (Linux) unicorn LTS 1.6.4 remains on Linux ``kernel`` version ``5.4``.
- deprecated `syncfon` package officially for 32-bit systems.


## toffeeOS Dev Version - Stable Channel
These releases are currently in-ring and are [supported](/releases/lifecycle/). 

### toffeeOS 1.6.3
| **Released** January 12, 2022 for x86_64 (64-bit) systems |
|--------------------------------|
| **Build**: 163rk2b |

- bug fixes
	- this release fixes an issue with UX in the Settings app
	- this release fixes an issue where, in some cases, Syncfon would crash upon automatic sync with a narwhal client device.
	- this release addresses an issue with `apt` and the graphical package manager that allowed users to effectively destroy `unicorn-desktop` (and all related) packages, removing access to their desktop environment.
	- this release fixed a system instability bug with storing files on spinning media (hard drives) under the deprecated ext3 file system. 
- also: some major performance improvements

### toffeeOS 1.6.3 (x86) LTS
| **Released** January 12, 2022 for x86 (32-bit) systems |
|--------------------------------------------------------|
| **Build**: 163rl1 |
| **LTS Support Ends On** March 1, 2021 (Stable) |

- unicorn LTS is available as upgrade-only for x86 systems as of right now, no ISOs are being distributed. This is easily worked around by grabbing an older ISO from the Jira and going from there, but we aren't providing any directly.
- bug fixes
	- this release fixes an issue with UX in the Settings app
	- this release addresses an issue with `apt` and the graphical package manager that allowed users to effectively destroy `unicorn-desktop` (and all related) packages, removing access to their desktop environment.
