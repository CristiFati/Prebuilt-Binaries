*LibreSSL* *.bin*s
------------------

[LibreSSL](https://www.libressl.org)

- Sources downloaded from [[OpenBSD.FTP]: /pub/OpenBSD/LibreSSL](https://ftp.openbsd.org/pub/OpenBSD/LibreSSL)
- Should be unpcaked in "***C:\Program Files***". That is because of *OPENSSLDIR* (yes, it's not a mistake) macro which contains the installation path, and was embedded in the binaries at build time. Of course, unpacking in other locations is possible, but some features might not work (e.g. finding *openssl.cnf*, ...)

