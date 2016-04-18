
# protodoc

[![Build Status](https://img.shields.io/travis/coreos/protodoc.svg?style=flat-square)][cistat] [![Godoc](http://img.shields.io/badge/go-documentation-blue.svg?style=flat-square)][protodoc-godoc]

protodoc generates Protocol Buffer documentation.

```
go get -v -u github.com/coreos/protodoc

prodoc ./parse/testdata --language-options="Go,C++,Java,Python" --title="testdata" --target-path="./sample.md"
```

Note that parser only understands the minimum syntax
of Protocol Buffer (just enough to generate documentation).

For full featured parser, please check out https://github.com/golang/protobuf.

[cistat]: https://travis-ci.org/coreos/protodoc
[protodoc-godoc]: https://godoc.org/github.com/coreos/protodoc

