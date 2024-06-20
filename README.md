# parse-dimacs

A DIMACS CNF parser library, implemented with Parsec 3, using ByteStrings.
DIMACS CNF is a file format for describing constraint problems in
conjunctive normal form.

# Profiling

Comment in the Executable in the `parse-dimacs.cabal` file.
Run the pdtest binary on a CNF file with `+RTS -p` at the end.

```
dist-newstyle/build/x86_64-osx/ghc-9.6.5/parse-dimacs-1.3/x/pdtest/build/pdtest/pdtest test.cnf +RTS -p
```

This produces a `pdtest.prof`.
