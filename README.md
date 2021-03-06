Fmt — OCaml Format pretty-printer combinators
-------------------------------------------------------------------------------
Release %%VERSION%%

Fmt exposes combinators to devise `Format` pretty-printing functions.

Fmt depends only on the OCaml standard library. It is distributed
under the BSD3 license.

Home page: http://erratique.ch/software/fmt  
Contact: Daniel Bünzli `<daniel.buenzl i@erratique.ch>`

## Installation

Fmt can be installed with `opam`:

    opam install fmt

If you don't use `opam` consult the [`opam`](opam) file for build
instructions.

## Documentation

The documentation and API reference is automatically generated by
`ocamldoc` from the interfaces. It can be consulted [online][5]
and there is a generated version in the `doc` directory of the
distribution.

[5]: http://erratique.ch/software/fmt/doc/

## Sample programs

If you installed Fmt with `opam` sample programs are located in
the directory `opam config var fmt:doc`.

In the distribution sample programs are located in the `test`
directory of the distribution. They can be built with:

    ocamlbuild -use-ocamlfind test/tests.otarget

The resulting binaries are in `_build/test`.

- `test.native` tests the library, nothing should fail.
