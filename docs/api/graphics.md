## Graphics API
**As of toffeeOS Dev Version 1.6.2 (and later)**, the Vulkan Graphics API will be enabled by default on x86_64 (64-bit) systems, and OpenGL will be deprecated and disabled by default for these systems. It will still be available through other means, such as PPAs, our repos, etc., however.

**In toffeeOS Dev Version 1.8**, the Vulkan Graphics API will become the only API bundled and enabled by default. OpenGL will be removed from repos and PPAs. Should third-party repos include them, we may take action to warn the user that we cannot diagnose any issues regarding OpenGL (through a tip in the Terminal and/or pop-up in userspace) in the future but will not disallow installation.
