# SparseArrays

[![Build Status](https://github.com/jlapeyre/SparseArrays.jl/workflows/CI/badge.svg)](https://github.com/jlapeyre/SparseArrays.jl/actions)
[![Coverage](https://codecov.io/gh/jlapeyre/SparseArrays.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/jlapeyre/SparseArrays.jl)

This package was created by migrating the `SparseArrays` directory in the Julia standard library
to this stand-alone repository

### Changes

* The uuid in Project.toml was changed so that this repo is recognized as distinct from the package in the standard library.
* Six tests that failed were changed from `@test` to `@test_broken`. These are marked with a comment `GJL`. Why these tests
  fail and what should be done about it remains to be investigated. Four tests fail for the same reason. The remaining two
  failures are each for a separate reason. So, it appears there are three failures to investigate.
  See the issues.
