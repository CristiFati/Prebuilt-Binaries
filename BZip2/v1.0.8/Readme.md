*BZip2 1.0.8* *.bin*s
---------------------

- Sources downloaded from [[SourceWare.BZip2]: bzip2-1.0.8.tar.gz](https://sourceware.org/pub/bzip2/bzip2-1.0.8.tar.gz)
- Modified main header file to:
    - Also produce a usable *libbz2.dll* (which doesn't happen *OOTB*)
    - Declare the functions as *\_\_cdecl*

