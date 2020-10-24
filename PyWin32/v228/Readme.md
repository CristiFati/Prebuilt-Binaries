*PyWin32 228* binaries
----------------------

Official ***v228*** (and older) doesn't work with *Python 3.**9***.

- Sources checked out in a branch from *tags/b228* (in a forked *repo*)
- Applied [[GitHub]: mhammond/pywin32 - Ensure we hold the GIL as win32ui initializes and calls back into Python](https://github.com/mhammond/pywin32/commit/a58d0a47b5201f7347afa7465e1a74a623173c6d#diff-463277b58680e924d2eb3486c5ffcdfece92520a691a54d2fd217f20ef166663) on top (patched them)
- As a side note, *9fbc2ed3c0d69aca2475975a599cc316016599d3* and *d37397db6f600b2ca7648d410f4f250cc79ed013* also needed to be applied for the build to succeed (not sure how the official build ran fine without them)

More details can be found at [[SO]: Trying to use win32ui with pywin32 gives: A dynamic link library (DLL) initialization routine failed
 (@CristiFati's answer)](https://stackoverflow.com/questions/64444740/trying-to-use-win32ui-with-pywin32-gives-a-dynamic-link-library-dll-initializ/64509494#64509494).

**Platforms**:
- *Windows*

