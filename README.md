pandoc-japanese-docx - Japanese Docx reader for pandoc
=======================================================

[![Build Status](https://travis-ci.org/konn/pandoc-japanese-docx.svg?branch=master)](https://travis-ci.org/konn/pandoc-japanese-docx) 
[![pandoc-japanese-docx](http://img.shields.io/hackage/v/pandoc-japanese-docx.svg)](http://hackage.haskell.org/package/pandoc-japanese-docx)

## What is this?
Enhanced Pandoc Docx reader with Japanese markup supported.

Currently pandoc does not provide environment representing
Japanese writings (such as ruby, horizontal-in-vertical and
side dots emphasis), so the resulting pandoc AST carries
such data as classes and attributes in `Span`{.haskell}.
Read source code for more detail.

## Install

```sh
$ cabal install pandoc-japanese-docx
```

## Licence

GPL
