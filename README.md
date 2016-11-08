# GRAPES: a Generic Environment for P2P Streaming
[![GoDoc](https://godoc.org/github.com/zaninime/go-grapes?status.svg)](https://godoc.org/github.com/zaninime/go-grapes)
[![Build Status](https://travis-ci.org/zaninime/go-grapes.svg?branch=master)](https://travis-ci.org/zaninime/go-grapes)
[![Coverage Status](https://coveralls.io/repos/github/zaninime/go-grapes/badge.svg?branch=master)](https://coveralls.io/github/zaninime/go-grapes?branch=master)

This is a (partial) port of [GRAPES library](https://github.com/netCommonsEU/PeerStreamer-grapes) in pure Go originally developed by [Francesco Zanini] (https://github.com/zaninime/go-grapes).

This package contains the functions needed to decode the GRAPES protocol:
messages, chunks, and RTP stuff. It can be used to mimic the features of
PeerStreamer. Chunk trading isn't implemented yet.


## Download
```shell
go get github.com/netCommonsEU/PeerStreamer-go-grapes
```

This work is BSD-licensed.
