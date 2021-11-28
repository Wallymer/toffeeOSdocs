## unicorn Alpha Channel
These releases are currently in-ring and are [supported](https://github.com/OneTwentyFour/unicorndocs/blob/main/Releases/release-support-lifecycle.md). Please click the build to see its changelog.
| Build String | Arch | OS Version Identifier | Date Released |
|--------------|------|-----------------------|---------------|
| [u163x86_64-alpha](#unicorn-1-6-3) | x86_64 | 1.6.3 | November 28, 2021 |
| [ults163x86-alpha](#unicorn-LTS-1-6-3) | x86 | 1.6.3lts-x86 | November 28, 2021 |

### unicorn 1.6.3
| **Released** November 28, 2021 for x86_64 systems |
|--------------------------------|
- bug fixes
	- this release fixes an issue with UX in the Settings app
	- this release fixes an issue where, in some cases, Syncfon would crash upon automatic sync with a narwhal client device.
	- this release addresses an issue with `apt` and the graphical package manager that allowed users to effectively destroy `unicorn-desktop` (and all related) packages, removing access to their desktop environment.
- performance improvements
- new system requirements announced earlier this year are now enforced.

### unicorn LTS 1.6.3
| **Released** November 28, 2021 for x86 (32-bit) systems |
|--------------------------------|
| **LTS Support Ends On** TBD (not released to Stable).|

- unicorn LTS is available as upgrade-only for x86 systems as of right now, no ISOs are being distributed. This is easily worked around by grabbing an older ISO from the Jira and going from there, but we aren't providing any directly.
- bug fixes
	- this release fixes an issue with UX in the Settings app
	- this release addresses an issue with `apt` and the graphical package manager that allowed users to effectively destroy `unicorn-desktop` (and all related) packages, removing access to their desktop environment.

## unicorn Beta Channel
These releases are currently in-ring and are [supported](https://github.com/OneTwentyFour/unicorndocs/blob/main/version-support.md#currently-supported-indev-builds). Please click the build to see its changelog.
| Build String | OS Version Identifier | Date Released |
|--------------|-----------------------|---------------|
| [u162x86_64-beta](#unicorn-1-6-2) | 1.6.2  | November 28, 2021 |
| [ults162x86-beta](#unicorn-1-6-2) | 1.6.2lts-x86 | November 28, 2021 |

### unicorn 1.6.2
| **Released** November 28, 2021 |
|--------------------------------|
- bug fixes
	- this release fixes an issue with UX in the Settings app
	- this release fixes an issue where, in some cases, Syncfon would crash upon automatic sync with a narwhal client device.
- performance improvements
- new system requirements announced earlier this year are now enforced.

**x86 build changes**
- x86 builds are now LTS by default. We plan to service 1.6.x with new x86 builds (with the latest security enhancements) until at least February 1, 2022.
	- Release notes will be separated from x86_64 versions, as LTS support is paused for the architecture.
	- LTS versions will be branded as "unicorn LTS"
- Server Communicator has been removed from the x86 build.
- users enrolled in a server environment on x86 builds of unicorn will have their user accounts converted into local ones.
- users enrolled in a server environment on x86 builds of unicorn will be prompted to contact their administrators about switching to an x86_64 (64-bit) build.
- Enterprise Mode and Education Mode have been deprecated and are no longer supported on x86 builds. Switch to a x86_64 (64-bit) build to continue receiving support after January 1, 2022. **Updates will continue per the x86 build deprecation timeline.**

## unicorn Stable Channel
These releases are currently in-ring and are [supported](https://github.com/Wallymer/unicorndocs/blob/main/version-support.md#currently-supported-stable-builds). Please click the build to see its changelog.
| Build String | OS Version Identifier | Date Released |
|--------------|-----------------------|---------------|
| [u161x86_64-master](#unicorn-1-6-1) | 1.6.1  | November 28, 2021 |
| [u161x86-master](#unicorn-1-6-1) | 1.6.1-x86 | November 28, 2021 |

### unicorn 1.6.1
| **Released** November 28, 2021 |
|--------------------------------|

- bug fixes
- updated to Stable seed to allow users to switch release channels following the [changes we made](https://github.com/Wallymer/unicorndocs/blob/main/changes-to-release-channels.md) earlier this week.
