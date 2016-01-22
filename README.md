Fpath — File paths for OCaml
-------------------------------------------------------------------------------
Release %%VERSION%%

Fpath is an OCaml module for handling file system paths on POSIX and
Windows operating systems. Fpath is independent from any system
library and does not provide operations that need to access the file
system.

Fpath depends on [Astring][1] and is distributed under the BSD3
license.

[1]: http://erratique.ch/software/astring

Home page: http://erratique.ch/software/fpath  
Contact: Daniel Bünzli `<daniel.buenzl i@erratique.ch>`

## Installation

Fpath can be installed with `opam`:

    opam install fpath

If you don't use `opam` consult the [`opam`](opam) file for build
instructions.

## Documentation

The documentation and API reference is automatically generated by
`ocamldoc` from the interfaces. It can be consulted [online][5]
and there is a generated version in the `doc` directory of the
distribution.

[5]: http://erratique.ch/software/fpath/doc/


## Sample programs

If you installed Fpath with `opam` sample programs are located in
the directory `opam config var fpath:doc`.

In the distribution sample programs are located in the `test`
directory of the distribution. They can be built with:

    ocamlbuild -use-ocamlfind test/tests.otarget

The resulting binaries are in `_build/test`.

- `test.native` tests the library, nothing should fail.
