ocaml-posix-types
=================

[ocaml-posix-types](https://github.com/yallop/ocaml-posix-types)
provides
[ctypes](https://github.com/ocamllabs/ocaml-ctypes)-compatible type
representations for the
[types exposed in `<sys/types.h>`](http://pubs.opengroup.org/onlinepubs/9699919799/basedefs/sys_types.h.html).
The implementation details, such as sizes and alignments, of the types
vary from platform to platform, but the interface of each type
is consistent across platforms.

[![Build Status](https://travis-ci.org/yallop/ocaml-posix-types.svg?branch=master)](https://travis-ci.org/yallop/ocaml-posix-types)
