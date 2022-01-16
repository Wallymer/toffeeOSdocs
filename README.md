[![MKDOCS BUILD TEST](https://github.com/Wallymer/toffeeOSdocs/actions/workflows/mkdocsbuild.yml/badge.svg)](https://github.com/Wallymer/toffeeOSdocs/actions/workflows/mkdocsbuild.yml)

## toffeeOS Development Version - Documentation Repository
This is the repository where we publicly mirror our documentation site's source material. If you're interested in helping us make corrections, please feel free to open an issue or pull request!

If you'd like to see the result of our build, please see the [gh-pages](https://github.com/Wallymer/unicorndocs/tree/gh-pages) branch.

Please see the [LICENSE](LICENSE.md) file for more information on this repository.

## Build Site from Source
We are providing our build mkdocs.yml file and our source files in this repository to encourage the community and to help us fix security flaws, spelling, or other errors in our documentation. 

**We do not permit spinning up any mirrors of our documentation site anywhere on the web. [toffeeosdocs.wallymer.com](https://toffeeosdocs.wallymer.com), and its repositories on the Wallymer GitHub account are the only official places that documentation should be hosted.**

We do, however, allow forks of this repository so long as they are being used for pull requests that you are submitting to us here on GitHub.

These instructions are specific to Ubuntu/Debian, as this is what our developers use internally.

Clone this repository using ``git``:  

```
git clone https://github.com/Wallymer/unicorndocs.git
```

Install ``mkdocs`` through the Terminal:  

```
sudo apt-get install mkdocs
```

Use ``pip`` to install the theme we use:  

```
pip install mkdocs-material
```

Use ``cd unicorndocs`` to head into folder ``git`` made for you.

Finally, make any and all changes, then run this command to spin up a local test server:  

```
mkdocs serve
```
