## x86 build support
For the few years we've been building unicorn, we've always included a 32-bit (x86) of the operating system for compatibility purposes. While we are certainly proud of this, we realized it significantly impacts our development time and resiliency to resolve bugs on two incredibly different codebases.

x86-only systems are becoming more and more rare as time goes on. For this reason, we've made a difficult decision. With unicorn 1.5, we have deprecated support for the x86 builds. 

We've included our full roadmap to sunsetting and ultimately retiring these builds below.

## Version Deprecation Roadmap
(**could be subject to change at any time!**)
- unicorn 1.5-x86: x86 build will be deprecated; software support continues with feature updates, though you will only be able to upgrade existing x86 builds. No new ISOs will be distributed to ring testers. "-x86" will be added to the build string in order to differentiate the versions on our end, since there will now be two different branches.
- unicorn 1.5.1-x86: performance and stability update
- unicorn 1.5.2-x86: security update
  - unicorn Server 1.5.2-x86: final release; no more Server builds will be made for the x86 architecture, and the application to interface with Server will be removed in unicorn 1.6-x86.
- unicorn 1.6-x86: feature update
- unicorn 1.6.1-x86: performance and stability update
- unicorn 1.6.2-x86: security update
- unicorn 1.7-x86: final feature update
- unicorn 1.7.5-x86: final non-long term support (LTS) security update; efforts will be focused on security for 3 months per update, with one last push for performance and stability before the final x86 release
- unicorn 1.7.6-x86: LTS security update
- unicorn 1.7.7-x86: LTS security update
- unicorn 1.7.8-x86: final security, performance, and stability updates
