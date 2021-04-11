Prebuilt binaries
=================

Prebuilt binaries on different platforms of various products.


**Notes**:

- They are not present in the official repositories
- Some might be customized
- If someone needs:
    1. Another (newer) version of an existing software
    2. A brand new software

    ping me (here, [\[StackOverflow\]: CristiFati](https://stackoverflow.com/users/4788546/cristifati), [\[LinkedIn\]: Cristi Fati](https://www.linkedin.com/in/cristi-fati-6942b844), ... ), and I'll try to add it. Note that it might / will take a while (especially for the 2<sup>nd</sup> item), and in some cases (when too much work / research is needed), it migt not even get materialized
- If someone spots a problem in an existing software, please let me know so I can remediate it *ASAP* (or remove the faulty piece)


**LEGAL INFORMATION**

**Under no circumstances, I** (the entity that built the software in this repository) **should be held responsible for any**:
- Damage or loss that may appear because the software use
- **License terms violation**. Anyone who uses the software is responsible for consulting (and **complying with**) the license terms. If something isn't clear, the software vendor should be contacted, before using the software

For software that I customly built (*e.g.* *.zip* files), I included the license file(s) (*e.g.* *LICENSE\**, *README\**, *COPYING\**, ...) of the software itself (and in some cases of any additional software that it uses) in the package. <br>**But** for some software that automatically generates the build artefacts (*e.g.* *.whl* files), and doesn't include the license file(s), in order to avoid modifying the build process, I didn't. Instead, I uploaded the files next to the artefacts, so they are easily accessible.


**DETAILS**

***Win* specific** (generics that apply unless otherwise specified):

- **Archive (*.zip*) packages should typically be unpacked in**:
    - **"*%ProgramFiles%*"**
    - **"*%ProgramFiles(x86)%*" for *32bit* binaries on *64bit* *OS* (which is equivalent to *%ProgramFiles%* in *32bit* processes)**
- Files in the archive are organized in a folder structure *${VENDOR}/${SOFTWARE}/${VERSION}/...*. Often, *${VENDOR}* and *${SOFTWARE}* are the same
    - The *bin* directory of such an "installation" could be added to *%PATH%* for convenience
- *MS **UCRT*** (<i><b>U</b>niversal <b>C</b> <b>R</b>un<b>T</b>ime</i> (from *Visual Studio 2015* **or newer**)) is used for builds
    - Binaries are typically linked against the **dynamic** *UCRT* version. In that case, the *Visual C Redistributable* (currently (*URL* might change in the future) available at [[MS.Support]: The latest supported Visual C++ downloads](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads)) is required on the target system

