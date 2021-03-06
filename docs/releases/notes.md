---
title: Current Release Notes
---

## toffeeOS Dev Version - Alpha Channel
These releases are currently in-ring and are [supported](/releases/lifecycle/).

### toffeeOS 1.7.1 for ARM
| **Released** February 6, 2022 for x86_64 (64-bit) systems |
|--------------------------------|
| **Build**: 170A1 |

- initial *test* release for ARM processors (currently supported: Snapdragon, Apple M1)
    - no support for Apple's M1 Pro or M1 Max chips at this time
- Some software may not work as intended.
    - only the [toffget package manager](/features/package-managers/#toffget) is available in ARM test builds (for now).

### toffeeOS 1.7.0
| **Released** February 1, 2022 for x86_64 (64-bit) systems |
|--------------------------------|
| **Build**: 170Y1 |
| **LTS Support Ends On** March 1, 2022 (Stable) |

- updated kernel to latest stable release for ``5.10.y`` as of this changelog ([kernel 5.10.95](https://git.kernel.org/pub/scm/linux/kernel/git/stable/linux.git/commit/?h=linux-5.10.y&id=77656fde3c0125d6ef6f7fb46af6d2739d7b7141))
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
| **LTS Support Ends On** March 2, 2022 (Stable) |

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
| **LTS Support Ends On** March 2, 2022 (Stable) |

- bug fixes

### toffeeOS 1.6.5 (x86) LTS
| **Released** January 12, 2022 for x86 (32-bit) systems |
|--------------------------------|
| **Build**: 165X2 |
| **LTS Support Ends On** March 2, 2022 (Stable) |

- bug fixes


## toffeeOS Dev Version - Stable Channel
These releases are currently in-ring and are [supported](/releases/lifecycle/). 

### toffeeOS 1.6.4
| **Released** February 1, 2022 for x86_64 (64-bit) systems |
|--------------------------------|
| **Build**: 163Y4 |
| **LTS Support Ends On** March 2, 2022 (Stable) |

- added new integrated controls for Syncfon in the system manager.
- (Linux) Linux ``kernel`` updated to version ``5.10`` from version ``5.4``.

### toffeeOS 1.6.4 (x86) LTS
| **Released** February 1, 2022 for x86 (32-bit) systems |
|--------------------------------|
| **Build**: 163X2 |
| **LTS Support Ends On** March 2, 2022 (Stable) |

- (Linux) unicorn LTS 1.6.4 remains on Linux ``kernel`` version ``5.4``.
- deprecated `syncfon` package officially for 32-bit systems.
