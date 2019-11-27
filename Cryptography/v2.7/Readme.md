*Cryptography 2.7* *.whl*s
--------------------------

- Sources downloaded from [[PyPI]: cryptography - cryptography-2.7.tar.gz](https://files.pythonhosted.org/packages/c2/95/f43d02315f4ec074219c6e3124a87eba1d2d12196c2767fadfdc07a83884/cryptography-2.7.tar.gz)
- Includes OpenSSL libraries
    - They're renamed (to avoid conflicts with default ones)
    - Dynamically links to them

More details about the build process can be found at [[SO]: OpenSSL FIPS\_mode\_set not working in Python cryptography library (@CristiFati's answer)](https://stackoverflow.com/questions/58228435/openssl-fips-mode-set-not-working-in-python-cryptography-library/58311407#58311407).

