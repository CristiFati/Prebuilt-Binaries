*OpenSSL 3.0* binaries
----------------------

- *v3.0.0-alpha**1***:

    Applied to original sources (as they don't build *OOTB*):
    - [[GitHub]: openssl/openssl - OpenSSL-3.0.0-alpha1 build fails](https://github.com/openssl/openssl/pull/11774)
    - [[GitHub]: openssl/openssl - Configurations/windows-makefile.tmpl: Fix template code for INSTALL\_MODULES](https://github.com/openssl/openssl/pull/11629)

- *v3.0.0-alpha**2***:

    Some (*16*) warnings (`libnonfips-lib-der_digests.obj : warning LNK4006: _der_oid_id_sha256 already defined in libnonfips-lib-der_rsa.obj; second definition ignored`) when creating (*lib*) *libnonfips\_static.lib*, *libcrypto\_static.lib*, *libfips\_static.lib*

- *v3.0.0-alpha**5***:

    Warnings:
    - `libnonfips-lib-rand_tsc.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libnonfips-lib-rand_cpu_x86.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libcrypto-lib-ebcdic.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libfips-lib-rand_tsc.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libfips-lib-rand_cpu_x86.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`

- *v3.0.0-alpha**6***:

    Warnings:
    - `libnonfips-lib-rand_tsc.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libnonfips-lib-rand_cpu_x86.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libcrypto-lib-ebcdic.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libfips-lib-rand_tsc.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libfips-lib-rand_cpu_x86.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this libra`
    - `engines\capi.def(5) : warning LNK4093: Drive/Directory component ignored in 'LIBRARY' statement`
    - `capi.exp : warning LNK4070: /OUT:capi-3.dll directive in .EXP differs from output filename 'engines\capi.dll'; ignoring directive`
    - `engines\dasync.def(5) : warning LNK4093: Drive/Directory component ignored in 'LIBRARY' statement`
    - `dasync.exp : warning LNK4070: /OUT:dasync-3.dll directive in .EXP differs from output filename 'engines\dasync.dll'; ignoring directive`
    - `engines\ossltest.def(5) : warning LNK4093: Drive/Directory component ignored in 'LIBRARY' statement`
    - `ossltest.exp : warning LNK4070: /OUT:ossltest-3.dll directive in .EXP differs from output filename 'engines\ossltest.dll'; ignoring directive`
    - `engines\padlock.def(5) : warning LNK4093: Drive/Directory component ignored in 'LIBRARY' statement`
    - `padlock.exp : warning LNK4070: /OUT:padlock-3.dll directive in .EXP differs from output filename 'engines\padlock.dll'; ignoring directive`
    - `providers\fips.def(5) : warning LNK4093: Drive/Directory component ignored in 'LIBRARY' statement`
    - `fips.exp : warning LNK4070: /OUT:fips-3.dll directive in .EXP differs from output filename 'providers\fips.dll'; ignoring directive`
    - `providers\legacy.def(5) : warning LNK4093: Drive/Directory component ignored in 'LIBRARY' statement`
    - `legacy.exp : warning LNK4070: /OUT:legacy-3.dll directive in .EXP differs from output filename 'providers\legacy.dll'; ignoring directive`
    - `test\p_test.def(5) : warning LNK4093: Drive/Directory component ignored in 'LIBRARY' statement`
    - `p_test.exp : warning LNK4070: /OUT:p_test-3.dll directive in .EXP differs from output filename 'test\p_test.dll'; ignoring directive`

- *v3.0.0-alpha**7***:

    Warnings:

    - `libnonfips-lib-rand_tsc.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libnonfips-lib-rand_cpu_x86.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libnonfips-lib-rand_tsc.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libnonfips-lib-rand_cpu_x86.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libcrypto-lib-prov_running.obj : warning LNK4006: ossl_prov_is_running already defined in libnonfips-lib-prov_running.obj; second definition ignored`
    - `libcrypto-lib-prov_running.obj : warning LNK4006: ossl_set_error_state already defined in libnonfips-lib-prov_running.obj; second definition ignored`
    - `libcrypto-lib-prov_running.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libcrypto-lib-md5_sha1.obj : warning LNK4006: md5_sha1_ctrl already defined in libimplementations-lib-md5_sha1.obj; second definition ignored`
    - `libcrypto-lib-md5_sha1.obj : warning LNK4006: md5_sha1_final already defined in libimplementations-lib-md5_sha1.obj; second definition ignored`
    - `libcrypto-lib-md5_sha1.obj : warning LNK4006: md5_sha1_init already defined in libimplementations-lib-md5_sha1.obj; second definition ignored`
    - `libcrypto-lib-md5_sha1.obj : warning LNK4006: md5_sha1_update already defined in libimplementations-lib-md5_sha1.obj; second definition ignored`
    - `libcrypto-lib-md5_sha1.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libcrypto-lib-md5_one.obj : warning LNK4006: MD5 already defined in libimplementations-lib-md5_one.obj; second definition ignored`
    - `libcrypto-lib-md5_one.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libcrypto-lib-md5_dgst.obj : warning LNK4006: MD5_Final already defined in libimplementations-lib-md5_dgst.obj; second definition ignored`
    - `libcrypto-lib-md5_dgst.obj : warning LNK4006: MD5_Init already defined in libimplementations-lib-md5_dgst.obj; second definition ignored`
    - `libcrypto-lib-md5_dgst.obj : warning LNK4006: MD5_Transform already defined in libimplementations-lib-md5_dgst.obj; second definition ignored`
    - `libcrypto-lib-md5_dgst.obj : warning LNK4006: MD5_Update already defined in libimplementations-lib-md5_dgst.obj; second definition ignored`
    - `libcrypto-lib-md5_dgst.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libcrypto-lib-md5-x86_64.obj : warning LNK4006: md5_block_asm_data_order already defined in libimplementations-lib-md5-x86_64.obj; second definition ignored`
    - `libcrypto-lib-md5-x86_64.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libcrypto-lib-ebcdic.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libfips-lib-rand_tsc.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `libfips-lib-rand_cpu_x86.obj : warning LNK4221: This object file does not define any previously undefined public symbols, so it will not be used by any link operation that consumes this library`
    - `engines\capi.def(5) : warning LNK4093: Drive/Directory component ignored in 'LIBRARY' statement`
    - `capi.exp : warning LNK4070: /OUT:capi-3.dll directive in .EXP differs from output filename 'engines\capi.dll'; ignoring directive`
    - `engines\dasync.def(5) : warning LNK4093: Drive/Directory component ignored in 'LIBRARY' statement`
    - `dasync.exp : warning LNK4070: /OUT:dasync-3.dll directive in .EXP differs from output filename 'engines\dasync.dll'; ignoring directive`
    - `engines\loader_attic.def(5) : warning LNK4093: Drive/Directory component ignored in 'LIBRARY' statement`
    - `loader_attic.exp : warning LNK4070: /OUT:loader_attic-3.dll directive in .EXP differs from output filename 'engines\loader_attic.dll'; ignoring directive`
    - `engines\ossltest.def(5) : warning LNK4093: Drive/Directory component ignored in 'LIBRARY' statement`
    - `ossltest.exp : warning LNK4070: /OUT:ossltest-3.dll directive in .EXP differs from output filename 'engines\ossltest.dll'; ignoring directive`
    - `engines\padlock.def(5) : warning LNK4093: Drive/Directory component ignored in 'LIBRARY' statement`
    - `padlock.exp : warning LNK4070: /OUT:padlock-3.dll directive in .EXP differs from output filename 'engines\padlock.dll'; ignoring directive`
    - `providers\fips.def(5) : warning LNK4093: Drive/Directory component ignored in 'LIBRARY' statement`
    - `fips.exp : warning LNK4070: /OUT:fips-3.dll directive in .EXP differs from output filename 'providers\fips.dll'; ignoring directive`
    - `providers\legacy.def(5) : warning LNK4093: Drive/Directory component ignored in 'LIBRARY' statement`
    - `legacy.exp : warning LNK4070: /OUT:legacy-3.dll directive in .EXP differs from output filename 'providers\legacy.dll'; ignoring directive`
    - `test\p_test.def(5) : warning LNK4093: Drive/Directory component ignored in 'LIBRARY' statement`
    - `p_test.exp : warning LNK4070: /OUT:p_test-3.dll directive in .EXP differs from output filename 'test\p_test.dll'; ignoring directive`




**Notes**:
- Starting with *v3.0.0-alpha**3***, **setting *OPENSSL\_FIPS* *env var* has no effect when running *openssl.exe***!

**Platforms**:
- *Windows*

