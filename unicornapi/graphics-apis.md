## Graphics APIs
**As of unicorn 1.5**, unicorn natively supports (and utilizes) the Vulkan Graphics API. OpenGL support is included, but not enabled by default as we recommend using Vulkan. App developers can target either API using the SDK we've bundled into unicorn 1.5.

**Upon release of unicorn 1.6.1 and 1.6.2**, the Vulkan Graphics API will be enabled by default on x86_64 (64-bit) systems, and OpenGL will be deprecated and disabled by default for these systems. It will still be available through other means, such as PPAs, our repos, etc., however.

**In unicorn 1.8**, the Vulkan Graphics API will become the only API bundled and enabled by default. OpenGL will not be able to install on this version of unicorn or later.