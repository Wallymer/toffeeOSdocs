## Changes to Release Channels  
We're changing the names and purposes of our Release Channels effective September 2021. This brings clarity to our software development structure and better describes the channels and their purposes of existence.

| Old Channel Name | Old Channel Purpose | New Channel Name | New Channel Purpose | 
|------------------|---------------------|------------------|---------------------|
| *Beta* | To test PreRel (pre-release) versions of the codename "unicorn" operating system. | **Stable** | To test stable versions of the prerelease codename "unicorn" operating system. |
| *Canary* | To test the next Beta versions of the codename "unicorn" operating system. | **Beta** | To test PreRel (pre-release) versions of the codename "unicorn" operating system. | **Stable** | To test more stable versions of the prerelease codename "unicorn" operating system. |
| *Dev* | To test the alpha builds "hot off the press" from our team of the codename "unicorn" operating system. | **Alpha** | To test the alpha builds "hot off the press" from our team of the codename "unicorn" operating system. |

Users on the previous Beta channel will be automatically moved to the new Beta channel unless they choose to move to Stable in the software update pane (Any downgrades, should there be any required, are possible for these channels as they're currently testing the same release version.)

All users on the previous Canary and Dev channels will be opted in to the new Beta and Alpha channels respectively automatically with no prompt (Downgrades will not be possible for Alpha channel users.)

Despite the Stable branding, we have no plans to release a public beta at this time due to some instability with the current Stable release, unicorn Development Version 1.5.
