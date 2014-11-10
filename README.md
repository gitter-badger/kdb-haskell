kdb-haskell
===========
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/jkozlowski/kdb-haskell?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Build Status](https://travis-ci.org/jkozlowski/kdb-haskell.svg?branch=master)](https://travis-ci.org/jkozlowski/kdb-haskell)
[![Coverage Status](https://coveralls.io/repos/jkozlowski/kdb-haskell/badge.png)](https://coveralls.io/r/jkozlowski/kdb-haskell)

kdb+ driver in Haskell.

Status:
* Parser and serializer for most kdb+ types is implemented with good test coverage.

Plans:
* q parser - I would like to be able to parse q into an ast 
  to see if it is possible to add some typing and type inference.
