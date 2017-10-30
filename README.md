# Gorilla WebSocket

Gorilla WebSocket is a [Go](http://golang.org/) implementation of the
[WebSocket](http://www.rfc-editor.org/rfc/rfc6455.txt) protocol.

[![Build Status](https://travis-ci.org/gorilla/websocket.svg?branch=master)](https://travis-ci.org/gorilla/websocket)
[![GoDoc](https://godoc.org/github.com/gorilla/websocket?status.svg)](https://godoc.org/github.com/gorilla/websocket)

### Documentation

* [API Reference](http://godoc.org/github.com/gorilla/websocket)
* [Chat example](https://github.com/gorilla/websocket/tree/master/examples/chat)
* [Command example](https://github.com/gorilla/websocket/tree/master/examples/command)
* [Client and server example](https://github.com/gorilla/websocket/tree/master/examples/echo)
* [File watch example](https://github.com/gorilla/websocket/tree/master/examples/filewatch)

### Status

The Gorilla WebSocket package provides a complete and tested implementation of
the [WebSocket](http://www.rfc-editor.org/rfc/rfc6455.txt) protocol. The
package API is stable.

### Installation

    go get github.com/gorilla/websocket

### Protocol Compliance

The Gorilla WebSocket package passes the server tests in the [Autobahn Test
Suite](http://autobahn.ws/testsuite) using the application in the [examples/autobahn
subdirectory](https://github.com/gorilla/websocket/tree/master/examples/autobahn).
