# fang - <SUMMARY>

[![Continuous Integration](https://github.com/wroyca/fang/actions/workflows/ci.yml/badge.svg)](https://github.com/wroyca/fang/actions/workflows/ci.yml)
[![Container Registry](https://github.com/wroyca/fang/actions/workflows/cr.yml/badge.svg)](https://github.com/wroyca/fang/actions/workflows/cr.yml)

`fang` is a <SUMMARY-OF-FUNCTIONALITY>.

This file contains setup instructions and other details that are more
appropriate for development rather than consumption. If you want to use
`fang` in your `build2`-based project, then instead see the accompanying
package [`README.md`](<PACKAGE>/README.md) file.

The development setup for `fang` uses the standard `bdep`-based workflow.
For example:

```
git clone .../fang.git
cd fang

bdep init -C @gcc cc config.cxx=g++
bdep update
bdep test
```
