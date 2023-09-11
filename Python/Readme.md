*Python* binaries
-----------------

[Python](https://www.python.org)

- The general idea behind this was to have available *pc032* builds, which are no longer provided by default (and the build process (including setup) might be painful)
- Builds (and tests) done on (check directory structure):
    - *Ubuntu 18.04*
    - *Ubuntu 20.04*
    - *Ubuntu 22.04*
- Built (**cross**) on *pc064* platforms
- **NOT tested** on *pc032* machines
- On *pc064* machines, the *pc032* version of *LibC* must be installed. Then, each extension module has its own dependencies, that (obviously) must be present in order for it to be loaded
    - *SSL* and *HashLib* were built with default *OpenSSL*. If not available on a platform, this repository provides several versions
- If binaries not present for a certain (new) platform, it's because the ones existing in most recent before it, work
- *pc064* binaries (where present), are for platforms where that particular version is not supported (provided), and building them was a *pc032* build prerequisite
- Sources checked out in a branch from [[GitHub]: CristiFai/cpython](https://github.com/CristiFati/cpython) (fork of official *repo* - select / checkout the appropriate tag for each version)

**Platforms**:
- *Linux*

