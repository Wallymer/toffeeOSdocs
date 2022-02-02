---
title: Package Managers
---

Package Managers are arguably one of the most fundamental parts of any distribution. Lucky for you, we've got two!

## toffget

``toffget`` is our signature package manager, and where (most of) the fundamental packages for toffeeOS are maintained. These include:
  - security/authentication-related packages
  - packages for various features, including Android apps

You can check for updates to various packages by performing the following action in Console/Terminal apps:

```
sudo toffget fetch --all
```

To apply ("snag") any updates ``fetch`` receives:

```
sudo toffget snag-new -y
```

To purge a badly-behaving update from your system (only use the ``--rm-user-data`` flag if the package you're trying to remove stores its data in the /home folder):

```
sudo toffget purge (package-name) --rm-user-data -y
```

## RPM (DNF)
Support for the RPM package manager (which users can interface with using ``dnf``) will be added in toffeeOS Development Version 1.7 for 32/64-bit releases. 
It will **not** be supported in toffeeOS Development Version 1.7.1, 1.7.2, or 1.7.3 test builds for ARM.

We've forked both the [RPM](https://github.com/Wallymer/rpm) and [DNF](https://github.com/Wallymer/dnf) source repos (both links included here are the public mirrors, our primary forks are hosted internally on our own servers), with the plan being to fetch updates to the package managers periodically with upstream and push applicable updates out to testers.
