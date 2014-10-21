Scholdoc-Texmath
================

### A fork of [Texmath][texmath] for [Scholdoc][scholdoc]

**Current stable version:** 0.1

**Development build status** [![build status][scholarly-devel-travisimage]][travis_stat]  
**Stable build status** [![build status][scholarly-travisimage]][travis_stat]

This package is a fork of [Texmath][texmath]. It is intended to support the
development of [Scholdoc][scholdoc], a fork of [Pandoc][pandoc] that
understands [ScholarlyMarkdown][scholmd]. The [Texmath][texmath] library
provides functions to read and write TeX math, presentation MathML, and OMML
(Office Math Markup Language, used in Microsoft Office). For more information,
consult the original README file of `texmath`, which is moved to [`README-texmath.md`][texmath-readme-blob].

`scholdoc-texmath` is currently just a trivial fork just so it can compile
against [Scholdoc-Types][scholdoc-types] instead of
[Pandoc-Types][pandoc-types], without polluting the `texmath` package namespace
on a user's Cabal build system. In the future, enhancements and modifications
made as part of the [Scholdoc][scholdoc] project will be introduced here first.

This package is currently up to date with [Texmath][texmath] version 0.8

[scholmd]: http://scholarlymarkdown.com
[scholdoc]: https://github.com/timtylin/scholdoc
[scholdoc-types]: https://github.com/timtylin/scholdoc-types
[texmath]: https://github.com/jgm/texmath
[pandoc]: http://johnmacfarlane.net/pandoc/
[pandoc-types]: https://github.com/jgm/pandoc-types
[travis_stat]: https://travis-ci.org/timtylin/scholdoc-texmath
[scholarly-devel-travisimage]: https://travis-ci.org/timtylin/scholdoc-texmath.svg?branch=master
[scholarly-travisimage]: https://travis-ci.org/timtylin/scholdoc-texmath.svg?branch=stable
[texmath-readme-blob]: https://github.com/timtylin/scholdoc-texmath/blob/master/README_TEXMATH.md
