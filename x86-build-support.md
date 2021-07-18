## x86 build support
For the entire 3 years we've been building unicorn, we've always included a 32-bit (x86) of the operating system for compatibility purposes. Our goal was to support as many systems as feasibly possible - and we did. While we are certainly proud of this, we realized it significantly impacts our development time and resiliency to resolve bugs on two incredibly different codebases. 

x86-only systems are becoming more and more rare as time goes on. So we're getting rid of the added stress (and ultimately, "busy work"): with unicorn 1.5, we have deprecated support for the x86 builds. And once unicorn 1.8 is rolled to the Beta ring (taking 1.7's place), x86 builds will no longer be supported.

We realize this change is difficult. But x86 systems are unpopular now and 64-bit (x86_64) is the way to go for any software release.

## FAQ
**Q: Will 32-bit app support go away?**  
A: No, 32-bit apps will continue to be supported for backwards compatibility reasons, even after this change.

**Q: Will there be security updates pushed out after it is deprecated?**  
Yes, we'll continue pushing out features updates until unicorn 1.7, after which point, only security/performance/stability updates will be rolled out. x86 systems will not get unicorn 1.8.

## Deprecation Roadmap
(**could be subject to change at any time!**)
- unicorn 1.5-x86: x86 build will be deprecated; software support continues with feature updates, though you will only be able to upgrade existing x86 builds. No new ISOs will be distributed to ring testers. "-x86" will be added to the build string in order to differentiate the versions on our end, since there will now be two different branches.
- unicorn 1.5.1-x86: performance and stability update
- unicorn 1.5.2-x86: security update
  - unicorn Server 1.5.2-x86: final release; no more Server builds will be made for the x86 architecture, and the application to interface with Server will be removed in unicorn 1.6-x86. If Server users would like to continue getting updates, or support their unicorn Production systems, they will need to switch to a 64-bit version past this point.
- unicorn 1.6-x86: feature update (with removal of the Server Communicator application)
- unicorn 1.6.1-x86: performance and stability update
- unicorn 1.6.2-x86: security update
- unicorn 1.7-x86: final feature update
- unicorn 1.7.1-x86: non-LTS performance and stability update
- unicorn 1.7.2-x86: non-LTS performance and stability update
- unicorn LTS 1.7.3-x86: final non-long term support (LTS) security update; efforts will be focused on security for 3 months per update, with one last push for performance and stability before the final x86 release.
  - with this update, users on x86 builds will be immediately swapped to the "unicorn LTS" update channel. We recommend that they install a 64-bit build to continue receiving updates, and use this extra time as a chance to transition!
  - updates will continue, once a month, for 6 months after the channel switch.
  - users will not receive unicorn 1.8 and cannot install that version on their devices.
- unicorn LTS 1.7.4-x86: LTS security update
- unicorn LTS 1.7.5-x86: LTS security update
- unicorn LTS 1.7.6-x86: LTS security update
- unicorn LTS 1.7.7-x86: LTS security update
- unicorn LTS 1.7.8-x86: LTS performance/stability update
- unicorn LTS 1.7.9-x86: final LTS security, performance, and stability update
  - at this stage, the x86 to x86_64 only transition will be completed, and unicorn 1.8 will be released to testers.
  - we recommend all users upgrade to a 64-bit (x86_64) build by two months after its release.