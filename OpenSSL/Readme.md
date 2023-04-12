*OpenSSL* binaries
------------------

[[GitHub]: openssl/openssl - TLS/SSL and crypto library https://www.openssl.org](https://github.com/openssl/openssl)

- Sources downloaded from [[OpenSSL]: Downloads](https://www.openssl.org/source) (including the ***Old Releases** URL*)
- *Win*:
    - Should be unpacked in ***"C:\\Program Files"***. That is because of *OPENSSLDIR* macro which contains the installation path, and was embedded in the binaries at build time. Of course, unpacking in other locations is possible, but some features might not work (e.g. finding *openssl.cnf*, engine *.dll*s, ...)
- *Nix*:
    - Should be unpacked in ***/usr/local*** (**requires *root***) for the same considerations, and also due to ***DT\_RUNPATH* hardcoding**

**Platforms**:
- *Linux*
- *Windows*

