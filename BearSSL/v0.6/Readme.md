*BearSSL 0.6* binaries
----------------------

- Sources downloaded from [[BearSSL]: projects/BearSSL/commit - BearSSL-0.6](https://www.bearssl.org/gitweb/?p=BearSSL;a=snapshot;h=8ef7680081c61b486622f2d983c0d3d21e83caad;sf=tgz)
- **!!! Built from modified sources !!!** - as original ones build a *.dll* that doesn't export anything (so it's pretty much useless):
    - Check *${ROOT\_DIR}\BearSSL\BearSSL\0.6\include\bearssl\_win\_exports.h*, included by other files for data export
    - Functions exported by a *.def* file

**Platforms**:
- *Windows*

