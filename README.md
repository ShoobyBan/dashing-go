dashing
=======

Update: this is a somewhat maintained fork of dashing-go focusing on extending and refactoring. Renamed to conform go naming standards.

A [Go][1] port of [shopify/dashing][2]. Now frameworkless!

To generate a dashboard using this library, please use the [Yeoman dashing-go generator][3].

For a live demo, here's the default [sample dashboard][4].

### Current Status

[![Documentation](https://godoc.org/github.com/shoobyban/dashing?status.svg)](http://godoc.org/github.com/shoobyban/dashing)
[![Go Report Card](https://goreportcard.com/badge/github.com/shoobyban/dashing)](https://goreportcard.com/report/github.com/shoobyban/dashing)
[![Build Status](https://travis-ci.org/ShoobyBan/dashing.svg?branch=master)](https://travis-ci.org/ShoobyBan/dashing)

* All endpoints have been ported over! Full functionality is available.
* For an example of how to write jobs in dashing-go, please refer to the [demo dashboard source][5].

Credits
-------

Much of the code is referenced from [golang-sse-todo][6] by @rwynn.

[1]: http://golang.org
[2]: http://shopify.github.io/dashing
[3]: https://github.com/gigablah/generator-dashing-go
[4]: http://dashing.kuanyen.net
[5]: https://github.com/gigablah/dashing-go-demo
[6]: https://github.com/rwynn/golang-sse-todo
