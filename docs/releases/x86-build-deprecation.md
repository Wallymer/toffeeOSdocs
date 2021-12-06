## x86 build support
For the entire 3 years we've been building unicorn, we've always included a 32-bit (x86) of the operating system for compatibility purposes. Our goal was to support as many systems as feasibly possible - and we did. While we are certainly proud of this, we realized it significantly impacts our development time and resiliency to resolve bugs on two incredibly different codebases. 

x86-only systems are becoming more and more rare as time goes on. So we're getting rid of the added stress (and ultimately, "busy work"): with unicorn 1.5, we have deprecated support for the x86 builds. And once unicorn 1.8 is rolled to the Stable ring (taking 1.7's place), x86 builds will no longer be supported.

We realize this change is difficult. But x86 systems are unpopular now and 64-bit (x86_64) is the way to go for any software release.

## FAQ
**Q: Will 32-bit app support go away?**  
A: No, 32-bit apps will continue to be supported for backwards compatibility reasons, even after this change.

**Q: Will there be security updates pushed out after it is deprecated?**  
A: Yes, we'll continue pushing out features updates until unicorn 1.7, after which point, only security/performance/stability updates will be rolled out. x86 systems will not get unicorn 1.8.

**Q: Why did you extend the 32-bit deprecation date**  
A: As requested by testers, it gives us (and them) a bit more buffer room to upgrade systems, and refine other branches of development to make even more changes before pulling the plug. Feature updates and compatibility, however, will be limited.

## Deprecation Roadmap
(**could be subject to change at any time!**)

**UPDATED TIMELINE BELOW**
- unicorn 1.4.2-x86-R2: x86 emergency build for Canary 2, marked as Release 2. Last 1.4 emergency fix to be x86 only on a non-deprecated release.
- unicorn 1.5-x86: x86 build will be deprecated; software support continues with feature updates, though you will only be able to upgrade existing x86 builds. No new ISOs will be distributed to ring testers. "-x86" will be added to the build string in order to differentiate the versions on our end, since there will now be two different branches.
- unicorn 1.5.1-x86: performance and stability update
- unicorn 1.5.2-x86: security update
  - unicorn Server 1.5.2-x86: final release; no more Server builds will be made for the x86 architecture, and the application to interface with Server will be removed in unicorn 1.6-x86. If Server users would like to continue getting updates, or support their unicorn Production systems, they will need to switch to a 64-bit version past this point.
- unicorn 1.6.1-x86: feature update (with removal of the Server Communicator application)
- unicorn LTS 1.6.2-x86: LTS performance, stability, and security update
- unicorn LTS 1.6.3-x86: LTS performance, stability, and security update
- unicorn LTS 1.6.4-x86: LTS performance, stability, and security update
- unicorn LTS 1.6.5-x86: LTS performance, stability, and security update
- unicorn LTS 1.6.6-x86: LTS performance, stability, and security update
- unicorn LTS 1.7-x86: feature update; LTS performance, stability, and security update
- unicorn LTS 1.7.1-x86: LTS performance, stability, and security update
- unicorn LTS 1.7.2-x86: LTS performance, stability, and security update
- unicorn LTS 1.7.3-x86: LTS performance, stability, and security update
- unicorn LTS 1.7.4-x86: LTS performance, stability, and security update
- unicorn LTS 1.7.5-x86: LTS performance, stability, and security update
- unicorn LTS 1.8-x86: feature update; LTS performance, stability, and security update
- unicorn LTS 1.8.1-x86: LTS performance, stability, and security update
- unicorn LTS 1.8.2-x86: LTS performance, stability, and security update
- unicorn LTS 1.8.3-x86: LTS performance, stability, and security update
- unicorn LTS 1.8.4-x86: LTS performance, stability, and security update
- unicorn LTS 1.8.5-x86: LTS performance, stability, and security update
- unicorn LTS 1.8.6-x86: **final** LTS performance, stability, and security update
