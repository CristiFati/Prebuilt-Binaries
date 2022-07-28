*Cryptography 2.7* binaries
---------------------------

- Sources downloaded from [[PyPI]: cryptography - cryptography-2.7.tar.gz](https://files.pythonhosted.org/packages/c2/95/f43d02315f4ec074219c6e3124a87eba1d2d12196c2767fadfdc07a83884/cryptography-2.7.tar.gz)
- Built with *OpenSSL-**FIPS** 1.0.2**t*** (***2.0.16***)
- Contains *OpenSSL* *.so*s:
    - They're renamed (to avoid conflicts with default ones)
    - Dynamically linking to them

More details about the build process can be found at [[SO]: OpenSSL FIPS\_mode\_set not working in Python cryptography library (@CristiFati's answer)](https://stackoverflow.com/a/58311407/4788546).

**Platforms**:
- *Linux*

