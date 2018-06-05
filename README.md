Static native library sameple
=============================


The repository demonstrates a minimal possible static library,
whick is used from 
 - Kotlin/Native (`in.sh`)
 - `main.c` (`inc.sh`)

I created the library to debug a linkage error I saw on macOS: `___isOSVersionAtLeast`.

The code fails to link now, but you may remove macOS version test from `lib.c` to make it work.


Releted Work
============

You may find more information on my blog:

- https://jonnyzzz.com/blog/2018/05/16/link-error/
- https://jonnyzzz.com/blog/2018/06/05/link-error-2/
- https://jonnyzzz.com/blog/2018/05/28/minimalistic-kn/



