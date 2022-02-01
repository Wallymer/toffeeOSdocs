---
title: Current Release Notes
---

## toffeeOS Dev Version - Alpha Channel
These releases are currently in-ring and are [supported](/releases/lifecycle/).

### toffeeOS 1.7.0
| **Released** February 1, 2022 for x86_64 (64-bit) systems |
|--------------------------------|
| **Build**: 165Y2 |
| **LTS Support Ends On** March 1, 2021 (Stable) |

- updated kernel to latest stable release for ``5.10.y`` as of this changelog ([kernel 5.10.95](https://github.com/Wallymer/linux-stable/commit/77656fde3c0125d6ef6f7fb46af6d2739d7b7141))
- new components have now been implemented at a kernel level:
    - scheduler (``wallymer-sysscheduler``) changes for better performance under certain workloads
    - improved hardware RAID support
    - network drivers for certain Wi-Fi 6 capable cards
    - hybrid graphics processing engine (``wallymer-hybridgfxeng``) which allows the system to move tasks freely between integrated and discrete GPUs without input from the user. This can be disabled in Settings.
    - new process allocation system to limit the amount of resources required by the system.

### toffeeOS 1.6.6 (x86) LTS
| **Released** February 1, 2022 for x86 (32-bit) systems |
|--------------------------------|
| **Build**: 166X1 |
| **LTS Support Ends On** March 1, 2021 (Stable) |

Final release for x86 architecture. We recommend upgrading at least 3 months after this release hits Stable.

- this release contains some components of ``1.7.0``, including
    - scheduler changes for better performance under certain workloads
    - new process allocation system to limit the amount of resources required by the system.
- Linux ``5.4.y`` (we will continue to service the kernel until at least June 2022)
- security fixes
- bug fixes

## toffeeOS Dev Version - Beta Channel
These releases are currently in-ring and are [supported](/releases/lifecycle/). 

### toffeeOS 1.6.5
| **Released** February 1, 2022 for x86_64 (64-bit) systems |
|--------------------------------|
| **Build**: 165Y2 |
| **LTS Support Ends On** March 1, 2021 (Stable) |

- bug fixes

### toffeeOS 1.6.5 (x86) LTS
| **Released** January 12, 2022 for x86 (32-bit) systems |
|--------------------------------|
| **Build**: 165X2 |
| **LTS Support Ends On** March 1, 2021 (Stable) |

- bug fixes


## toffeeOS Dev Version - Stable Channel
These releases are currently in-ring and are [supported](/releases/lifecycle/). 

### toffeeOS 1.6.4
| **Released** February 1, 2022 for x86_64 (64-bit) systems |
|--------------------------------|
| **Build**: 163Y4 |
| **LTS Support Ends On** March 1, 2021 (Stable) |

- added new integrated controls for Syncfon in the system manager.
- (Linux) Linux ``kernel`` updated to version ``5.10`` from version ``5.4``.

### toffeeOS 1.6.4 (x86) LTS
| **Released** February 1, 2022 for x86 (32-bit) systems |
|--------------------------------|
| **Build**: 163X2 |
| **LTS Support Ends On** March 1, 2021 (Stable) |

- (Linux) unicorn LTS 1.6.4 remains on Linux ``kernel`` version ``5.4``.
- deprecated `syncfon` package officially for 32-bit systems.
