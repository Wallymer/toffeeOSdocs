---
title: Release Lifecycle
---

We've updated our archetecture codes! Read more [about the change here](/api/release-targets/#architecture-codes)!

## Currently Supported InDev Builds
| Channel | OS Version | Build | Kernel Version | Date Released | Support End Date | LTS? | Architecture |
|---------|------------|-------|----------------|---------------|------------------|------|------------|
| Alpha | 1.7.0 | 170Y1 | [v5.10.95](https://git.kernel.org/pub/scm/linux/kernel/git/stable/linux.git/commit/?h=v5.10.95&id=77656fde3c0125d6ef6f7fb46af6d2739d7b7141) | February 1, 2022 | To be determined | No | x86_64 |
| Alpha | 1.6.6 (x86) LTS | 166X1 | [v5.4.175](https://git.kernel.org/pub/scm/linux/kernel/git/stable/linux.git/commit/?h=v5.4.175&id=7cdf2951f80d189e9a0a5b6836664ccc8bfb2e7e) | February 1, 2022 | March 1, 2022 (^) | Yes | x86 (final release) |
| Beta | 1.6.5 (x86_64) | 165Y2 | [v5.10.95](https://git.kernel.org/pub/scm/linux/kernel/git/stable/linux.git/commit/?h=v5.10.95&id=77656fde3c0125d6ef6f7fb46af6d2739d7b7141) | February 1, 2022 | To be determined | No | x86_64 |
| Beta | 1.6.5 (x86) LTS | 165X2 | [v5.4.175](https://git.kernel.org/pub/scm/linux/kernel/git/stable/linux.git/commit/?h=v5.4.175&id=7cdf2951f80d189e9a0a5b6836664ccc8bfb2e7e) | February 1, 2022 | March 1, 2022 (^) | Yes | x86 |

## Currently Supported Stable Builds
| Channel | OS Version | Build | Date Released | Support End Date | LTS? | Architecture |
|---------|------------|------------------|---------------|------------------|------|------------|
| Stable | 1.6.4 (x86_64) | 163Y4 | January 12, 2022 | To be determined | No | x86_64 |
| Stable | 1.6.4 (x86) LTS | 163X2 | January 12, 2022 | March 1, 2022 (^) | Yes | x86 |


(^) Stable LTS builds are supplemented by point releases (x.x) and are supported until at least this date, after which, you will be able to upgrade to the next LTS release (which comes out around every three months).

___

## Archived & Unsupported Builds
We are no longer showing **all** of these directly on the doc in order to reduce confusion. We plan to list the most recent **Stable** versions below (along with their support end dates) to encourage testers to upgrade.

| Channel | OS Version | Build | Date Released | Support End Date | LTS? | Architecture |
|---------|------------|------------------|---------------|------------------|------|------------|
| Stable  | 1.6.3 (x86_64) | 163rk2b | January 12, 2022 | To be determined | No | x86_64   |
| Stable | 1.6.3 (x86) LTS | 163rl1 | January 12, 2022 | February 1, 2022 (update to 1.6.4 (x86) LTS) | Yes | x86 |
