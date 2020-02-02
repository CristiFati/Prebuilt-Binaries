Prebuilt binaries
=================

Prebuilt binaries on different platforms of various products.


**Notes**:

- They are not present in the official repositories
- Some might be customized

***Win* specific** (generics that apply unless otherwise specified):

- Archive (*.zip*) packages should typically be unpacked in *%ProgramFiles%* (*%ProgramFiles(x86)%* for *32bit* binaries on *64bit* *OS*)
    - Files in the archive are organized in a folder structure *${VENDOR}/${SOFTWARE}/${VERSION}/...*. Often, *${VENDOR}* and *${SOFTWARE}* are the same
    - The *bin* directory of such an "installation" could be added to *%PATH%* for convenience
- *MS **UCRT*** (***U**niversal **C** **R**un**T**ime* (from *Visual Studio 2015* **or newer**)) is used for builds
    - Binaries are typically linked against the **dynamic** *UCRT* version. In that case, the *Visual C Redistributable* ([[MS.Support]: The latest supported Visual C++ downloads](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads)) is required on the target system

