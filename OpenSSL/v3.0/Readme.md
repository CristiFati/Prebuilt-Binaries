*OpenSSL 3.0* *.bin*s
---------------------

- v3.0.0-alpha**1**:

    Applied to original sources (as they don't build *OOTB*):
    - [[GitHub]: openssl/openssl - OpenSSL-3.0.0-alpha1 build fails](https://github.com/openssl/openssl/pull/11774)
    - [[GitHub]: openssl/openssl - Configurations/windows-makefile.tmpl: Fix template code for INSTALL\_MODULES](https://github.com/openssl/openssl/pull/11629)

- v3.0.0-alpha**2**:

    Some (*16*) warnings (`libnonfips-lib-der_digests.obj : warning LNK4006: _der_oid_id_sha256 already defined in libnonfips-lib-der_rsa.obj; second definition ignored`) when creating (*lib*) *libnonfips\_static.lib*, *libcrypto\_static.lib*, *libfips\_static.lib*

