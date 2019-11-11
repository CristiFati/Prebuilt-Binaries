*Cryptography* *.whl*s
----------------------

[[GitHub]: pyca/cryptography - cryptography is a package designed to expose cryptographic primitives and recipes to Python developers. https://cryptography.io](https://github.com/pyca/cryptography):
- Includes OpenSSL libraries
    - They're renamed (to avoid conflicts with default ones)
    - Dynamically links to them

More details about the build process can be found at [[SO]: OpenSSL FIPS\_mode\_set not working in Python cryptography library (@CristiFati's answer)](https://stackoverflow.com/questions/58228435/openssl-fips-mode-set-not-working-in-python-cryptography-library/58311407#58311407).

